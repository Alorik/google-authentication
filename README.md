# Next.js + NextAuth (Google Authentication)

This project demonstrates how to set up **Google Sign-In** with [NextAuth.js](https://next-auth.js.org/) in a Next.js 13+ App Router project.


app/
  api/
    auth/
      [...nextauth]/
        route.ts   # NextAuth API handler
  providers.tsx    # SessionProvider wrapper
  layout.tsx       # Root layout
  page.tsx         # Home page with login/logout