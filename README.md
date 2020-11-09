# Push From

このリポジトリ（のGithub Actions）から、ファイルを別のリポジトリにPushします。

この[ワークフロー](.github/workflows/push_to_another_repo.yaml)ではAPIトークンが必要です。

1. [New personal access token](https://github.com/settings/tokens/new)ページで、スコープにrepoを選択してトークンを生成します。
2. プロジェクトのSettingsから、`API_TOKEN_GITHUB`の名前で先程のトークンを設定します。

これで、このリポジトリにPushがあると[push-to](https://github.com/taq-fujihara/push-to)リポジトリに`output`フォルダの中身がPushされます。

このリポジトリはプライベートでも構いません。
