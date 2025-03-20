# Sample: Proto contracts for Customer service

Part of presentation for Team Convention 2025. The repository of proto files for fictional customer service. It includes Profile and Avatar services.

## Visual Studio Code setup

1. Install [buf cli](https://buf.build/docs/cli/installation/). Feel free to use any appropriate method.
2. Install VS Code plugin [bufbuild.vscode-buf](https://marketplace.visualstudio.com/items?itemName=bufbuild.vscode-buf)

## Git setup

Configure git hooks:
1. Change hooks directory
```
git config --local core.hooksPath .githooks/s
```
2. Configure permissions (on Linux)
```
chmod +x .githooks/pre-commit
```
