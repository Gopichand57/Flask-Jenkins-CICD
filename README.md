# Flask Jenkins CI/CD Pipeline 
This project demonstrates a basic CI/CD pipeline using **Jenkins** and **Docker** to build and deploy a simple Flask application.
# Technologies Used
- Python (Flask)
- Jenkins
- Docker
- GitHub
- AWS EC2 (Ubuntu)
##]📁 Project Structure

---

## 🛠️ Jenkins Pipeline Overview

1. **Pulls the latest code** from GitHub.
2. **Builds Docker Image** using `Dockerfile`.
3. **Runs a Flask app** inside a Docker container.
4. Application is exposed on port 5000.

---

## 📸 Jenkins Dashboard (Example)

> Your live Jenkins instance (replace with your actual IP if public):
> (http://13.232.64.167:8080)

---

## 💡 Run Locally

```bash
git clone https://github.com/Gopichand57/Flask-Jenkins-CICD.git
cd Flask-Jenkins-CICD
docker build -t flask-jenkins-app .
docker run -d -p 5000:5000 flask-jenkins-app


