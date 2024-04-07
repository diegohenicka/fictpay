## Start project FictPay
### Description


### Dev environment
#### Requirements
- Docker
- VSCode

#### Util commands
```bash
chmod +x .docker/start.sh
```

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
- Initialize npm project
- Install dev dependencies
  -  ``` ts-node typescript jest @types/jest @swc/cli @swc/core @swc/jest ```
- Create and configure <code>tsconfig.json</code>
- Create and configure <code>jest.config.json</code>
  - Change transform to use swc
  - Configure <code>rootDir</code> to ./src
- Create <code>src</code> folder
- Create and configure <code>.swcrc</code>