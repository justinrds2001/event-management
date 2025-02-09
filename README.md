# Event management App

## Overview

This is a simple Event management API application built as part of a Udemy course. The app allows users to manage events, attendees and sent emails. The app is built with Laravel.

## Features

- Authentication with Laravel Sanctum
- Authorization with Laravel Policies
- Create, read, update, and delete events
- Create, read, update, and delete attendees
- Run cron job to send emails to attendees

## Tech Stack

- **Laravel** - Main framework for backend and business logic
- **Docker Compose** - Containerized development environment

## Installation

### Prerequisites

- Docker & Docker Compose for database & db client
- PHP ^8.2 installed on your machine (or with docker)
- Composer installed on your machine (or with docker)

### Steps

1. Clone this repository:
   ```sh
   git clone git@github.com:{github_username}/event-management.git
   cd event-management
   ```
2. Copy the environment file:
   ```sh
   cp .env.example .env
   ```
3. Start the database server using Docker Compose:
   ```sh
   docker-compose up -d
   ```
4. Run Laravel migrations and seed database (if needed):
   ```sh
   php artisan migrate --seed
   ```

## Usage

- Add new tasks through the UI
- Mark tasks as completed/incomplete
- Delete tasks when no longer needed

## Development

To start a development environment:

```sh
   php artisan serve
```
