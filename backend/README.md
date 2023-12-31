# re-realworld backend

- express 公式ドキュメントの express-generator から作成
  - https://expressjs.com/en/starter/generator.html
- 機能は express 公式ドキュメントを参考して実装

### サーバ実行コマンド

```bash
$ npm install
# DB migrate
$ npx prisma migrate dev --name init
# サーバ起動
$ npm start
OR
$ DEBUG=backend:* npm start
OR
$ npm devstart
```

### swagger url

http://localhost:3000/api-docs

### 参考 URL

- express
  - https://expressjs.com/
  - https://github.com/geshan/expressjs-structure/tree/master/src
  - https://github.com/expressjs/express/tree/master/examples
- prisma
  - https://github.com/prisma/prisma-examples/tree/latest/javascript
- jest
  - https://www.albertgao.xyz/2017/05/24/how-to-test-expressjs-with-jest-and-supertest/
- etc..
