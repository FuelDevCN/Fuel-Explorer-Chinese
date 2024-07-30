# Fuel-Explorer-Chinese
Fuel浏览器中文文档

## 安装依赖

安装所需的依赖项：

### 1. 安装 Node.js

- 下载并安装 [Node.js v20.11.0 或最新稳定版](https://nodejs.org/en/)。
- 我们建议使用 [nvm（Node Version Manager）](https://github.com/nvm-sh/nvm) 来安装 Node.js。

  ```sh
  # 安装 nvm
  curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
  
  # 载入 nvm
  export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
  [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
  
  # 安装指定版本的 Node.js
  nvm install 20.11.0
  
  # 使用指定版本的 Node.js
  nvm use 20.11.0
  ```

### 2. 安装 PNPM

- 下载并安装 [PNPM v8.15.7 或最新稳定版](https://pnpm.io/installation/)。

  ```sh
  # 使用 npm 安装 pnpm
  npm install -g pnpm@8.15.7
  ```

### 3. 安装 Docker

- 下载并安装 [Docker v25.0.3 或最新稳定版](https://docs.docker.com/get-docker/)。
- 下载并安装 [Docker Compose v2.24.6 或最新稳定版](https://docs.docker.com/get-docker/)。

  ```sh
  # 安装 Docker（示例命令，具体操作请参考官方文档）
  curl -fsSL https://get.docker.com -o get-docker.sh
  sh get-docker.sh
  
  # 安装 Docker Compose
  sudo curl -L "https://github.com/docker/compose/releases/download/v2.24.6/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
  sudo chmod +x /usr/local/bin/docker-compose
  ```

⚠️注意：如果你是在中国大陆的开发者，可能会遇到无法连接docker镜像的情况，请自行解决网络问题

### 4. 安装 Rust

- 下载并安装 [Rust v1.76.0 或最新稳定版](https://www.rust-lang.org/tools/install)。

  ```sh
  # 安装 Rust
  curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  
  # 配置环境变量
  source $HOME/.cargo/env
  ```

### 5. 安装 Forc

- 下载并安装 [Forc v0.49.3 及最新工具链](https://install.fuel.network/latest)。

  ```sh
  # 安装 Forc
  curl -sSfL https://install.fuel.network/latest | sh
  ```

---

这样，你就完成了所有依赖项的安装，可以开始本地运行项目了。请按照后续步骤继续进行项目的设置和运行。


