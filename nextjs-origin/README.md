1. Technology used
   Frontend: Next.js v14 (typescript), auth.js v5 (next-auth)
   Backend: Nest.js v10 (typescript), endpoint authentication with JWT (json web token)
   Database: MongoDB for free use with MongoDB Atlas
   (in the course I use docker - files are provided to follow)

2. Main features (demo)

How I base the project from scratch, how to read the documentation...
CRUD users (next.js + nestjs)
Integrate JWT for nestjs
Send email (according to template) with nestjs
Login login/register/forgot password

When registering (new account), need to authenticate the account via email

When logging in (if the account is not authenticated), need to authenticate via email

When forgetting password, need to confirm via email

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
