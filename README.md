# laravel_vite_react プロジェクト
このプロジェクトは、Laravel 11アプリケーションにViteとReactを統合したものです。このプロジェクトの目的は、Viteをビルドツールとして使用してLaravelでReactをセットアップおよび使用する方法を示すことです。

## インストール
1. **リポジトリをクローンする:**
    ```sh
    git clone https://github.com/eyamagishi/laravel_vite_react.git
    cd laravel_vite_react
    ```

2. **PHP依存関係をインストールする:**
    ```sh
    composer install
    ```

3. **JavaScript依存関係をインストールする:**
    ```sh
    npm install
    ```

4. **環境ファイルのコピーとアプリケーションの設定:**
    ```sh
    cp .env.example .env
    php artisan key:generate
    ```

5. **`.env`ファイルの設定:**
   `.env`ファイルにデータベースやその他必要な設定を正しく記入してください。

6. **データベースのマイグレーションを実行する:**
   ```sh
   php artisan migrate
   ```

## 使用方法
1. **Laravel開発サーバーを起動する:**
    ```sh
    php artisan serve
    ```

2. **Vite開発サーバーを起動する:**
    ```sh
    npm run dev
    ```

3. **アプリケーションにアクセスする:**  
    ブラウザで http://localhost:8000 にアクセスしてください。

## 開発
1. **コードのリントを実行する:**
    ```sh
    npm run lint
    ```

2. **テストを実行する:**
    ```sh
    php artisan test
    npm run test
    ```

## ビルド
アプリケーションのプロダクションビルドを作成するには:

```sh
npm run build
```

これにより、最適化されたアセットが public ディレクトリに生成されます。

## 貢献
このプロジェクトはLaravel11のVite環境でReactを利用するのを勉強するために作成したものです。そのため貢献は特にないです。

## ライセンス
上に同じで特にないです。

## 参考リンク
- [Laravel9のVite環境でReactを利用する方法](https://reffect.co.jp/laravel/laravel9_vite_react#google_vignette)
- [Laravel](https://laravel.com/)
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
