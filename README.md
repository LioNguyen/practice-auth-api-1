[Build an Authentication API with Node.js, TypeScript, Typegoose, ExpressJS & Zod](https://youtu.be/qylGaki0JhY?si=JGKvUCQMk8CNekS2)

[Auth Api Tutorial Repo](https://github.com/TomDoesTech/auth-api-tutorial)

[Typescript paths with ts-node, ts-node-dev, and jest](https://medium.com/@fmoessle/typescript-paths-with-ts-node-ts-node-dev-and-jest-671deacf6428)

# SETUP

## Init project

```bash
yarn init
```

## Install TypeScript

```bash
yarn add typescript --dev
tsc --init
```

## Install dev dependencies

```bash
yarn add typescript ts-node-dev tsconfig-paths @types/express @types/config pino-pretty @types/nodemailer @types/lodash @types/jsonwebtoken -D
```

## Install Express

```bash
yarn add express@5
```

## Install dependencies

```bash
yarn add mongoose @typegoose/typegoose config argon2 pino dayjs nanoid nodemailer lodash jsonwebtoken dotenv zod
```

## Add scripts in package.json

```json
{
  "scripts": {
    "dev": "ts-node-dev -r tsconfig-paths/register --respawn --transpile-only src/app.ts"
  }
}
```
