# AGENTS.md

Tsubasa.Studioの公開Webリポジトリ。現在の静的サイト構成と公開URLを壊さず、依頼範囲だけを変更する。

## 永続ルール

- 既存の静的HTML/asset構成を尊重し、必要性のないframework・build system・dependencyを追加しない。
- 各アプリの公開ページ、privacyページ、redirect、広告関連ファイルを無関係な変更に巻き込まない。
- URLや公開文言を推測で変更しない。
- 大規模なデザイン刷新やサイト構成変更は、依頼されている場合だけ行う。

実装・公開コンテンツ変更では `.agents/skills/project-change` を使用する。
