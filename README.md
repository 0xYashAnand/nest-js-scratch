# Nest.js Hello World Example

This is a simple Nest.js application demonstrating a basic REST API endpoint that returns "Hello World!" when accessed.

## Prerequisites

Before running this application, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd nestjs-hello-world
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To start the application, run the following command:

```bash
npx ts-node-dev src/main.ts
```

Once the application is running, you can access the API endpoint by navigating to `http://localhost:3000` in your web browser or using tools like Postman.

## API Endpoint

- **GET** `/`

  Returns a greeting message "Hello World!".

## Folder Structure

```
src/
├── main.ts         # Entry point of the application
├── app.controller.ts # Controller containing the API endpoint
└── app.module.ts   # Main module of the application
```
