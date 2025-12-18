# Eventora

Discover events that inspire your world.

## What it does

* Discover upcoming events
* Browse events by interest
* View detailed event information
* Explore tech meetups, workshops, concerts, and more
* Works seamlessly on desktop and mobile

That’s it.

## Why I built this

I wanted a clean and modern way to discover meaningful events without jumping across multiple platforms.
So I built Eventora.

## Tech Stack

* Next.js
* Tailwind CSS
* shadcn/ui
* Clerk
* Convex for DB
* JWT

## How it works

1. Events are displayed in a clean, curated interface
2. Users browse and explore events
3. Each event shows detailed information
4. The interface adapts smoothly across devices

## Setup (Local)

1. Clone the repo
2. Install dependencies
3. Run the app

```bash
npm install
npm run dev
```

## Environment Variables

Create a `.env.local` file with the following variables:

```bash
CONVEX_DEPLOYMENT=your_convex_deployment
NEXT_PUBLIC_CONVEX_URL=https://your-project.convex.cloud
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_your_clerk_publishable_key
CLERK_SECRET_KEY=sk_test_your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
CLERK_JWT_ISSUER_DOMAIN=https://clerk.your-domain.com
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=your_unsplash_access_key
GEMINI_API_KEY=your_gemini_api_key
CRON_SECRET=your_cron_secret
```

**Om Sharma**  
Indie developer building useful, real-world products.  
🔗 [LinkedIn](https://www.linkedin.com/in/om-sharma1905/)