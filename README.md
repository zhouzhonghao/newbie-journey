# newbie-journey

## Setup your development environment

### Setup Homebrew
Homebrew is the easiest and most flexible way to install the UNIX tools Apple didn’t include with macOS. It can also install software not packaged for your Linux distribution without requiring sudo.

### Setup Git

### Setup Nginx
1. Install nvm
   ```bash
   brew install nginx
   ```

### Setup MySQL/MariaDB

### Setup Docker
1. Get Docker Desktop Installer
   <pre>
   <code>The download page: <a href="https://docs.docker.com/get-started/get-docker">https://docs.docker.com/get-started/get-docker</a></code>
   </pre>
2. Install via installer

### Get started with JavaScript
##### Setup
1. Install nvm
   ```bash
   brew install nvm
   ```
2. Install node.js runtime
   ```bash
   nvm install 22.6.0
   nvm alias default 22.6.0
   ```
##### Tips
1. Serve a static site
   ```bash
   npx serve .
   ```
2. Generate an express project
   ```bash
   npx express-generator .
   ```
3. Generate an koa2 project
   ```bash
   npx -p koa-generator koa2 .
   ```   
4. Generate a react project
   ```bash
   npm create react-app .
   ```
5. Generate a nextjs project
   ```bash
   npm create next-app .
   ```
6. Generate a plasmo project
   ```bash
   npm create plasmo .
   ```
7. Generate a vite project
   ```bash
   npm create vite .
   ```

### Get started with Go
1. Install goenv
   ```bash
   brew install goenv
   ```
2. Install go runtime
   ```bash
   goenv install 1.23.0
   goenv global 1.23.0
   ```

### Get started with Java
1. Install jenv
   ```bash
   brew install jenv
   ```
2. Install java runtime
