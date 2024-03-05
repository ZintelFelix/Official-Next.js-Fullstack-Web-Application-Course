## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## Fresh Install to Develop:

1. Add `.env` with the PostgreSQL content found on Vercel.
2. Install npm with: 
    ```bash
    npm i
    ```
3. Install debounce: 
    ```bash
    npm i use-debounce
    ```
4. Run for the Dashboard to work.
    ```bash
    npm run build
    ``` 
5. Install NextAuthJs with: 
    ```bash
    npm install next-auth@beta
    ```
6. Generate a new secret key for the Application with: 
    ```bash
    openssl rand -base64 32
    ```
7. Then, in your `.env` file, add your generated key to the `AUTH_SECRET` variable.
