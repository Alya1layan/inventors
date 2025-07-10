# inventors
Inventors screening task

---

## 🔧 Technologies Used

- **Frontend**: React (Vite), HTML/CSS/JS
- **Backend**: Node.js, Express, MongoDB
- **CI/CD**: GitHub Actions
- **Docker**: Dockerfiles, Docker Hub
- **Orchestration**: Docker Compose

---
P.S: I had to create a gitignore file because the folders were too big, but I dont really think I needed it.
I learnt the basics of docker while doing this and have an improved understaning of yml files so i enjoyed it

## ✅ Completed Tasks

- ✅ Created a GitHub repository
- ✅ Wrote Dockerfiles for frontend and backend
- ✅ Created GitHub Actions workflow for CI/CD
- ✅ Built and pushed Docker images to Docker Hub:
  - [Frontend Image](https://hub.docker.com/r/aaliyaha/nventors-frontend)
  - [Backend Image](https://hub.docker.com/r/aaliyaha/nventors-backend)
- ✅ Configured local Docker environment
- ✅ Used Docker Compose with health checks
- ✅ Verified backend with curl
- ✅ Exposed frontend on `localhost:9060`

---

## 🚀 Running Locally
Ensure Docker is running, then clone the repository and start the containers:
bash script:
git clone https://github.com/aaliyaha/inventors-devops-task.git
cd inventors-devops-task
docker-compose up --build
