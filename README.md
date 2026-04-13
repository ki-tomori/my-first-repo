# 🚀 プロジェクト名

[![CI](https://github.com/yourname/project/actions/workflows/ci.yml/badge.svg)](https://github.com/yourname/project/actions/workflows/ci.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue.svg)](https://www.typescriptlang.org/)

> **一言で説明**: このプロジェクトが何をするものか、1〜2文で。

![デモのスクリーンショットやGIF](docs/images/demo.gif)

## 📖 概要

このプロジェクトは〇〇のために開発しました。
〇〇という課題を、△△というアプローチで解決しています。

### なぜ作ったのか（モチベーション）

- 既存の〇〇には△△という課題があった
- □□を実現するツールが存在しなかった
- ××の技術を実践的に学びたかった

## ✨ 主な機能

- **機能A**: 説明
- **機能B**: 説明
- **機能C**: 説明

## 🛠 技術スタック

| カテゴリ | 技術 |
|:--|:--|
| フロントエンド | Next.js 15 / React 19 / TypeScript |
| バックエンド | Node.js / Hono |
| データベース | PostgreSQL / Prisma |
| インフラ | Vercel / Docker |
| CI/CD | GitHub Actions |
| テスト | Vitest / Playwright |

## 🏗 アーキテクチャ

```
[Client] → [Next.js App Router] → [API Routes] → [Prisma] → [PostgreSQL]
                                        ↓
                                  [External APIs]
```

詳細は [docs/architecture.md](docs/architecture.md) を参照してください。

## 🚀 はじめ方

### 前提条件

- Node.js >= 20.x
- Docker & Docker Compose
- pnpm >= 9.x

### セットアップ

```bash
# リポジトリをクローン
git clone https://github.com/yourname/project.git
cd project

# 環境変数を設定
cp .env.example .env
# .env を編集して必要な値を設定

# 依存関係をインストール
pnpm install

# データベースを起動
docker compose up -d

# マイグレーションを実行
pnpm db:migrate

# 開発サーバーを起動
pnpm dev
```

http://localhost:3000 でアプリケーションにアクセスできます。

### テストの実行

```bash
# ユニットテスト
pnpm test

# E2Eテスト
pnpm test:e2e

# カバレッジレポート
pnpm test:coverage
```

## 📝 デモ

🔗 **ライブデモ**: [https://project.vercel.app](https://project.vercel.app)

| 機能 | スクリーンショット |
|:--|:--|
| ダッシュボード | ![dashboard](docs/images/dashboard.png) |
| 検索機能 | ![search](docs/images/search.png) |

## 📄 ライセンス

このプロジェクトは [MIT License](LICENSE) の下で公開されています。
