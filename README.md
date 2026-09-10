# CVCoach

A modern web application built with Next.js, React, and TypeScript.

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Development](#development)
- [Testing](#testing)
- [Deployment](#deployment)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- Built with Next.js 14 and React 18
- TypeScript for type safety
- Tailwind CSS for styling
- ESLint and Prettier for code quality
- Jest for unit testing
- Docker support for containerization
- GitHub Actions for CI/CD
- Responsive design

## 🛠️ Tech Stack

- **Frontend**: Next.js, React, TypeScript
- **Styling**: Tailwind CSS, PostCSS
- **Development Tools**: ESLint, Prettier, Jest
- **DevOps**: Docker, Docker Compose
- **CI/CD**: GitHub Actions
- **Package Manager**: npm

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ or 20+
- npm or yarn
- Docker (optional, for containerized development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/bc-cvcoach/cvcoach.git
   cd cvcoach
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup environment variables**
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` with your configuration.

4. **Start development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 💻 Development

### Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Start production server
npm start

# Run linter
npm run lint

# Format code
npm run format

# Run tests
npm test

# Watch tests
npm run test:watch
```

### Using Docker

```bash
# Build and start with Docker Compose
docker-compose up --build

# Stop services
docker-compose down
```

## 🧪 Testing

```bash
# Run all tests
npm test

# Run tests in watch mode
npm run test:watch

# Run tests with coverage
npm test -- --coverage
```

## 📦 Deployment

### Build for Production

```bash
npm run build
npm start
```

### Docker Deployment

```bash
# Build Docker image
docker build -t cvcoach:latest .

# Run Docker container
docker run -p 3000:3000 cvcoach:latest
```

### GitHub Actions

This project includes CI/CD pipelines configured in `.github/workflows/deploy.yml`.

## 📂 Project Structure

```
cvcoach/
├── .github/
│   └── workflows/          # GitHub Actions workflows
├── pages/                  # Next.js pages
├── components/             # React components
├── styles/                 # CSS stylesheets
├── public/                 # Static assets
├── src/                    # Source code (alternative)
├── .eslintrc.json         # ESLint configuration
├── .prettierrc.json       # Prettier configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
├── jest.config.js         # Jest configuration
├── next.config.js         # Next.js configuration
├── Dockerfile             # Docker configuration
├── docker-compose.yml     # Docker Compose configuration
├── .env.example           # Environment variables template
└── README.md              # This file
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style

- Use TypeScript for type safety
- Follow ESLint rules
- Format code with Prettier
- Write tests for new features

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📧 Support

For support, email support@cvcoach.com or open an issue on GitHub.

---

**Happy coding! 🚀**
