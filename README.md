# 🐳 Hello Docker

A simple **Dockerized Python App** with CI/CD using **GitHub Actions**  
This project is designed to demonstrate the basics of containerization and automation in a DevOps workflow.

---

## 📁 Project Structure

hello-docker/
├── app.py # Simple Python script
├── Dockerfile # Docker instructions
├── .github/workflows/ci.yml # GitHub Actions workflow
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How to Run the App

### Using Docker:

```bash
docker build -t hello-docker .
docker run hello-docker
✅ Output:

css
Copy
Edit
Hello from inside a Docker container!
⚙️ CI/CD with GitHub Actions
This project uses GitHub Actions for continuous integration.

On every push or pull request to the main branch:

✅ Code is checked out

🐍 Python 3.10 is set up

▶️ Python script (app.py) is executed

💡 You can view the status and logs in the "Actions" tab of this repository.

📚 What I Learned
Docker basics: writing a Dockerfile, building and running containers

Using GitHub Actions for CI pipelines

Automating Python project testing and execution

Structuring DevOps-ready repositories

🔗 Useful Commands
Build Docker image:

bash
Copy
Edit
docker build -t hello-docker .
Run the container:

bash
Copy
Edit
docker run hello-docker
🧑‍💻 Author
Syntax-Vibe-Amir
GitHub: github.com/Syntax-Vibe
