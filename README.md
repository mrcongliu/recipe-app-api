# recipe-app-api
Build a Backend REST API using Python, Django (3.2), Django REST Framework (3.12), Docker, GitHub Actions, Postgres, and Test Driven Development!

## Usage

### Docker Hub Secrets

To take advantage of [Docker Hub](https://hub.docker.com)'s Authenticated Rate Limits of 200/6h, set up secrets in GitHub Settings.


- DOCKERHUB_USER
- DOCKERHUB_TOKEN

### GitHub Actions

Under `.github/workflows/`, stores all the actions.

Each yml file starts with three dashes `---`.