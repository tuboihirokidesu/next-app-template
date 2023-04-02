# Next.js + Tailwind CSS + Supabase テンプレート

このプロジェクトは、Next.js、Tailwind CSS、Supabase を使用して Web アプリケーションを構築するためのテンプレートです。以下の手順に従って、ローカルマシンでこのテンプレートを実行することができます。

## インストール

このプロジェクトを実行するには、ローカルマシンに Node.js と Yarn がインストールされている必要があります。

1. このリポジトリをクローンします。

```bash
git clone https://github.com/tuboihirokidesu/next-app-template.git
```

2. クローンしたリポジトリのディレクトリに移動します。

```bash
cd next-app-template
```

3. 依存関係をインストールします。

```bash
yarn install
```

4. 環境変数を設定します。

```bash
cp .env.local.example .env.local
```

5. [Supabase](https://supabase.io/)でアカウントを作成し、プロジェクトを作成して、プロジェクトの API キーを`.env.local`ファイルに追加します。

```bash
NEXT_PUBLIC_SUPABASE_URL=<your_supabase_url>
NEXT_PUBLIC_SUPABASE_ANON_KEY=<your_supabase_anon_key>
```

## 開発サーバーの実行

1. 開発サーバーを起動します。

```bash
yarn dev
```

2. ブラウザで`http://localhost:3000`にアクセスして、アプリケーションが正常に実行されていることを確認します。

## 本番用ビルド

1. アプリケーションを本番用にビルドします。

```bash
yarn build
```

2. アプリケーションを起動します。

```bash
yarn start
```

3. ブラウザで`http://localhost:3000`にアクセスして、アプリケーションが正常に実行されていることを確認します。

## テスト

このプロジェクトには、自動テスト用のテンプレートが含まれていません。テストを実装する場合は、Jest や React Testing Library などのツールを使用して、適切なテストを作成する必要があります。
