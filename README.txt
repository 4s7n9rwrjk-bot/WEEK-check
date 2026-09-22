WEEK check v3

1. Google CloudでGoogle Calendar APIを有効化
2. WebアプリケーションのOAuthクライアントIDを作成
3. 承認済みのJavaScript生成元にRenderのURLを登録
4. APIキーを作成し、Google Calendar APIに制限
5. google-config.js に Client ID と API Key を入力
6. GitHubへ4ファイルをアップロードしてRenderを再デプロイ

重要:
- Client Secretはgoogle-config.jsに入れません。
- Google Calendarの読み取り専用スコープを使用します。
- この版はGoogle公式JavaScriptクイックスタートのgapiLoaded/gisLoaded方式で初期化します。
