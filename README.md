# Nuxt Travel Log

A full stack application built with Nuxt that allows users to keep track of all the places they've been.

## Setup

Make sure to install dependencies:

````bash
# npm
npm install

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev

## Production

Build the application for production:

```bash
# npm
npm run build

Locally preview production build:

```bash
# npm
npm run preview
````

### WSL Commands (Won't work on bash)

<!-- start up local db -->

turso dev --db-file local.db

<!-- create tables on db -->

npx drizzle-kit migrate

<!-- test -->

npx drizzle-kit studio
