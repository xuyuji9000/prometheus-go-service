- Build image: `docker build -t prometheus-go-service .`

- Run container: `docker run -d -p 8080:8080 --rm prometheus-go-service`

- Push Docker image: 

    ```
    DOCKER_ID_USER=DOCKER_ID_USER
    docker tag prometheus-go-service $DOCKER_ID_USER/prometheus-go-service
    docker push $DOCKER_ID_USER/prometheus-go-service
    ```
