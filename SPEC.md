# AIプロンプト設計ツール【無料】無料Webツール - 技術仕様書

## 概要

**サービス名**: Ai Prompt Designer
**バージョン**: 1.0.0
**更新日**: 2026-05-27
**URL**: https://appadaycreator.com/ai-prompt-designer/

目的・ジャンル・出力形式を選ぶだけで効果的なAIプロンプトを自動生成。ChatGPT・Claude対応。登録不要・完全無料でご利用いただけます。

## データ管理

- **ストレージ**: ブラウザ localStorage（外部API通信なし）
- **永続化**: ページ読み込み時に自動復元
- **クリア**: ブラウザのサイトデータ削除で初期化

## 技術スタック

- HTML5 / CSS3 / Vanilla JavaScript
- PWA対応（manifest.json / Service Worker）
- レスポンシブデザイン（モバイルファースト）

## 使い方

1. 生成したい内容の種類・条件を選択する
2. キーワードや詳細設定を入力する
3. 「生成」ボタンをクリックして出力を取得する
4. 生成された内容をコピーして活用する
5. 条件を変えて複数パターンを試す

## よくある質問（FAQ）

**Q: AIプロンプト設計ツールは無料で使えますか？**

はい、完全無料・登録不要でご利用いただけます。

**Q: 生成した内容を商用利用できますか？**

生成されたコンテンツはご自由にご利用いただけます。内容の最終確認はご自身でお願いします。

**Q: 何回でも生成できますか？**

はい、回数制限なく何度でも生成いただけます。

**Q: 生成データはサーバーに保存されますか？**

いいえ。すべてブラウザ内で生成され、サーバーへの送信・保存は行いません。

**Q: スマートフォンで利用できますか？**

はい、PC・スマートフォン・タブレットすべてに対応しています。


## 関連サービス

- [Engineer Career Roadmap](https://appadaycreator.com/engineer-career-roadmap/)
- [ブログ・SNS収益化適性診断](https://appadaycreator.com/blog-income-advisor/)
- [ハッシュタグ戦略診断](https://appadaycreator.com/hashtag-strategy-advisor/)

## テスト

| ファイル | フレームワーク | 概要 |
|---------|--------------|------|
| `tests/e2e/` | Playwright | 本番URL対象E2E（Jest対象外） |

## デプロイ

GitHub Pages（mainブランチ push → 自動デプロイ）

## ライセンス

MIT License
