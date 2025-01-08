# Raspiservices - Vannak

This repository offers a set of Docker images designed to run various services on Raspberry Pi.
Each image is optimized to make the most of the Raspberry Pi’s capabilities, providing an easy-to-configure, consistent environment with stable performance.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Usage](#usage)
  - [Accessing the services](#accessing-the-services)
    - [SSH](#ssh)
- [Contributing](#contributing)

## Getting Started

### Prerequisites
- **Docker**  
  Make sure you have a recent version of Docker installed on your Raspberry Pi.
- **Docker Compose**  
  Required for orchestrating containers easily.

### Installing

```sh
git clone https://github.com/vannak/raspiservices.git
cd raspiservices
cd service-name
docker-compose up -d
```

## Usage

### Accessing the services

#### SSH

- ssh vannak@raspberrypi
- password: your password

> Adjust the username and password to match your own configuration.

## Contributing

Pull requests are welcome.