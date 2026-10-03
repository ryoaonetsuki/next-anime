# Next Anime

An anime-focused web application for browsing and presenting content.

## Requirements

- Node.js
- npm
- Database configured for Prisma

## Installation

```bash
git clone https://github.com/ryoaonetsuki/next-anime.git
cd next-anime
npm install
```

The project uses a post-install Prisma generation step. Configure the database before using database-backed features.

## Development

The development server is configured to use port 4099:

```bash
npm run dev
```

## Production

```bash
npm run build
npm start
```

## Database

The project uses Prisma. Check the Prisma schema and environment configuration before running database migrations or generating the client.

## Configuration

Provide the required database and application environment values through the local environment configuration. Never commit secrets.

## Notes

External content providers and APIs may change independently of the application.
