# sci-bone-day-2026

# sci-bone day 2026

**sci-bone day 2026** のイベントLP（ランディングページ）です。

🔗 **公開URL**: https://sci-bone.github.io/sci-bone-day-2026/

## イベント概要

- **日時**: 2026年3月11日（水） 14:00 - 16:00 JST
- **会場**: 赤羽イノベーションサイト ＋ オンライン配信
- **参加登録**: https://sci-bone-day-2026.peatix.com/

## 技術スタック

- HTML / CSS（単一ファイル構成）
- [Tailwind CSS](https://tailwindcss.com/)（CDN）
- [Google Fonts](https://fonts.google.com/)（Inter）
- GitHub Pages（ホスティング）

## ディレクトリ構成

```
sci-bone-day-2026/
├── index.html              # メインページ
├── assets/
│   ├── images/
│   │   ├── sci-bone_day_2026_logo.png
│   │   ├── logo_only.png
│   │   ├── dash-ai.png
│   │   ├── miyazawa.png
│   │   └── akiyoshi.png
│   └── movie/
│       ├── trailer_scibone_day_run.mp4
│       ├── trailer_scibone_day_football.mp4
│       └── trailer_scibone_day_basketball.mp4
└── README.md
```

## ローカルでの開発

### 1. クローン

```bash
git clone https://github.com/sci-bone/sci-bone-day-2026.git
cd sci-bone-day-2026
```

### 2. ローカルサーバーを起動

```bash
# Python
python3 -m http.server 8000

# または Node.js
npx serve .
```

### 3. ブラウザで確認

```
http://localhost:8000
```

## デプロイ（本番反映）

GitHub Pages を使用しているため、`main` ブランチに push するだけで自動デプロイされます。

```bash
git add .
git commit -m "変更内容のメモ"
git push origin main
```

push 後 1〜2 分で https://sci-bone.github.io/sci-bone-day-2026/ に反映されます。

## ページ構成

| セクション | 内容 |
|---|---|
| Hero | イベントロゴ・日時・参加登録ボタン |
| The Mission | sci-bone のビジョン |
| Technology | DashAI / Basketball Analysis のデモ紹介 |
| Event Teasers | ティザー動画（Running / Football / Basketball） |
| Speakers | 登壇者紹介（4名） |
| Booth | ブース出店情報（4ブース） |
| Footer | コーポレートサイトへのリンク |

## ライセンス

© 2026 sci-bone corporation. All rights reserved.