## Project Setup

This repo uses ddev.

Steps for initial setup:

- clone
- `ddev start`
- copy env: `cp .env.example .env`
- `ddev artisan key:generate`
- `ddev composer i`
- `ddev artisan migrate:fresh --seed`
- Login at https://paleraventattoos.ddev.site/cp/ using admin@example.com with pw 'secret'