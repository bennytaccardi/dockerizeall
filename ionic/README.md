# 📱 Ionic App
This folder contains some examples of Dockerfiles and docker-compose files in order to build and/or execute an app based on ionic framework.

# 🚀 Getting Started

There are two Dockerfiles:

1. Dockerfile.dev: Build an image for development purpose. The command executed is a "serve" command. So livereloading is active
2. Dockerfile.prod: Build an image for production purpose. The command executed is a "build --prod". This command will generate a "www" folder that should be used, further, by a web server.

There are two docker-compose files:

Basically, they are quite similar. They mount some volumes and use provious Dockerfiles as context in order to execute ionic in docker stack.


# 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.