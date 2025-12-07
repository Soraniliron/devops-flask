# DevOps Flask Demo

A simple Flask application running in a Docker container.

## What this project shows

- Basic Python Flask app (`app.py`)
- Dependency management with `requirements.txt`
- Containerized using Docker (`Dockerfile`)
- Local run with `python3 app.py`
- Container run with `docker build` + `docker run -p 5000:5000`

## How to run locally

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 app.py
# DevOps Flask Project

This is a simple demonstration project used to showcase basic DevOps skills:
- Running a Python Flask application
- Managing dependencies with requirements.txt
- Building and running a Docker container
- Working inside Linux (WSL) using terminal commands

## How to run the project

### 1. Build the image:
docker build -t devops-flask .

### 2. Run the container:
docker run -d -p 5000:5000 devops-flask

### 3. Open in browser:
http://localhost:5000

docker build -t devops-flask .
docker run -d -p 5000:5000 --name devops-flask-container devops-flask

שמור וצא (`Ctrl+O`, Enter, `Ctrl+X`).

---

## שלב 4 – הופכים את התיקייה לריפו Git

```bash
git init
git status
git add app.py requirements.txt Dockerfile README.md .gitignore
git commit -m "Initial DevOps Flask demo project"


