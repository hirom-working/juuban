# 焼肉ホルモン十番 LINE公式アカウント

## System
- purpose: 焼肉ホルモン十番のLINE公式アカウント運用（ショップカード・リッチメニュー・クーポン・SNS連携）
- type: webapp
- lang: HTML/CSS（静的ページ）、将来的にBot化時はTBD
- deploy: SNSページ → GitHub Pages or Cloudflare Pages（未決定）
- repo: ~/Projects/juuban

## Architecture
- Phase 1（現在）: LINE標準機能 + 静的SNSリンクページ
- Phase 2（将来）: LINE Messaging API + カスタムBot

## Dependencies
| 依存先 | 接続情報 | 用途 |
|--------|----------|------|
| LINE Official Account Manager | https://manager.line.biz/ | アカウント管理・設定 |
| 公式サイト | https://yakinikujyuban.owst.jp | 店舗情報・メニュー |
| Google Reviews | https://g.page/r/CRwA4EfsMmAkEAE/review | 口コミ投稿リンク |
| Instagram | https://www.instagram.com/yakinikuhorumonjuuban | SNS |
| X | https://x.com/@yakinikujuban | SNS |
| TikTok | https://www.tiktok.com/@yakinikuhorumon10ban | SNS |

## Key Paths
| パス | 内容 |
|------|------|
| sns-links/index.html | SNSリンク集ページ（リッチメニューから遷移） |
| assets/rich-menu.jpeg | リッチメニュー背景画像 |
| docs/line-setup-guide.md | LINE OAセットアップ手順書 |
| 焼肉ホルモン十番Line.pdf | 元デザイン案PDF（別系列店の参考例含む） |

## Configuration
- LINE公式アカウント: コミュニケーションプラン（無料）
- ショップカード: 5スタンプ → 1,000円引き / 有効期限1年
- リッチメニュー: 大（上段2分割 + 下段3分割）
- クーポン: 月替わり

## Current State
- 最終更新: 2026-03-24
- Phase 1 成果物作成完了（SNSページ、リッチメニュー画像、手順書）
- LINE公式アカウント: 未作成（ユーザー作業待ち）
- SNSページ: 未デプロイ（ホスティング先未決定）
