# CuisineAI

> Personalized culinary discovery that transforms home cooking through intelligent, adaptive recipe experiences

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/cuisineai/app)

## Overview

CuisineAI is an innovative recipe discovery platform that leverages AI to provide personalized cooking recommendations tailored to individual preferences, dietary needs, and skill levels. Our mission is to empower home cooks with intelligent, efficient, and nutritious meal planning solutions.

## Features

- ✨ AI-powered personalized recipe recommendations
- 🚀 Comprehensive dietary and nutritional filtering
- 💡 Budget-friendly meal planning
- 🔒 Secure user authentication and profile management

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Tailwind CSS
- Zustand State Management
- React Router v6

**Backend:**
- Next.js API Routes
- PostgreSQL with Prisma ORM
- NextAuth.js Authentication

**Deployment:**
- Vercel
- Supabase
- Cloudinary

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/cuisineai/app.git

# Install dependencies
cd app
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── prisma/             # Database schema
├── public/             # Static assets
└── tests/              # Test files
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
DATABASE_URL=your_postgresql_connection_string
NEXTAUTH_SECRET=your_auth_secret
NEXT_PUBLIC_API_URL=your_api_endpoint
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage
```

## Deployment

### Vercel

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and development process.

### How to Contribute
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue in the GitHub repository or email support@cuisineai.com.

---

**Created with ❤️ by CuisineAI Team**