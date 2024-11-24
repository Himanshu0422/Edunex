# Project Setup Guide

## Prerequisites
- Node.js installed on your system
- npm (Node Package Manager)

## Environment Setup

### Frontend Setup
1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Create environment file:
- Copy the example environment file
```bash
cp .env.example .env
```
- Open `.env` and update the variables according to your needs

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm start
```

### Backend Setup
1. Navigate to the server directory:
```bash
cd server
```

2. Create environment file:
- Copy the example environment file
```bash
cp .env.example .env
```
- Open `.env` and update the variables according to your needs

3. Install dependencies:
```bash
npm install
```

4. Start the server:
```bash
npm start
# OR
npm run dev
```

## Notes
- Make sure both frontend and backend .env files are properly configured before starting the servers
- The backend server should be running before starting the frontend application
- Check the respective .env.example files for all required environment variables

## Common Issues
If you encounter any issues:
- Ensure all environment variables are correctly set
- Check if the ports specified in your .env files are available
- Make sure all dependencies are properly installed