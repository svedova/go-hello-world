# Go Hello World Example

This repository contains a simple "Hello, World!" application written in Go. Follow the steps below to build and deploy the project.

## Prerequisites

- [Go](https://golang.org/dl/) installed (version 1.16 or later)
- [Git](https://git-scm.com/) installed

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/go-hello-world.git
   cd go-hello-world
   ```

2. Build the project:

   ```bash
   go build -o dist/server
   ```

3. Run the application locally:

   ```bash
   ./dist/server
   ```

## Deploying with Stormkit

1. Login to your self-hosted Stormkit Instance. Here's [a guide](https://www.stormkit.io/tutorials/how-to-self-host-stormkit-on-hetzner-cloud) to set it up.
2. Import this project from URL
3. Configure the Build Settings:
   - Build command: `go build -o dist/server server.go`
   - Output folder: `./dist`
4. Click Save and Deploy.
