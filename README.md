# Kube Orchestrator in Go

A container orchestration system built in Go, based on the book **“Build an Orchestrator in Go”** by Tim Boring.

## About This Project

This project is a hands-on implementation of the orchestrator described in Tim Boring’s book. The code is being retyped for learning purposes and will later be modified and extended for testing and experimentation.

## What is an Orchestrator?

A container orchestrator is a system that automates the deployment, scaling, and management of containerized applications. This implementation provides insights into how systems like Kubernetes work under the hood.

## Project Status

🚧 **Work in Progress** - Currently working through the book and implementing the core functionality.

### Current Progress

- [ ] Core orchestrator components
- [x] Task scheduling
- [x] Worker management
- [x] API layer
- [ ] CLI interface
- [ ] Custom modifications and testing

## Getting Started

### Prerequisites

- Go 1.21 or higher
- Docker (for container management)
- Basic understanding of containerization concepts

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd kube

# Install dependencies
go mod download

# Build the project
go build -o kube
```

### Running the Orchestrator

```bash
# Run the orchestrator
./kube
```

## Project Structure

```
.
├── worker/          # Worker node implementation
├── manager/         # Manager node implementation
├── task/            # Task definitions and management
├── scheduler/       # Task scheduling logic
├── node/            # Node management
└── main.go          # Entry point
```

## Learning Goals

- Understand the architecture of container orchestrators
- Learn Go’s concurrency patterns in a real-world application
- Explore distributed systems concepts
- Build a foundation for custom orchestration logic

## Future Plans

- Add custom scheduling algorithms
- Implement additional testing scenarios
- Extend functionality beyond the book’s scope
- Document architectural decisions and modifications

## Resources

- **Book**: “Build an Orchestrator in Go” by Tim Boring

## License

This project is for educational purposes. Please refer to the book’s licensing terms for any commercial use.