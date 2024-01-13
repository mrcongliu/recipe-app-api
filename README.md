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


### Container Structure

There are two containers managed by docker-compose: app and db.

`app` will wait for `db`.

Progress:

```
docker-compose run --rm app sh -c "python manage.py startapp recipe"
```
