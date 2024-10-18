# Devcontainers with Zed IDE

Zed is super fast, and it looks sharp. Its hard to go back to VScode, but theres no direct support for devcontainers (yet).
You can however use Zed Tasks to get things working.

### Prerequisites
- #### installs nvm (Node Version Manager)
  ```
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
  ```
- #### download and install Node.js (you may need to restart the terminal)
  ```
  nvm install 20
  ```
- #### install devcontainercli
  ```
  npm install -g @devcontainers/cli
  ```
- #### run zed task
  ```
  option + shift + t - Build Dev Container
  option + shift + t - Run Dev Container
  ```
