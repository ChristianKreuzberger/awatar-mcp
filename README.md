# Awatar MCP Project

This repository contains a Model Context Protocol (MCP) implementation. MCP is a protocol designed to facilitate communication between models and tools in a standardized way.

## Getting Started

### Prerequisites

- Visual Studio Code (VS Code) installed on your system.
- Node.js and npm installed.

### Installation

1. Clone this repository:

2. Install dependencies:
   ```bash
   npm install
   ```

### Usage in VS Code

1. Open the project folder in VS Code:
   ```bash
   code .
   ```

2. Ensure the MCP server is running:
   ```bash
   npm start
   ```

3. Build it:
   ```bash
   npm run build
   ```

4. Use the MCP features in VSCode with GitHub copilot, e.g., by putting this into `.vscode/mcp.json`
   ```
   {
        "servers": {
            "my-mcp-4-youtube": {
                "type": "stdio",
                "command": "node",
                "args": [
                    "${workspaceFolder}/dist/index.js"
                ]
            }
        }
    }
   ```

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENCE.md) file for details.