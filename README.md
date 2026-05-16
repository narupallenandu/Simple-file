Cute Nannuu Mini Project 💖
Description

This is a cute personalized mini project created for the name Nandini using HTML, CSS, and JavaScript. The project contains a beautiful pink gradient background, animated floating hearts, a stylish card design, and an interactive button that displays a sweet popup message. The main purpose of this project is to practice basic front-end development concepts in a fun and creative way.

Features
Pink aesthetic background 🌸
Floating heart animations 💖
Animated card effect ✨
Interactive popup button 🎀
Beginner-friendly project 💻
Technologies Used
HTML
CSS
JavaScript
Docker
Dockerfile
FROM nginx:alpine

COPY . /usr/share/nginx/html

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
Build Docker Image
docker build -t nandini-project .
Run Docker Container
docker run -d -p 8080:80 --name cute-container nandini-project
Open in Browser
http://localhost:8080
Project Structure
cute-project/
│── index.html
│── Dockerfile
│── README.md
Output

The project displays a cute animated webpage with floating hearts and personalized messages for Nannuu 💕
