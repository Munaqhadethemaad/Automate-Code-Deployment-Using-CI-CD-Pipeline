# Automate Code Deployment Using CI/CD Pipeline (GitHub Actions)

This project demonstrates a complete **CI/CD pipeline** for a Node.js web app using **GitHub Actions** and **DockerHub**.

## 🚀 Steps Performed by CI/CD
1. Checkout code from GitHub
2. Install Node.js dependencies
3. Run test script
4. Build Docker image
5. Push image to DockerHub

## 🐳 Docker Image
Image pushed to: `munaqhad/nodejs-demo-app:latest`

## ▶️ Run Locally
```bash
npm install
npm start
# open http://localhost:3000
```

## 🧩 Secrets Required (in GitHub → Settings → Secrets → Actions)
- `DOCKERHUB_USERNAME`
- `DOCKERHUB_TOKEN`
