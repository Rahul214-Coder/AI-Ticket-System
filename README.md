
## AI-Ticket-Assistant 🚀

Welcome to the AI-Powered Ticket Management System! This web app uses AI to categorize, prioritize, and assign support tickets automatically.

## Features

- AI-driven ticket categorization, priority, and suggestions
- Skill-based moderator assignment with fallback to admin
- JWT-based role authentication and user management
- Background ticket processing with Inngest and email notifications


## Tech Stack

- Node.js, Express, MongoDB, JWT

- Inngest for background jobs

- Google Gemini API for AI integration

- Nodemailer + Mailtrap for emails

## Setup

1. Clone repo & install dependencies

2. Add .env with DB, JWT, Mailtrap, Gemini config

3. Run npm run dev & npm run inngest-dev to start app
