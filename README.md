# Go RabbitMQ Producer Consumer

This repository contains a simple implementation of a producer and consumer using RabbitMQ and Go. It demonstrates the basics of message queuing with RabbitMQ and how to integrate it with a Go application.

## Features

- **Producer**: Sends messages to a RabbitMQ queue.
- **Consumer**: Listens for messages from the RabbitMQ queue and processes them.
- **Configuration**: Easily configurable RabbitMQ connection settings.

## Prerequisites

- Go 1.18 or higher
- RabbitMQ server

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mazzlookman/go-rabbitmq-producer-consumer.git
   ```
2. Change to the project directory:
   ```bash
   cd go-rabbitmq-producer-consumer
   ```
3. Install dependencies:
   ```bash
   go mod tidy
   ```

## Usage

### Running the Producer

To run the producer, execute the following command:
```bash
go run producer/main.go
```

### Running the Consumer

To run the consumer, execute the following command:
```bash
go run consumer/main.go
```

## Configuration

Configuration settings for RabbitMQ (such as the server URL, queue name, etc.) can be modified in the `config/config.go` file.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or fixes.

---

Thanks. ✨
