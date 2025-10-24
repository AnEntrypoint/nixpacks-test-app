# Nixpacks Test App

A simple Node.js application designed to test nixpacks deployment with Coolify.

## Features

- Express.js web server
- Health check endpoint
- JSON API responses
- Nixpacks configuration for containerization

## Endpoints

- `GET /` - Main application info
- `GET /health` - Health check endpoint

## Deployment with Nixpacks

This app includes a `nixpacks.toml` configuration file that specifies:

- Node.js 18 runtime
- npm build phase
- Production startup command

## Testing Locally

```bash
npm install
npm start
```

The server will start on port 3000.
