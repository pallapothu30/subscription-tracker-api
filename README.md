<div align="center">
  
  <div>
    <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" alt="node.js" />
    <img src="https://img.shields.io/badge/express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="express.js" />
    <img src="https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
  </div>

  <h3 align="center">A Subscription Management System API</h3>

</div>

# Subscription Tracker API

This project was created while following a step-by-step tutorial and has been adapted here for learning and local use. It is presented in a neutral, non-promotional form and does not include external affiliate links or community invites.

A simple, self-hosted Node.js API for managing subscriptions and users. This repository contains the server-side code (Express + MongoDB) for creating and tracking subscription records.

## Summary

- Lightweight REST API for subscription tracking
- Authentication via JWT
- MongoDB + Mongoose for data persistence

## Tech Stack

- Node.js
- Express
- MongoDB (Mongoose)

## Features

- User registration and authentication (JWT)
- CRUD operations for subscriptions
- Background/email reminder hooks (configurable)
- Middleware for request validation and error handling

## Quick Start

Prerequisites:

- Node.js (v16+ recommended)
- npm or yarn
- A running MongoDB instance (local or hosted)

Install and run locally:

```powershell
git clone https://github.com/pallapothu30/subscription-tracker-api.git
cd subscription-tracker-api
npm install
```

Create an environment file at the project root (for example `.env`) and provide the values used by the app (example keys shown below):

```env
# Server
PORT=5500

# Database
DB_URI=

# JWT
JWT_SECRET=
JWT_EXPIRES_IN=1d

# Optional: other service keys (only if you enable related features)
# ARCJET_KEY=
# QSTASH_TOKEN=
```

Start the server in development:

```powershell
npm run dev
```

The API will be available at `http://localhost:5500` by default.

## Configuration and Security

- Remove or rotate any sample/placeholder keys before deploying to production.
- Do not commit secrets to version control. Use environment variables or a secrets manager.


