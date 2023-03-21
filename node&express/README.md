# 🚀 Node.js and Express.js App with Nodemon Hot Reloading
This folder contains examples of Dockerfiles and docker-compose files to build and/or execute a Node.js and Express.js app with Nodemon hot reloading.

# 🛠️ Getting Started
There are one Dockerfiles:

Dockerfile: Builds an image for development purposes. The command executed is nodemon which enables hot reloading.

docker-compose.yml: This file sets up the development environment with the Dockerfile.dev and mounts the local src directory as a volume to enable hot reloading.

docker-compose -f docker-compose.prod.yml up

# 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.