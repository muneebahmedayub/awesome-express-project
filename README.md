# awesome-express-project

awesome-express-project

### Prerequisites

- [Docker (at least 1.10)](https://www.docker.com/)
- [Docker-compose (at least 1.6)](https://docs.docker.com/compose/install/)

## Getting Started

To get up and running on local, simply do the following:

    $ cd awesome-express-project
    # build docker images
    $ docker-compose build
    $ docker-compose up

## Deployment

ssh to server

    $ cd ~/awesome-express-project
    $ git pull origin develop
    $ docker-compose -f docker-compose.dev.yml build
    $ docker-compose -f docker-compose.dev.yml up -d
