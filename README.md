# go-started
Simple and quick start golang project sample<br>
<br>
I made a simple golang executable project.
<br>
Use it when you want to start a project right away

<br>

# run local
### direct run
    go run src/main.go
    
### run with docker-compose
    docker-compose build
    docker-compose up -d

# run prod server
    docker build -f docker/prod/Dockerfile -t go-api:0.0.1 .
    docker run -d --name="go-api" -p 80:80 go-api:0.0.1
