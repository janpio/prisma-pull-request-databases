# prisma-pull-request-databases

A repository that creates a unique database for each PR with its Prisma Schema.

- GH Action that is run on PR pushes
- Manipulate database connection string from environment variables to have unique database name
- Use Prisma Migrate to create database and migrate database
- Use seeding to populate database with data
- Run Prisma Studio via ngrok to make database and data accessible
- 
