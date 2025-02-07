# Nodus AI

Nodus AI is an open-source workflow automation platform that intelligently connects applications and services, allowing integrations with any local or external data source (such as Google Drive, databases, APIs, and more). With its intuitive, no-code interface, Nodus AI enables seamless automation of repetitive tasks and complex business processes.

## Features

- **Open-Source and Self-Hosted**: Deploy Nodus AI on your own server to maintain full control over your data and privacy.
- **AI-Driven Automation**: Leverage built-in artificial intelligence to enhance workflows, make data-driven decisions, and optimize tasks automatically.
- **Intuitive Visual Interface**: Build workflows easily with a drag-and-drop interface, without the need to write any code.
- **Extensive Integrations**: Connect with over 200 services and data sources, including popular platforms like Google Drive, databases, social media tools, CRMs, and more.
- **Scalability and Customization**: Create custom nodes to extend the platform's capabilities and tailor workflows to your specific needs.

## Getting Started

### Prerequisites

- Docker
- Node.js (if you prefer to run Nodus AI without Docker)

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/nodusai/nodusai.git
    cd nodus-ai
    ```

2. **Set up environment variables**:

    Configure your preferred integrations by creating a `.env` file or modifying the existing example file:

    ```bash
    cp .env.example .env
    ```

3. **Choose your installation method**:

    #### Docker Installation

    1. **Build the Docker image**:

        ```bash
        docker build -t nodus-ai .
        ```

    2. **Run the Docker container**:

        ```bash
        docker run -d -p 8888:8888 nodus-ai
        ```

    3. **Access the application**:

        Open your browser and go to [http://localhost:8888](http://localhost:8888).

    #### Node.js Installation

    1. **Install dependencies**:

        ```bash
        npm install
        ```

    2. **Start the application**:

        ```bash
        npm start
        ```

    3. **Access the application**:

        Open your browser and go to [http://localhost:8888](http://localhost:8888).

## Usage

Once Nodus AI is running, you can:

- **Create Workflows**: Use the drag-and-drop editor to connect apps and automate tasks.
- **Leverage AI**: Enable smart suggestions and workflow optimization powered by AI.
- **Connect Data Sources**: Integrate with any external or local data source by configuring the available nodes.

## Contributing

We welcome contributions to Nodus AI! If you'd like to help improve the platform, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Write tests and code.
4. Submit a pull request with a detailed description of your changes.

Please refer to the [contribution guidelines](#) for more information.

## License

Nodus AI is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

