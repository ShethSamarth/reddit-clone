# Reddit Clone

This is a repository for Reddit Clone: Next.js 13.4, React, TailwindCSS, ShadCN UI, MySQL, Upstash Redis, Next-Auth.

Key Features:

- Infinite scrolling for dynamically loading posts
- Authentication using NextAuth & Google
- Custom feed for authenticated users
- Advanced caching using Upstash Redis
- Optimistic updates for a great user experience
- Modern data fetching using React-Query
- A beautiful and highly functional post editor
- Image uploads & link previews
- Full comment functionality with nested replies
- Uploading and commenting on post
- Creating and joining communities
- Image uploads with UploadThing
- Validatation of form data with Zod
- MySQL database with prisma adapter
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices

# Final Version

To visit the website, [click here.](https://reddit-clone-ss.vercel.app/)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/reddit-clone.git
```

### Install packages

```shell
yarn
```

### Setup .env file

```js
DATABASE_URL=

NEXTAUTH_SECRET=
NEXTAUTH_URL=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

### Setup prisma

```shell
npx prisma db push
```

### Start the app

```shell
yarn run dev
```
