# SecureProxy - Web Proxy Application

A modern web-based proxy application built with React and Express.js that helps bypass network restrictions.

## Features

- 🌐 **Web Proxy** - Access blocked websites through our secure proxy
- 🛡️ **Security Options** - Control scripts, cookies, and ad removal
- 📊 **Request Logging** - Track all your browsing activity
- 🎨 **Modern UI** - Clean, responsive interface
- ⚡ **Fast Performance** - Optimized for speed and reliability

## Quick Start

### Local Development
```bash
npm install
npm run dev
```

### Production Build
```bash
npm run build
npm start
```

## Deployment Options

### Vercel Deployment
1. Connect your GitHub repository to Vercel
2. The `vercel.json` configuration is already included
3. Deploy with one click

### Railway Deployment
1. Connect your GitHub repository to Railway
2. The `railway.toml` configuration is already included
3. Deploy automatically

### Docker Deployment
```bash
docker build -t secureproxy .
docker run -p 3000:3000 secureproxy
```

## Usage

1. Enter any website URL in the form
2. Choose your proxy options (scripts, cookies, ads)
3. Click "Browse" to access the site through the proxy
4. View request history in the log section

## Configuration

The application works out of the box with no additional configuration required. It uses in-memory storage for request logging.

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Express.js, Node.js
- **Build Tool**: Vite
- **UI Components**: Radix UI + shadcn/ui

## License

MIT License - Feel free to use this project however you'd like!