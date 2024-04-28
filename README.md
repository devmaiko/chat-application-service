# Chat Application Service

This is a chat application service developed in NestJS, utilizing Socket.IO for real-time communication.

[![JavaScript](https://skillicons.dev/icons?i=typescript,nodejs,nestjs,git)](https://skillicons.dev)

## Videos
- [Complete feature working](https://drive.google.com/file/d/1dRgm9pgoc5Z0EpjQZRDL7AEHyzAxesD-/view?usp=sharing)

## Features

- Real-time messaging: Instantly send and receive messages between users.
- Customizable: Easily extend and customize the service to fit your specific requirements.

## Installation

To run this service locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/devmaiko/chat-application-service.git
```

2. Install dependencies:

```bash
cd chat-application-service
yarn
```

Make sure to fill in the necessary environment variables in the `.env` file.

3. Start the server:

```bash
yarn start:dev
```

The service should now be running locally on `http://localhost:3000`.

## Usage

To use the chat application service, follow these steps:

1. Connect to the chat service using a compatible client.
2. Start sending and receiving messages in real-time.

## Endpoints

### Messages

- `messages`: Send a new message.

## Technologies Used

- [NestJS](https://nestjs.com/): A progressive Node.js framework for building efficient, reliable, and scalable server-side applications.
- [Socket.IO](https://socket.io/): Real-time bidirectional event-based communication library.
- [TypeORM](https://typeorm.io/): ORM for TypeScript and JavaScript.
