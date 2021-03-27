# prisma-pull-request-databases

A repository that creates a unique database for each PR with its Prisma Schema.

- GH Action that is run on pushes
- Manipulate database connection string from environment variables to have unique database name if in Pull Request
- Use Prisma Migrate (`db push`) to create database and migrate database schema
- Run Prisma Studio via ngrok to make database accessible
