# Docker Scaffolding for Laravel Apps
* for easy dev setup
* utilitizes the .env file of your Laravel app
* works as a git submodule

## Installation Instrucktions
### 1. Add as git submodule
In your document root run:
```shell
$ git submodule add git://github.com/kkugelmann/laravelDocker.git docker
```

### 2. Link the docker compose
```shell
$ ln -s laravelDocker/docker-compose.yml
```

### 3. Run docker
```shell
$ docker-compose up -d
```

Your application will be ready on http://localhost:8080
