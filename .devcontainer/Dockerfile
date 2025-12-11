# Use the Default Linux Universal devcontainer image as the base
FROM mcr.microsoft.com/devcontainers/universal:2


# Install Vue.js CLI (frontend) and Flask (backend)
RUN npm install -g @vue/cli \
    && pip3 install --no-cache-dir flask

# Set working directory inside the container
WORKDIR /workspace

# Expose common dev ports (Vue = 5173, Flask = 5000)
EXPOSE 5173 5000
