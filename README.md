# Fancy Todo Prisma

Fancy Todo Prisma is a simple ToDo application for tracking your activities.

## Technologies Used

- Express.js
- MySQL + Prisma (ORM)

## Installation

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Create a `.env` file and insert `DATABASE_URL="Your-Database-Url"`.

## Directory Structure

- `prisma/`: Manages the database through Prisma.
- `src/`:
  - `controllers/`: Application controllers.
  - `routes/`: Route definitions.
  - `services/`: Business logic and integration with Prisma.
  - `app.js`: Main application configuration.
  - `index.js`: Main application entry point.

## Example Usage

First, make sure you have completed the installation steps above. Then, run the application with `npm run dev`.

Example usage of the API can be found [here](https://documenter.getpostman.com/view/31662650/2s9YkjCPYU).

