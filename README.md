## Nestjs migrations

To run this repo, create a `.env` file for the docker compose file and for the nestjs backend.
I have added the `.example` postfix on my already existing env files.

To run the database container:

> docker compose up --build --detach

Go to the `migrations-backend` directory and run:

> npm run start:dev

The migrations scripts are inside the `package.json` file inside the `migrations-backend` directory
