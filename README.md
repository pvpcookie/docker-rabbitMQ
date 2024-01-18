# Docker-RabbitMQ

This repository contains a Docker configuration for the RabbitMQ messaging broker. RabbitMQ is an open-source message broker that implements the Advanced Message Queuing Protocol (AMQP) enabling queued, reliable messaging between your applications.

## Features

- Pre-configured RabbitMQ Docker image
- Automatic setup to get started quickly
- High availability for your messaging needs

## Prerequisites

- Docker
- Docker Compose

## Getting Started

### 1. Clone the repository

First, you need to download the repository to your local machine. You can do this either by downloading it as a zip file or by using the following `git` command:

```
git clone https://github.com/pvpcookie/docker-rabbitmq.git
```

### 2. Navigate to the directory

Change your current directory to the folder containing the repository:

```
cd docker-rabbitmq
```

### 3. Start the RabbitMQ server

To start the RabbitMQ server using Docker, run the following command:

```
docker-compose up -d
```

This command starts the RabbitMQ server in a detached mode, which means it will run in the background.

### 4. Access the RabbitMQ Management Console

After the server is up and running, you can open the RabbitMQ Management Console in your browser. The default URL is:

```
http://localhost:15672
```

Use the default credentials to log in:

- Username: `guest`
- Password: `guest`

### 5. Customize your RabbitMQ installation

To customize your RabbitMQ installation, modify the `docker-compose.yml` file as needed. For example, you can change the default username and password for the management console, or bind a different port to the host system.

## Contributing

Feel free to contribute to this project by reporting issues, submitting pull requests, or lending other support.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

The pre-configured RabbitMQ Docker image is based on the official [RabbitMQ image](https://hub.docker.com/_/rabbitmq/) from Docker Hub.
