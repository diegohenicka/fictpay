## Start project FictPay
### Description


### Dev environment
#### Requirements
- Docker
- VSCode

#### Change Log
- Create README
- Create .gitignore
- Create new git repository
---
- Create Dockerfile
- Create docker-compose
- Create .docker/start.sh
  - List of commands for start new container
- Install extension [Dev Container](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
  - Ctrl + Alt + P
    - Add Dev Container Configuration Files
      - From 'docker-compose-yaml'
      - Select options
        - ZSH Plugins
        - Common Utilities
        - Shell History
        - Keep defautl
    - Configure .devcontainer/decontainer.json
      - Change name
      - Add our extensions in customizations
---