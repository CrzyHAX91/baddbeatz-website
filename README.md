# baddbeatz-website
 DJ THEBADGUY Official Website
## Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

- ## Features
- 🎨 Sleek neon cyberpunk design with smooth animations
  - Example: Animated transitions between pages.
- 🎵 Real-time audio visualization
  - Example: Dynamic visual effects that react to the beat of the music.
- 🤖 AI-powered playlist generation
  - Example: Personalized playlists based on user listening habits.
- 📱 Responsive layout for all devices
  - Example: Optimized views for mobile, tablet, and desktop.
- 🖥️ Cross-platform desktop application (Electron)
  - Example: Native-like experience on Windows, macOS, and Linux.
- 🌐 Web version accessible from any browser
  - Example: Full functionality available on Chrome, Firefox, and Safari.
 
  - ## Prerequisites
- Node.js (version x.x.x)
- npm or yarn
- Git

- ## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/CrzyHAX91/badbeats.git
   cd badbeats

   # Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install

# Install Electron dependencies
cd ../electron
npm install

PORT=3001
NEXT_PUBLIC_API_URL=http://localhost:3001
DEV_SERVER_URL=http://localhost:3000
PRODUCTION_APP_URL=app://./index.html

# Start Next.js client (in client directory)
npm run dev

# Start Express server (in server directory)
npm run dev

# Start Electron app (in electron directory)
npm start

## Running Tests
- To run tests for the client:
  ```bash
  cd client
  npm test

  cd ../server
npm test

cd ../electron
npm test

## Contributing
We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/my-feature`
5. Submit a pull request

### Code Style
- Follow the existing code style and conventions.
- Ensure your code passes all tests.
- Write clear, concise commit messages.

- ## Contact
For support or questions, please contact worlddre3mer1991@protonmail.ch
--------------------------------------------------------------------------
badbeats/
├── client/                 # Next.js frontend
│   ├── src/
│   │   ├── app/           # App router pages
│   │   ├── components/    # React components
│   │   ├── hooks/        # Custom React hooks
│   │   └── types/        # TypeScript definitions
│   └── public/           # Static assets
├── server/               # Express.js backend
│   ├── index.js         # Server entry point
│   └── routes/          # API routes
└── electron/            # Desktop application
    ├── main.js         # Main process
    └── preload.js      # Preload scripts

    Development
Client: The Next.js frontend runs on http://localhost:3000
Server: The Express backend runs on http://localhost:3001
API: Access the API at http://localhost:3001/api
Desktop: The Electron app loads the development server in development mode


License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Neon UI inspiration from cyberpunk aesthetics
Audio visualization powered by Web Audio API
Icons and graphics from various open-source projects
Contact
