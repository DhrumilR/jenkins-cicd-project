# Jenkins CI/CD Project

This is a simple Node.js app integrated with Jenkins for a complete CI/CD pipeline demonstration.

---

## 📁 Project Structure

├── app.js # Sample Node.js server file
├── package.json # Node.js dependencies and metadata
└── Jenkinsfile # Jenkins pipeline configuration


---

## 🔁 CI/CD Pipeline Workflow

1. Jenkins pulls the latest code from GitHub
2. Installs Node.js and required dependencies using `npm install`
3. Executes `node app.js` to run the application
4. Future-ready: Add testing, Dockerization, or deployment to cloud

---

## ⚙️ Technologies Used

- Jenkins (Automation Server)
- Node.js (App runtime)
- GitHub (Code repository)
- npm (Package manager)

---

## 🧰 Jenkins Configuration

- **Pipeline Type:** Declarative  
- **Trigger:** Manual (can later be upgraded with GitHub Webhooks)
- **Stages:**
  - Checkout code from Git
  - Install dependencies
  - Run Node.js app
  - Display server logs (via Console Output)

---

## ✅ Skills Demonstrated

- Jenkins setup and plugin configuration
- Node.js environment setup in Jenkins
- CI/CD pipeline creation
- GitHub integration and pipeline execution
- Troubleshooting module errors (`MODULE_NOT_FOUND`)

---

## 👤 Author

**Dhrumil Raval**  
[GitHub Profile](https://github.com/DhrumilR)

---

## 🚀 Future Enhancements

- Add automated test stage (e.g., Jest/Mocha)
- Integrate Docker and containerize app
- Deploy to AWS EC2, Render, or Railway
- Add GitHub Webhook for automatic build triggers

---




