
# Hyperhire Assesment

Application currently available to access in https://fe-hyperhire.kabpaser.id
## Requirements
- NodeJS > 18

## Installation Process
First things you need to clone repository.

Create database in your postgresSQL then in folder backend create file `.env` add key for access database with `DATABASE_URL`.

For backend
```bash
    cd backend
    npm i
    npx prisma migrate dev --name init
    npm run build
    npm run start
```
backend will run by default on `http://localhost:3000`

Then for frontend part. Add file .env.local inside folder `frontend`, add key `NEXT_PUBLIC_BACKEND_URL` with value url backend. After that run this

```bash
    cd frontend
    npm i && npm run build
    npm start
```
frontend will run by default on `http://localhost:3001`.

## Authors

- Sadriansyah

