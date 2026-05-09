Calculator Application

A simple and responsive Calculator Application built using modern web technologies with Docker support for easy setup and deployment.

Features
Basic arithmetic operations
Responsive user interface
Docker container support
Lightweight and fast
Easy deployment using Docker
Technologies Used
HTML
CSS
JavaScript
Docker
Git & GitHub
Project Structure
project-folder/
│
├── Dockerfile
├── package.json
├── .dockerignore
├── src/
└── README.md
Installation
Clone the Repository
git clone https://github.com/your-username/your-repository-name.git
Navigate to the Project Folder
cd your-repository-name
Run Locally

Install dependencies:

npm install

Start the application:

npm start
Docker Setup
Build Docker Image
docker build -t calculator-app .
Run Docker Container
docker run -p 3000:3000 calculator-app

Open in browser:

http://localhost:3000
Git Commands
git init
git add .
git commit -m "Initial commit"
git remote add origin <repository-url>
git push -u origin main
Dockerfile Example
FROM node:18

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
Author

Darwin Prem Kumar
