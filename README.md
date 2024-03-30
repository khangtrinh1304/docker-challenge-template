# docker-challenge-template
This repository presents work completed for Challenge 1 of the Docker project: creating a Docker container capable of serving static web content through NGINX.

# Introduction
This challenge provided hands-on experience using Docker, an industry leading software containerization platform, and NGINX, an efficient high performance web server.

# Learning Experience
Through this project, I gained insight into containerization basics as well as Docker for creating and managing containers efficiently. Furthermore, NGINX gave me knowledge on serving static content more efficiently.

# Step I Take to finished this challenge 1
1. I Created the "public" folder as the challenge requirement.
2. I Created the "index.html" File inside the "public" folder that includes my personal information as per the project's requirements.
3. I Created the Dockerfile in the challenge1 directory
4. Build the Docker Image by using the "docker build" command docker "build -t my-nginx-image" . to create an image from the Dockerfile
5. Run the Docker container using the "docker run" command "docker run --name my-nginx-container -d -p 8080:80 my-nginx-image", mapping the appropriate ports.
6. Test the application to verified the application by accessing "http://localhost:8080" and ensuring that my "index.html" was displayed correctly.
7. After my challenge had been successfully completed I screenshot terminal and result.

# Step I take to finished this challenge 2
1. I downloaded challenge2 zip folder and saved it onto my computer from D2L.
2. I extracted all the files from the zip file and placed them within my challenge2 directory.
3. I created a Dockerfile within the directory and included any necessary code necessary for building my container.
4. Next, I made a docker-compose.yml file which will handle Docker setup for this challenge.
5. I made several mistakes which needed fixing multiple times. At first it was difficult to pinpoint exactly where everything had gone wrong but with enough attempts and deletions eventually I managed to resolve all errors and restore functionality.
6. I added a default.conf file and wrote coded settings specific for Nginx server configurations.
7. My initial docker-compose up --build run produced errors. After realizing there were conflicts, I stopped the previous server running before restarting this command in Docker Desktop.
8. After much effort and struggle, I finally managed to correct the code. First I used docker-compose down before rebuilding with docker-compose up --build. Finally I received notification that my server was now operating on port 3000.
9. After my challenge had been successfully completed, I opened my browser and entered localhost:3000/api/books into it to see if my challenge had succeeded and screenshot terminal and result.

# Conclusion and Summary
This challenge is really useful for me. I learned a lot through this challenge. It helps me understand more about this Docker software and will be an important tool for me