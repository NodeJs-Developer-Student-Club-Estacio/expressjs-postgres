---
title: ExpressJS Postgres
description: An ExpressJS server that connects to a PostgreSQL database
tags:
  - express
  - postgresql
  - typescript
---

# ExpressJS Postgres Example

This example starts an [ExpressJS](https://expressjs.com/) server that connects
to a Railway PostgreSQL database.

## ✨ Features

- Postgres
- Express
- TypeScript

## 💁‍♀️ How to use

- Install dependencies `yarn`
- [Create a Railway project with the Postgres plugin](https://dev.new)
- Connect to your Railway project `railway link`
- Start the server `railway run yarn dev`

## 📝 Notes

The server started simply returns the current time in the database. The SQL
query is located in `src/index.js`.
