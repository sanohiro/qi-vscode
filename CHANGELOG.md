# Changelog

このファイルは、Qi VSCode拡張機能のすべての重要な変更を記録します。

バージョン番号は[Semantic Versioning](https://semver.org/lang/ja/)に従います。
バージョンはqi-langのバージョンと同期させます。

## [未リリース]

### 追加
- 初期プロジェクト構成

## [0.1.0] - 未定

### 追加
- Qi言語のシンタックスハイライト
- 言語設定（コメント、ブラケット、自動閉じ括弧など）
- 基本的なスニペット集
- Qiファイル実行コマンド (`qi.runFile`)
- REPL起動コマンド (`qi.startRepl`)
- デバッグサポート (`qi.debugFile`)
- ドキュメント表示コマンド (`qi.showDocs`)
- キーバインディング設定
  - `Cmd/Ctrl+F5`: ファイルを実行
  - `Cmd/Ctrl+Shift+R`: REPL起動
  - `F5`: デバッグ開始
- 設定項目
  - `qi.executablePath`: Qi実行ファイルのパス
  - `qi.enableLinting`: リンティング有効化
  - `qi.repl.autoStart`: Qiファイルを開いた時の自動REPL起動

### 変更
- なし

### 非推奨
- なし

### 削除
- なし

### 修正
- なし

### セキュリティ
- なし

---

## バージョン管理ポリシー

- **バージョン番号**: qi-langのバージョンと同期
- **リリースタイミング**: qi-langの主要アップデートに合わせてリリース
- **手動同期**: qi-langのバージョンが更新された場合、package.jsonとこのCHANGELOGを手動で更新

[未リリース]: https://github.com/sanohiro/qi-vscode-new/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/sanohiro/qi-vscode-new/releases/tag/v0.1.0
