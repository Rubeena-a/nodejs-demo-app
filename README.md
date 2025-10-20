# nodejs-demo-app
## Automate Code Deployment Using CI/CD Pipeline

###  Objective
Automate the process of building, testing, and deploying a Node.js web application using a CI/CD pipeline.
---
###  Features
- ✅ Automatically runs tests on every push
- ✅ Builds a Docker image of the app
- ✅ Pushes the image to DockerHub
- ✅ Uses GitHub Actions for continuous integration and deployment
---
### Testing The App

#### Local Testing:
Here's how the application and tests run locally, along with Docker image creation and execution.

- **Run Node.js Application:**
  ```bash
  node app.js
  ```
  Access the application at `http://localhost:3000`

- **Run Tests:**
  ```bash
  node test.js
  ```
- **Build Docker Image Locally:**
  ```bash
  docker build -t nodejs-cicd-app .
  ```

- **Run Node.js App in Docker:**
  ```bash
  docker run -p 3000:3000 nodejs-cicd-app
  ```
  Access the application at `http://localhost:3000`
---
### Results

<p align="center">
  <div style="display: inline-block; text-align: center; margin: 5px;">
    <img src="https://github.com/user-attachments/assets/fc8d9d72-e16e-434d-b89a-4391ebc01b7e" width="300" />
    <br>
    <b>Fig 1:</b> Node.js Application
  </div>
  <div style="display: inline-block; text-align: center; margin: 5px;">
    <img src="https://github.com/user-attachments/assets/7bdca3c1-2890-4681-9599-b5b6c8369eee" width="300" />
    <br>
    <b>Fig 2:</b> Running Test
  </div>
</p>

<p align="center">
  <div style="display: inline-block; text-align: center; margin: 5px;">
    <img src="https://github.com/user-attachments/assets/c8c61ca0-a900-4027-a309-3dc2bde21651" width="300" />
    <br>
    <b>Fig 3:</b> Build Docker Image Locally
  </div>
  <div style="display: inline-block; text-align: center; margin: 5px;">
    <img src="https://github.com/user-attachments/assets/144897f2-6604-41c1-9052-c574edc6eeeb" width="300" />
    <br>
    <b>Fig 4:</b> Run node.js app in Docker
  </div>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/05ad05a2-db72-490e-8830-0a7bf20022d6" width="45%" />
  <br>
  <b>Fig 5:</b> Docker Image Created
</p>

---

### GitHub Actions Workflow

<p align="center">
  <img src="https://github.com/user-attachments/assets/302392fb-170c-4cd0-81e8-a9b3a203210c" width="60%" />
  <br>
  <b>Fig 6:</b> GitHub Actions CI/CD Workflow
</p>
---
### Prerequisites
Before running or testing this project, ensure you have the following installed:
1.  **Node.js** 
2.  **Docker Desktop**
3.  **Git**
4.  A **GitHub account**
5.  A **DockerHub account**
---
### Author 
Rubeena Shaik
---
