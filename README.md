# sql-container
### 環境構築
1. docker desktopがインストールされていることを確認する。
2. ソースコードを任意のディレクトリにクローン。
3. dockerのネットワークを作成
   ```
   docker network create default_network
   ```
   これでdefault_networkで他のコンテナから接続できる。
4. コンテナを起動
   ```
   docker compose up -d
   ```