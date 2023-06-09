# Containerizing the application

The application has been configured to be containerized via the config in the `Dockerfile`.

Clone the repository if you want && run the command `docker build -f Dockerfile -t django-app .` 

<!-- If you do not want to clone the repo, download the container using the `docker pull ernestklu/django-e-commerce:v1` command. -->

There is a `Dockerfile.prod`, which is an attempt at creating a production-ready container.
There is more work to be done to get it ready.