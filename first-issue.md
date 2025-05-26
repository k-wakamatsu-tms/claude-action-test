# Reactプロジェクトの作成方法

このガイドでは、Reactプロジェクトを作成する方法を簡単に説明します。

## 前提条件

以下がインストールされていることを確認してください：
- Node.js (v18以上推奨)
- npm または yarn

## 新しいReactプロジェクトの作成

### 1. Create React Appを使用する方法

最も簡単で一般的な方法です：

```bash
npx create-react-app my-app
cd my-app
npm start
```

### 2. Viteを使用する方法（推奨）

より高速で軽量な開発体験を提供します：

```bash
npm create vite@latest my-app -- --template react
cd my-app
npm install
npm run dev
```

### 3. Next.jsを使用する方法

フルスタックReactアプリケーションの場合：

```bash
npx create-next-app@latest my-app
cd my-app
npm run dev
```

## 基本的なファイル構造

```
my-app/
  ├── public/
  │   └── index.html
  ├── src/
  │   ├── App.js
  │   ├── App.css
  │   ├── index.js
  │   └── index.css
  ├── package.json
  └── README.md
```

## よく使用されるコマンド

- `npm start` または `npm run dev` - 開発サーバーを起動
- `npm run build` - 本番用にビルド
- `npm test` - テストを実行
- `npm install <package-name>` - パッケージをインストール

## 次のステップ

1. お気に入りのエディターでプロジェクトを開く
2. `src/App.js`を編集してカスタマイズを開始
3. 必要に応じて追加のライブラリをインストール（React Router、Material-UIなど）
4. コンポーネントを作成してアプリケーションを構築

これでReactアプリケーションの開発を始める準備が整いました！