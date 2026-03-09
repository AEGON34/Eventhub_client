## Event Hub

Live site: https://event-hub-puce-iota.vercel.app/

## Overview

Event Hub is a full-stack event management web application where visitors can browse upcoming events and view details, while authenticated users can create and manage events. The experience focuses on clear navigation, responsive layouts, and reliable data handling across the client and API.

## Tech Stack

### Frontend
- Next.js (App Router)
- React
- Tailwind CSS
- Firebase Authentication
- React Hook Form
- React Hot Toast

### Backend
- Node.js
- Express.js
- MongoDB
- CORS
- Dotenv

## Core Features

- Public event listing and detail pages
- Authenticated event creation and management
- Protected routes with Firebase Authentication
- Toast notifications for key actions
- Responsive layout for mobile, tablet, and desktop

## Authentication

Firebase Authentication secures protected routes. Users can browse events anonymously, and sign in to create or manage events.

## Environment Variables

Sensitive values such as Firebase credentials and the MongoDB connection string are stored in environment variables.

## Routes

- `/` - Landing page
- `/login` - Login page
- `/events` - Event listing page
- `/events/[id]` - Event detail page
- `/add-event` - Protected add event page

## Setup

```bash
git clone https://github.com/your-username/event-hub-client.git
cd event-hub-client
npm install
npm run dev
