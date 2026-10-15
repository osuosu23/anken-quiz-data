# anken-quiz-data

YouTube案件動画クイズ（`anken-quiz`）向けの動画データ収集・管理リポジトリです。

## 概要
- YouTube Data API v3 を使用して、日本の話題動画（通常動画・PR/タイアップ動画）を収集・仕分けします。
- `data/` 配下にカテゴリ別の JSON データを生成・保持します。

## スクリプト
- `npm run fetch-videos`: YouTube Data API v3 を使用して最新データを取得・更新（要 `YOUTUBE_API_KEY`）
