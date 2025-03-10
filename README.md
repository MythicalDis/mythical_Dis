# Duality Game

A 3D adventure game where players experience the power of duality, choosing between light and dark paths with unique characters and storylines.

## Features

- Two playable characters: Malice (Evil Mastermind) and Lumina (Accidental Hero)
- Multiple game modes: Story Mode, Versus Mode, and Challenges
- Rich narrative with branching storylines
- Modern UI with smooth animations and transitions
- Real-time 3D graphics using Three.js

## Tech Stack

- Next.js
- React
- Three.js
- TypeScript
- PostgreSQL
- Redis
- Stripe for payments
- Docker support

## Prerequisites

- Node.js 18+
- npm or yarn
- Docker (optional)
- PostgreSQL (optional if using Docker)
- Redis (optional if using Docker)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/duality-game.git
cd duality-game
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```
Edit `.env.local` with your configuration.

## Development

Run the development server:
```bash
npm run dev
```

## Docker Development

Using Docker Compose:
```bash
docker-compose up --build
```

## Deployment

### Vercel Deployment
```bash
vercel
```

### Docker Production Deployment
```bash
docker build -t duality-game .
docker run -p 3000:3000 duality-game
```

## Environment Variables

Required environment variables:
- `DATABASE_URL`: PostgreSQL connection string
- `REDIS_URL`: Redis connection string
- `STRIPE_SECRET_KEY`: Stripe secret key
- `STRIPE_WEBHOOK_SECRET`: Stripe webhook secret
- `NEXT_PUBLIC_API_URL`: Public API URL
- `NEXT_PUBLIC_ASSET_URL`: Public asset URL

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
