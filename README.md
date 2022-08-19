## Nodejs Docker MongoDB

> Simple example of a dockerized Node/Mongo app

### Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

app running on localhost:3000

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
