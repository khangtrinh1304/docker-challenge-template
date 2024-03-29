# docker-challenge-template
This repository presents work completed for Challenge 1 of the Docker project: creating a Docker container capable of serving static web content through NGINX.

# Introduction
This challenge provided hands-on experience using Docker, an industry leading software containerization platform, and NGINX, an efficient high performance web server.

# Learning Experience
Through this project, I gained insight into containerization basics as well as Docker for creating and managing containers efficiently. Furthermore, NGINX gave me knowledge on serving static content more efficiently.

# Step I Taken to finished this challenge 1
1. Create the "public" folder to hold the static assets.
2. Create the "index.html" File inside the "public" folder that includes my personal information as per the project's requirements.
3. Create the Dockerfile and Authored a Dockerfile to build a custom NGINX image that serves the contents of the "public" folder.
4. Build the Docker Image by using the "docker build" command to create an image from the Dockerfile.
5. Run the Docker container using the "docker run" command, mapping the appropriate ports.
6. Test the application to verified the application by accessing "http://localhost:8080" and ensuring that my "index.html" was displayed correctly.
