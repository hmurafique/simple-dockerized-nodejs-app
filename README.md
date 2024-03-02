# Dockerized Node.js Express Application

This project demonstrates the fundamental steps of dockerizing a simple Node.js Express application. It's perfect for those looking to understand the workflow of packaging and running applications within Docker containers.

## Setup 

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Emminex23/simple-dockerized-nodejs-app.git
   ```

2. **Install dependencies:**
   ```bash
   cd dockerized-nodejs-express
   npm install 
   ```

## Dockerizing the Application

1. **Dockerfile:** The `Dockerfile` contains the instructions for building the Docker image.  Refer to the `Dockerfile` for detailed explanations of each step.

2. **Build the image:**
   ```bash
   docker build -t nodejs-express-app .
   ```

3. **Run the container:**
   ```bash
   docker run -p 3000:3000 -d nodejs-express-app
   ```

## Accessing the Application

Open your web browser and go to  http://localhost:3000/. You should see the message "Hello from Express!".

## Project Structure

* `server.js`:  The Node.js Express server code.
* `package.json`: Contains project dependencies.
* `Dockerfile`:  Instructions for creating the Docker image.
