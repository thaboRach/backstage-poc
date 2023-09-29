# Backstage POC

A platform to manage all your software in one place. It gives you a uniform view of all the services a team own and their related resource like deployments, data, pipelines, pull requests etc.

## Getting started

It is recommended that you use docker to run a local instance.

1. Create a `.env` file to store the following environment variables in the root of the project

   ```bash
        POSTGRES_PORT=5432
        POSTGRES_HOST='postgres'
        POSTGRES_USER='postgres'
        POSTGRES_PASSWORD='supersecret'

        AUTH_GITHUB_CLIENT_ID=...
        AUTH_GITHUB_CLIENT_SECRET=...

        GITHUB_TOKEN=...
   ```

1. Start the container

   ```bash
       docker compose up
   ```

You should then start to get logs in your terminal, and then you can open your browser at http://localhost:7007.
