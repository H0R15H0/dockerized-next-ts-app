# README

# Requirement
```
Docker
docker-compose
```

# Usage
``` bash
$ git clone git@github.com:H0R15H0/dockerized-next-ts-app.git YOUR_APP_NAME
$ cd YOUR_APP_NAME
$ docker-compose build
$ docker-compose run --rm app yarn install
$ docker-compose up
# Go to http://localhost:3000 and you'll see: "Welcome to Next.js!"
```

# Change remote repository
```
$ git remote set-url origin https://github.com/USERNAME/REPOSITORY.git
```
