# 在庫管理システム (Inventory Management System)

このプロジェクトは、React を使用したフロントエンドと、Node.js/Express を使用したバックエンドから成る在庫管理システムです。商品情報の管理や在庫アラート機能などを提供します。

## プロジェクト構成
inventory-management-system/ ├── client/ # フロントエンド (React) ├── server/ # バックエンド (Node.js, Express) └── db/ # データベーススキーマやマイグレーションファイル


## 必要要件

- Node.js
- MySQL (または他のデータベース)

## サーバーの立ち上げ方法

1. **依存パッケージのインストール**  
   `server` ディレクトリに移動して依存関係をインストールします。

   ```bash
   cd server
   npm install

