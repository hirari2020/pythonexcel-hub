# pythonexcel-hub

板橋区立企業活性化センターの技術勉強会向けに作成した、生成AI・AIエージェントの俯瞰ダッシュボード集です。

公開URL: **https://hub.pythonexcel.net/**

## 構成

- `/` — トップページ（各ダッシュボードへのリンク集）
- `/chat-ai/` — チャット型AI ダッシュボード
- `/ai-agents/` — AIエージェント ダッシュボード
- `/japan-ai/` — 日本ブランド生成AI ダッシュボード
- `/icons/` — サービスアイコン（ローカルホスト）

## 技術メモ

- 静的HTMLのみ（ビルド不要）
- GitHub Pages + カスタムドメイン
- アイコンはすべて `icons/` 配下でセルフホスト
- 情報は2026年5月時点のスナップショット

## 更新

Claude Code 経由でファイルを編集し、`git push` すると GitHub Pages が自動デプロイします。
