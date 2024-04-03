# Authentication Service

## Overview

The Authentication Service is a foundational component designed to manage user authentication within our system. This service is responsible for user login, registration, and password management operations. It's built with a focus on security, scalability, and ease of integration.

## Setup

### Prerequisites

- Node.js
- TypeScript

### Installation

1. Clone the repository and navigate to the service directory.
2. Install the required dependencies using `npm install`.
3. Ensure the configuration files (`nodemon.json`, `tsconfig.json`) are set up as per your development environment.

### Running the Service

- To start the service in development mode, run `npm run dev`. This utilizes `nodemon` and `ts-node` for hot reloading.
- For production, compile the TypeScript files and then start the service.

## API Specification

The service defines several endpoints for user operations, detailed in the `api.spec.yaml` file. Key endpoints include:

- **Login**: Authenticate users and provide session tokens.
- **Registration**: Register new users in the system.
- **Password Management**: Allow users to change or reset their passwords.

For a complete list of endpoints and their specifications, please refer to the `api.spec.yaml` file.
