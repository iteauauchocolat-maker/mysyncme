# mysyncme

キャラクターと対話できる、Gemini API ベースの AI エージェント Web アプリ。

🌐 **公開 URL**: https://iteauauchocolat-maker.github.io/mysyncme/aiag.html

## 特徴

- 単一 HTML ファイル(`aiag.html`)で完結 — サーバー不要
- Gemini API を使ったキャラクター対話(各ユーザーが自分の API キーを使用)
- 複数キャラクター切替(現在: ミル・プイ の 2 キャラ)
- キャラごとに口調・性格・テーマカラー・表情が切替
- iPhone Safari 最適化 + ホーム画面追加対応(PWA 的利用)
- データは全て LocalStorage に保存(プライバシー配慮)

## 使い方

1. https://iteauauchocolat-maker.github.io/mysyncme/aiag.html にアクセス
2. 設定タブで [Google AI Studio](https://aistudio.google.com/app/apikey) で取得した API キーを登録
3. チャットタブでキャラクターと対話開始
4. ヘッダーのキャラ名(▼)をタップでキャラ切替

iPhone なら Safari の共有ボタンから「ホーム画面に追加」でアプリのように使える。

## 開発について

Claude Code を使った開発を想定。設計方針・お約束は [`CLAUDE.md`](./CLAUDE.md) を参照。

詳細ドキュメント:
- [`docs/decisions.md`](./docs/decisions.md) — 設計判断の経緯
- [`docs/roadmap.md`](./docs/roadmap.md) — 開発ロードマップ
- [`docs/characters.md`](./docs/characters.md) — キャラクター設定

## ライセンス

個人利用想定。商用利用や再配布は予定していない。
