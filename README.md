# Node.js Docker AWS Deployment

This is a simple Node.js and Express application running in a Docker container. The project has been created exclusively for **deployment practice**.

## 📁 Project Directory Structure
```bash
simple-dockerized-nodejs-app/
├── server.js
├── package.json
├── Dockerfile
└── README.md
```

## 📦 How to Use (Locally or EC2):
```bash
#1. Clone the Repository:
   git clone https://github.com/<your-username>/<your-repo>.git
   cd simple-dockerized-nodejs-app

#2. Build Docker Image:
   docker build -t node-app .

#3. Run Docker Container:
   docker run -d --name node-app-service -p 3000:3000 node-app

#4. Open in Browser or Curl:
   curl http://localhost:3000
   or
   open in browser: http://<your-ec2-ip>:3000
