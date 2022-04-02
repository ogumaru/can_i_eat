# can_i_eat

## これなに

食の好みやアレルギーの管理を行うアプリケーション

## 機能

- ユーザ認証
- 好み、アレルギー情報の登録
- 食べ物情報の検索
- 食べ物情報の削除
- エイリアスの登録、検索

## 利用した主なもの

### 実装

| 名称        | 用途                |
| ----------- | ------------------- |
| Next.js     | フロントエンド, API |
| Prisma      | データベース操作    |
| MUI         | UI コンポーネント   |
| AWS Amplify | 認証コンポーネント  |

### デプロイ

| 名称        | 用途         |
| ----------- | ------------ |
| Vercel      | デプロイ環境 |
| PlanetScale | データベース |
| AWS Cognito | ユーザ認証   |

## TODO

- テスト
- 概要などの更新
- 画面デザイン(エイリアス, ログアウト, リスト部分など)
