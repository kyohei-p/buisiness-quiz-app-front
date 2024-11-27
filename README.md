# 環境構築（フロントエンド）
## node.jsのインストール〜バージョン切り替え
```
nvm install 18.18.0
nvm use 18.18.0
```

### nodeバージョン確認
```
nvm list
```

## Next.jsアプリケーション作成
```
npx create-next-app buisiness-quiz-app-front
```

### 設定
```
✔ What is your project named? … buisiness-quiz-app-front
✔ Would you like to use TypeScript? … Yes
✔ Would you like to use ESLint? …  Yes
✔ Would you like to use Tailwind CSS? … Yes
✔ Would you like your code inside a `src/` directory? … Yes
✔ Would you like to use App Router? (recommended) … Yes
✔ Would you like to use Turbopack for next dev? … Yes
✔ Would you like to customize the import alias (@/* by default)? … No
```

## 開発サーバーの起動
http://localhost:4000/ にアクセスして、Next.jsの初期ページが表示されれば成功です。

```
cd buisiness-quiz-app-front
npm run dev
```

## バージョン
name | version
-- | --
node | 18.18.0
next.js | 15.0.3
