This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Install the node_modules

```bash
npm install -g husky
npm install
```

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

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Code Quality and Formatting

This project uses Husky to enforce code quality and formatting. Husky is a tool that allows you to create hooks for your Git repository. In this project, we use Husky to run Prettier and ESLint before committing code.

## Prettier

Prettier is a code formatter that helps keep your code clean and consistent. It is configured to format your code according to the .prettierrc file in the project root.

## ESLint

ESLint is a linter that helps catch errors and enforce coding standards. It is configured to use the eslint-config-next configuration, which is a set of rules specifically designed for Next.js projects.

## Docker Integration

To run this project with Docker, you can use the provided Dockerfile and docker-compose.yml.
[Commands]
you need to run this cmd only one time during project setup
[DockerBuildCmd]

```bash
docker-compose up --build
```

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
# sooqcars
# sooqcars
