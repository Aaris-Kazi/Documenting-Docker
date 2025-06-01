# Redis Run for Docker

### Docker pull image
    docker pull redis:8.0.2-alpine3.21
    
### Docker run command to create user and password
    docker run -d --name redis-server -p 6379:6379 redis:8.0.2-alpine3.21 redis-server \
    --user "aaris on >123456789 allcommands allkeys" \
    --user "default off"
