# Prismaに入門するためのリポジトリ

# Getting Started with Prisma

```sh
$ npm init -y
$ npm install typescript tsx @types/node --save-dev
$ npx tsc --init
$ npm install prisma --save-dev
$ npx prisma init --datasource-provider postgresql
$ npx prisma migrate dev --name init
$ touch script.ts
$ npx tsx script.ts
```

# Ref

- https://www.prisma.io/docs/getting-started/quickstart-sqlite
