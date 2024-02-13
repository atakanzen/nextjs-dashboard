# InnVoice - A Next.js App Router Dashboard


InnVoice is an application management platform that is fully built with Next.js capabilities. With the recent update to Next.js we can leverage App Router to enable server components. Which we can directly run SQL queries for fetching and updating data. Please see the `app/lib/data.ts` file for some example functions that handle these data actions. 

> Read more about server components and app-router [here](https://nextjs.org/docs/app)

## Accessing the App

Application can be reached from [here](https://nextjs-dashboard-psi-eight-77.vercel.app/). The login credentials are as below: 
```yml
email: user@nextmail.com
password: 123456
```

## App Short Demo



https://github.com/atakanzen/nextjs-dashboard/assets/59116264/defd91af-38b4-4cdd-b08f-524732539e79



## Deployment

The deployment of the application is configured on [Vercel](https://vercel.com/). We're also using Vercel's own storage solution, which is a Postgres Database. 

Additionally, the CI/CD integration is also integrated with the GitHub repository of the project. Here's how it works in summary: 

- Everytime there is a push to the `main` branch, Vercel detects the changes and it starts up a new deployment right away. 
- Everytime there is a new branch made on the repository, Vercel also creates a "preview" environment to be able to test the changes in live environments.


## Contributioners

Atakan Zengin: Deployment - Full-Stack
Vladimir Chukhlebov: Backend - SQL Queries
Mikhail Kisliakov: Front-End - Design

