# SankalpSocial

<div align="center">
  <strong>
  <h2>Your ultimate AI social media scheduling tool</h2><br />
  SankalpSocial: An alternative to Buffer.com, Hypefury, Twitter Hunter, etc...<br /><br />
  </strong>
  SankalpSocial offers everything you need to manage your social media posts,<br />build an audience, capture leads, and grow your business.
</div>

<p align="center">
<a href="https://opensource.org/license/agpl-v3">
  <img src="https://img.shields.io/badge/License-AGPL%203.0-blue.svg" alt="License">
</a>
</p>

<div class="flex" align="center">
  <br />
  <img alt="Instagram" src="https://postiz.com/svgs/socials/Instagram.svg" width="32">
  <img alt="Youtube" src="https://postiz.com/svgs/socials/Youtube.svg" width="32">
  <img alt="Dribbble" src="https://postiz.com/svgs/socials/Dribbble.svg" width="32">
  <img alt="Linkedin" src="https://postiz.com/svgs/socials/Linkedin.svg" width="32">
  <img alt="Reddit" src="https://postiz.com/svgs/socials/Reddit.svg" width="32">
  <img alt="TikTok" src="https://postiz.com/svgs/socials/TikTok.svg" width="32">
  <img alt="Facebook" src="https://postiz.com/svgs/socials/Facebook.svg" width="32">
  <img alt="Pinterest" src="https://postiz.com/svgs/socials/Pinterest.svg" width="32">
  <img alt="Threads" src="https://postiz.com/svgs/socials/Threads.svg" width="32">
  <img alt="X" src="https://postiz.com/svgs/socials/X.svg" width="32">
  <img alt="Slack" src="https://postiz.com/svgs/socials/Slack.svg" width="32">
  <img alt="Discord" src="https://postiz.com/svgs/socials/Discord.svg" width="32">
  <img alt="Mastodon" src="https://postiz.com/svgs/socials/Mastodon.svg" width="32">
  <img alt="Bluesky" src="https://postiz.com/svgs/socials/Bluesky.svg" width="32">
</div>

## ✨ Features

- Schedule all your social media posts (many AI features)
- Measure your work with analytics
- Collaborate with other team members to exchange or buy posts
- Invite your team members to collaborate, comment, and schedule posts

## Tech Stack

- NX (Monorepo)
- NextJS (React)
- NestJS
- Prisma (Default to PostgreSQL)
- Redis (BullMQ)
- Resend (email notifications)

## Quick Start

### Using Docker Compose (Recommended)

1. Clone this repository:
```bash
git clone https://github.com/vsrn09/sankalpsocial.git
cd sankalpsocial
```

2. Build and start all services:
```bash
docker-compose -f docker-compose.dev.yaml up -d --build
```

3. Access the application:
- Frontend: http://localhost:4200
- Backend API: http://localhost:3000
- PostgreSQL: localhost:5432
- Redis: localhost:6379
- PG Admin: http://localhost:8081 (admin@admin.com / admin)
- RedisInsight: http://localhost:5540

### Manual Installation

For detailed manual installation instructions, please refer to the original [Postiz documentation](https://docs.postiz.com/quickstart).

## Docker Alpine Build Fixes

This fork includes important fixes for Docker builds on Alpine Linux:
- Prisma binary targets configured for `linux-musl-openssl-3.0.x`
- `bcrypt` native module rebuild support
- Proper `STORAGE_PROVIDER` environment variable configuration
- Nginx reverse proxy configuration for uploads

## License

This repository's source code is available under the [AGPL-3.0 license](LICENSE).

## Credits

This project is based on [Postiz](https://github.com/gitroomhq/postiz-app) - an amazing open-source social media scheduling tool. SankalpSocial is a fork with Docker and Alpine Linux improvements.

<p align="center">
  <strong>Built with determination and resolve - Sankalp Social</strong>
</p>
