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
$ npx prisma studio # ブラウザでデータベースを確認 https://localhost:5555
```

# Ref

- https://www.prisma.io/docs/getting-started/quickstart-sqlite
