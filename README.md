# Stripe Test Project

A simple web application demonstrating Stripe payment integration using TypeScript and Express.

## Features

- Stripe payment processing
- Express.js backend server
- TypeScript support
- Environment variable configuration
- CORS enabled for cross-origin requests

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- Stripe account and API keys

## Installation

1. Initialize the project:
```bash
npm init -y
```

2. Install dependencies:
```bash
npm install express stripe dotenv cors
```

3. Create a `.env` file in the root directory and add your Stripe API keys:
```
STRIPE_SECRET_KEY=<your_stripe_secret_key>
```

## Running the Application

1. Start the backend development server:
```bash
npx tsx server.ts
```

2. The server will run on port 4242 by default
3. Open your browser and navigate to `http://localhost:4242`
4. Start the frontend development server:
```bash
npx serve .
```
5. The frontend will run on port 3000 by default

## Project Structure

- `server.ts` - Express server with Stripe integration (runs on port 4242)
- `index.html` - Frontend interface
- `package.json` - Project dependencies and scripts
- `tsconfig.json` - TypeScript configuration
- `.env` - Environment variables

## Dependencies

- express: Latest version
- stripe: Latest version
- cors: Latest version
- dotenv: Latest version
- tsx: Development dependency for running TypeScript files

## Development Tools

- `tsx` - Used for running TypeScript files directly
- `serve` - Optional static file server (version 14.2.4)

## License

ISC

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request 