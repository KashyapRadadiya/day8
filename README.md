# Java Maven Jenkins Project

This is a simple Java Maven project designed to demonstrate **Jenkins build automation** (CI/CD).  

---

## 🛠️ Tools Used

- **Java JDK 8 or 11** – Programming language
- **Maven** – Build and dependency management
- **Jenkins** – CI/CD automation server
- **Git / GitHub** – Version control

---

## 🚀 Steps to Build and Run Project

### 1. Build Locally
```bash
    mvn clean package
```
- This will compile HelloWorld.java and generate hello-1.0.jar in the target/ folder.
- You should see BUILD SUCCESS in the console.

### 2. Setup Jenkins
- Start Jenkins and open: http://localhost:8080
- Go to Manage Jenkins → Global Tool Configuration → Maven and add Maven installation.
- Create a Freestyle project.
- In Build → Invoke top-level Maven targets, set Goal: clean package.
- Save and click Build Now.
- You should see BUILD SUCCESS in the console output.