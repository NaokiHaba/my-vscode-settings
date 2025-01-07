# VS Code 設定

このプロジェクトのVS Code設定とおすすめの拡張機能について説明します。

## JetBrains Monoフォントのインストール

JetBrains Monoは、コーディング用に最適化された読みやすいモノスペースフォントです。以下の手順でインストールできます：

1. [JetBrains Mono公式サイト](https://www.jetbrains.com/lp/mono/)からフォントをダウンロード

2. システムフォントへのインストール:
   - ダウンロードしたzipファイルを解凍
   - `.ttf`ファイルを以下のディレクトリにコピー:
     - Mac: `/Library/Fonts/`
     - Windows: `C:\Windows\Fonts\`

3. VS Codeの設定:
   - このプロジェクトではすでに`settings.json`で設定済み:
   ```json
   {
     "editor.fontFamily": "JetBrains Mono",
     "editor.fontLigatures": true
   }
   ```

4. VS Codeを完全に再起動（`Cmd/Ctrl + Q`で終了後、再起動）

## 拡張機能

必要な拡張機能は`extensions.json`に記載されています。VS Codeで推奨拡張機能として表示されます。

主な拡張機能:
- ESLint
- Volar (Vue Language Features)
- GitLens
- Error Lens
- Copilot
- Vitesse Theme
など

## その他の設定

- エディタの設定（インデント、フォントサイズなど）
- Git関連の設定
- ファイル自動保存
- 検索除外設定

詳細は`settings.json`を参照してください。
