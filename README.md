# Face Recognition Attendance System

A modern web application for managing student attendance using face recognition technology.

## Features

- Faculty authentication with password or OTP
- Interactive class timetable
- Face recognition for automated attendance
- Manual attendance management
- Responsive design

## Tech Stack

- React
- TypeScript
- Tailwind CSS
- React Router
- Vite

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/face-recognition-attendance-system.git
cd face-recognition-attendance-system
```

2. Install dependencies
```bash
npm install
# or
yarn
```

3. Start the development server
```bash
npm run dev
# or
yarn dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Development

### Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run lint` - Run ESLint to check for code issues
- `npm run format` - Format code using Prettier

### VS Code Setup

This project includes recommended VS Code settings and extensions for an optimal development experience. When you open the project in VS Code, you'll be prompted to install the recommended extensions.

## Project Structure

```
src/
├── components/       # Reusable UI components
├── context/          # React context providers
├── pages/            # Page components
├── services/         # API and service functions
├── types/            # TypeScript type definitions
├── App.tsx           # Main application component
└── main.tsx          # Application entry point
```

## License

MIT