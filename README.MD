# Prerequisites

Before diving into the test, you'll have a bit of set-up to do.

In order to run the database, make sure you have `docker-compose` installed on your machine. You can see the doc [here](https://docs.docker.com/compose/install/)

Once you're done you would be able to run `docker-compose up` at the root folder of the project.

Next, using your package manager of choice run the following commands in your terminal:
- `cd backend && yarn`
- `cd ../frontend && yarn`

Finally, you can start both the API and the UI by running `yarn dev` in the corresponding folders.

Head to the following urls to check all is working properly:
- `localhost:8080` should prompt you an adminer interface. Loggin with `{system: PostgreSQL, server: db, user: sacha, pwd: bourgpalet, db: eshard}`
- `localhost:3001/` should display a JSON gathering saying that all is working.
- `localhost:3000` should prompt you a grid of pokemons images and names

Congratulations you're all set-up and ready to go!

# Test

This little project is based upon Next.js, Express, prisma and PostgreSQL.