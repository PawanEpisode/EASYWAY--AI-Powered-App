This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

# TimePeriod

- Initialized repository using Nextjs, Typescript, Tailwin css, Shadcn ui, eslint etc. 
- Created File structure for application , using App router in nextjs, dynamic routes. 
- Created Route Groups - (auth) and (root)
- Inside (auth) , There is a file layout.tsx which consist of routing  for authentication of the application
- Inside (root) , We have created 3 more nested routes namely - credits, profile, transformations;
- credits and profile are routes pages;
- transormations route consist of dynamic routes and have **id** as dynamic route variable
- Inside transformations dynamically generated routes consist of updated routes
- Also transformation routes consist of **add** url parameters
- Created all the pages components for these specific routes
- Clerk Installation for User Management , Authentication
- Setup Clerk Authentication of application
- Created Signin & Signup folder to consist of Optional catch-all route segment(Dynamic routes)
- UserButton added to HomePage to check if user is logged in
- changes in .env.local file
- Installed different shadcn ui components like Buttons, Sheet .
- Implemented Layout Section for Sidebar and Mobile Navigation
- Two Different Components Created from scratch
- Created constants folder at the root of file structure for constants variables.
- Installed mongodb and mongoose for database management
- a folder called **database** created inside lib folder of root, inside dataabse, the root file is mongoose.ts setting up the connection from database, also implemented cached connecton check. 
- Created models for our database of the application- image, user, transaction
- Using Server Actions, when creating user, we sync Clerks user data to our backend using something known as webhook
- CRUD functionality for user actions meaning creating , viewing , updating and deleting users
- Implementing route.ts for CRUD operations. 
- Added utility folder for utilities files and functions
- created user actions for CRUD operations
- defined all types for type checking each variable and component
- webhooks added to sync data with clerk 
- middleware updated
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
