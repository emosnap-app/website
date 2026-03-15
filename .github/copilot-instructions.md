# GitHub Copilot カスタム指示（website）

## コミュニケーション
- 回答は日本語で行う

## コミット
- コミットメッセージは必ず日本語で書く
- `git add` / `git commit` はユーザーの明示的な指示があるまで勝手に実行しない

## リポジトリ運用（重要）
- この `website` ディレクトリの変更は `emosnap-app/website`（`origin`）へ反映する
- website のコミットや push を行う前に `git -C website status` で対象変更を確認する
- `ios` 側の変更と混同しない