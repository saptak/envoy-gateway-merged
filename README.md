# Docker Desktop Extension for Envoy Gateway

This repository contains the implementation of a Docker Desktop Extension for Envoy Gateway, providing a user-friendly interface to deploy, configure, and manage Envoy Gateway directly from Docker Desktop.

## Project Overview

The Docker Desktop Extension for Envoy Gateway simplifies the process of setting up and managing API gateways for containerized applications. It provides a graphical interface for tasks that would otherwise require complex YAML configurations and command-line operations.

## Implementation Status

This project combines Phase 1 and Phase 2 of the implementation plan:

### Phase 1: Setup and Basic Infrastructure ✅
- Docker Desktop Extension setup and packaging
- Basic UI framework with tabbed interface
- Placeholder components for main features

### Phase 2: Core Functionality ✅
- Backend API for Kubernetes and Envoy Gateway operations
- Gateway management UI components with backend integration
- Configuration editor with template selection and validation
- Route management with CRUD operations
- Monitoring dashboard with mock data visualization

## Deployment Options

This repository includes two deployment options:

1. **React-based UI with Node.js Backend**: The full implementation with all features, but requires additional work to resolve TypeScript compatibility issues.

2. **Simplified HTML-based UI**: A lightweight version that can be immediately deployed to Docker Desktop for basic functionality.

## Getting Started

### Prerequisites

- Docker Desktop with Extensions support
- Kubernetes enabled in Docker Desktop

### Installation

To install the simplified version:

```bash
cd /path/to/repository
docker build -t saptak/envoy-gateway-extension:latest .
docker extension install saptak/envoy-gateway-extension:latest --force
```

## Features

- One-click installation of Envoy Gateway
- Visual configuration editor with templates
- Route management and traffic control
- Real-time monitoring and visualization
- Integration with Docker Desktop's Kubernetes

## Documentation

- [Product Requirements Document](./PRD-Docker-Desktop-Extension-Envoy-Gateway.md)
- [Implementation Plan](./Implementation-Plan-Docker-Desktop-Extension-Envoy-Gateway.md)

## License

[MIT License](LICENSE)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Resources

- [Docker Extensions SDK Documentation](https://docs.docker.com/extensions/extensions-sdk/)
- [Envoy Gateway Documentation](https://gateway.envoyproxy.io/)
- [GitHub Repository](https://github.com/saptak/envoy-gateway-merged)
