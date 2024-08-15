# nestjs-nextjs-auth-demo-typescript

1. Technology used
   Frontend: Next.js v14 (typescript), auth.js v5 (next-auth)
   Backend: Nest.js v10 (typescript), endpoint authentication with JWT (json web token)
   Database: MongoDB free to use with MongoDB Atlas
   (in the course I use docker - files provided for tracking)

2. Main features (demo)

How I built the project from scratch, how to read the documentation...
CRUD users (next.js + nestjs)
JWT integration for nestjs
Send email (by form) with nestjs
Login login/register/forgot password

When registering (new account), need to authenticate the account via email

When logging in (if the account is not authenticated), need to authenticate via email

When forgetting the password, need to confirm via email
