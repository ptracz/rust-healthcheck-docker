# rust-healthcheck-docker
simple rust healthcheck in docker

based on https://blog.logrocket.com/packaging-a-rust-web-service-using-docker/


to start enter this command in command line inside main folder:

cargo build

docker-compose up

and then http://localhost:8000/health


cargo build command is just to generate cargo.lock file if you want to skip this just comment

COPY ./Cargo.lock ./Cargo.lock

inside Dockerfile 
