# InnVoice - A Next.js App Router Dashboard

InnVoice is an application management platform that is fully built with Next.js capabilities. With the recent update to Next.js we can leverage App Router to enable server components. Which we can directly run SQL queries for fetching and updating data. Please see the `app/lib/data.ts` file for some example functions that handle these data actions. 

> Read more about server components and app-router [here](https://nextjs.org/docs/app)

# Deployment

The deployment of the application is configured on [Vercel](https://vercel.com/). We're also using Vercel's own storage solution, which is a Postgres Database. 

Additionally, the CI/CD integration is also integrated with the GitHub repository of the project. Here's how it works in summary: 

- Everytime there is a push to the `main` branch, Vercel detects the changes and it starts up a new deployment right away. 
- Everytime there is a new branch made on the repository, Vercel also creates a "preview" environment to be able to test the changes in live environments.
