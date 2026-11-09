# My First Docker Project 🐳

My first project made by Vasu Sharma using Python + Docker + GitHub.

## What is this?
A simple Python app that runs inside Docker.

## Files in this project
- `app.py` - Main Python code
- `Dockerfile` - Instructions to build Docker image
- `requirements.txt` - Python libraries

## How to Run?

### 1. Using Docker
```bash
docker build -t my-first-project .
docker run -p 5000:5000 my-first-project