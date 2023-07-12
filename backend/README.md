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
$ DEBUG=backend:* npm start
```