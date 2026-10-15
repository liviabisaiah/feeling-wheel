# Feeling Wheel

A web application built with React and TypeScript, designed to help users explore and identify feelings through a visual feeling wheel.

## Tech Stack

- **React** — UI components
- **TypeScript** — type-safe JavaScript
- **Vite** — development server and build tooling
- **Docker** — containerized development environment

## Getting Started

### Prerequisites

- Node.js and npm
- Git

### Run Locally

1. Clone the repository.
2. Navigate to the frontend directory.
3. Install dependencies.
4. Start the development server.

```bash
cd frontend
npm install
npm run dev
```

Open the local URL printed in your terminal.

### Run with Docker

Install Docker Desktop, then run these commands from the `frontend` directory:

```bash
docker compose up --build
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

To stop the containers, press `Ctrl+C` and run:

```bash
docker compose down
```

## Development

Run ESLint to check code quality:

```bash
npm run lint
```

Build the application:

```bash
npm run build
```

## Project Status

This project is under active development.