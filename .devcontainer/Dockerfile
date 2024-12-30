FROM mcr.microsoft.com/devcontainers/javascript-node:18

WORKDIR /workspace
COPY package*.json ./

RUN npm install || echo "Preinstalling NPM packages not possible! Please run 'npm install' after devcontainer is created."

EXPOSE 3000
CMD ["bash"]
