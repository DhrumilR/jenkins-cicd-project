# Jenkins CI/CD Project

This is a simple Node.js app integrated with Jenkins for a full CI/CD pipeline.

---

## 🔧 Project Structure
├── app.js # Sample Node.js app file
├── package.json # Project dependencies
└── Jenkinsfile # Jenkins pipeline configuration


---

## 🚀 CI/CD Pipeline Flow

1. Jenkins pulls code from GitHub
2. Installs Node.js and project dependencies
3. Runs tests or build steps (currently just install)
4. Optionally deploys the app (future)

---

## 📦 Technologies Used

- Node.js
- Jenkins
- GitHub
- npm

---

## 🛠 Jenkins Configuration

**Pipeline Type:** Declarative  
**Trigger:** Manual (can later be configured for GitHub Webhooks)  
**Stages:**  
- Checkout from Git  
- Install dependencies using `npm install`  
- Build (extendable)

---

## 👤 Author

Dhrumil Raval  
[GitHub Profile](https://github.com/DhrumilR)

---

## 💡 Future Scope

- Add test scripts
- Add deployment step to a cloud server
- Configure auto-deploy via GitHub webhook



