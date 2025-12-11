FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils pacakge
RUN apt-get update && apt-get install -y xz-utils

# Install Python dependencies (Flask)
RUN pip install --upgrade pip && \
    pip install flask

# Install Vue.js globally
RUN npm install -g @vue/cli