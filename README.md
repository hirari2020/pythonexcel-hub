# pythonexcel-hub

生成AI・AIエージェントの俯瞰ダッシュボード集です。

(c) WhiteCloud Consulting Inc.

公開URL: **https://hub.pythonexcel.net/**

## 構成

- `/` — トップページ（各ダッシュボードへのリンク集）
- `/chat-ai/` — チャット型AI ダッシュボード
- `/ai-agents/` — AIエージェント ダッシュボード
- `/japan-ai/` — 日本ブランド生成AI ダッシュボード
- `/local-llm/` — ローカルLLM ダッシュボード
- `/coding-agents/` — 自律型コーディングエージェント ダッシュボード
- `/coding-agents-guide/` — 自律型コーディングエージェント 徹底整理（解説記事）
- `/china-ai/` — 中華系生成AI ダッシュボード
- `/icons/` — サービスアイコン（ローカルホスト）

## アーカイブ（スナップショット）

指定時点のサイト全体を凍結保存したもの。本体を更新してもアーカイブは変更しない。

- `/2026July/` — 2026年7月時点のスナップショット（アイコン含む完全自己完結コピー）

## 技術メモ

- 静的HTMLのみ（ビルド不要）
- GitHub Pages + カスタムドメイン
- アイコンはすべて `icons/` 配下でセルフホスト
- 情報は2026年7月時点のスナップショット

## 更新

Claude Code 経由でファイルを編集し、`git push` すると GitHub Pages が自動デプロイします。
