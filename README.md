# Video Tutorial Link:

https://www.youtube.com/watch?v=NIHzYIkXFhE

### Please watch the video before trying to understand the code

- Dockerfile.app:

  - used to build and cotainerise our FastAPI application so that its easily shippable with docker. It can be uploaded to the docker-hub and pulled like other images without any hassle.

- Docker-Compose:

  - simplifies the grouping of multiple apps/containers/services that you want to run. upon using the `up` command, it pulls and builds your services as a network service making it easier to get up and running with already pre-built containers such as Postgresql and Redis etc. Used to build our docker-file and use Traefik image along with the Traefik-Hub image and connect to the Traefik-Hub dashboard to allow us to create our services.

- `app/__init__.py`:

  - basic FastAPI example for an API. It has a single route which returns a message. Its hosted using the entire setup. Its an `__init__.py` file inside of the app directory as that's how uvicorn is used to find your application inside of your application as uvicorn apps tend to be quite large.

  If there are any issues with the repo please make sure to create an issue or comment in the video using the video link provided up top.
