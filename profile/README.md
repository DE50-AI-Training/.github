# Welcome to the SimplifyAI org

This project was created by five students at UTBM.

## Run the project

_If you don't want to use Docker, refer to the individial instructions from the `ai-training-webapp` and `ai-training-backend` repositories_

Prerequisites:
- Have Docker installed via your package manager
- **For windows users**: install docker via Docker Desktop

First, clone the repository:
```
git clone https://github.com/DE50-AI-Training/ai-training-docker && cd ai-training-docker
```

Then run the Docker Compose:
```
docker compose up --build
```
You should be ready to go !

You can also run the project detached from your terminal using the `-d` flag
In this case, stop it using:
```
docker compose down
```
Keep in mind that you need to be in this repository's folder.

