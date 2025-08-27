## 📚 Documentation & Wiki

This repository includes a comprehensive wiki submodule containing architectural and business documentation:

- **📖 Wiki Access**: The `wiki/` directory contains extensive documentation
- **🔄 Wiki Sync**: Use `./scripts/update-wiki.sh` to sync latest wiki changes
- **📋 Wiki Guide**: See [WIKI.md](WIKI.md) for detailed wiki management instructions

⚠️ **Important**: The wiki is read-only in this repository. Edit content through GitHub's wiki interface, then sync locally using the provided script.


# re9.ai n8n Workflows

## Overview

The n8n Workflows repository contains workflow automation definitions for the re9.ai platform. This repository manages business process automation using n8n, an open-source workflow automation tool, to streamline operations and reduce manual tasks across the platform.

## Key Features

- **Business Process Automation**: Automation of common business processes and workflows
- **Integration Hub**: Centralized management of integrations with external services
- **Workflow Definitions**: Declarative workflow definitions using n8n's visual editor
- **Event-Driven Processing**: Trigger-based processing of business events
- **Error Handling**: Robust error handling and retry mechanisms
- **Monitoring and Logging**: Comprehensive monitoring and logging of workflow execution
- **Version Control**: Git-based version control for workflow definitions

## Technology Stack

- **Workflow Engine**: n8n
- **Data Storage**: PostgreSQL for workflow state and metadata
- **Message Queue**: Redis for workflow triggering and coordination
- **Infrastructure**: Docker, Kubernetes, AWS EKS
- **Version Control**: Git

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/re9-ai/re9ai-n8n-workflows.git
   cd re9ai-n8n-workflows
   ```

2. Install n8n:
   ```bash
   npm install n8n -g
   ```

3. Set up environment variables (refer to `.env.example`)

4. Run n8n:
   ```bash
   n8n
   ```

## Documentation

For detailed documentation, architecture diagrams, and business requirements, see the [wiki](./wiki/) directory.

## Contributing

Please read our [contribution guidelines](wiki/business/CONTRIBUTING.md) before submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
