# Athena

> Knowledge base application with public-facing articles and user-controlled ticketing system
> Like zendesk!

## Team

  - __Product Owner__: Bradford Melluish
  - __Scrum Master__: Cary Meskell
  - __Development Team Members__: Amelia Brown

## Table of Contents

1. [Usage](#Usage)
1. [Requirements](#requirements)
1. [Development](#development)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Tasks](#tasks)
1. [Team](#team)
1. [Contributing](#contributing)

## Usage

> Create an account and log in to create tickets and articles

## Requirements

- Docker
- Docker-compose
- Docker machine

## Development

### Installing Dependencies

> To clone the submodules, make sure you use the recursive flag

```sh
git clone --recursive https://github.com/amelia-brown/athenaKb.git
```

From within the root directory:

```sh
docker-compose build
docker-compse up
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines.
