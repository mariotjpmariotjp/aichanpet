# あいちゃんペット Webサイト

埼玉県入間市のペットシッター「あいちゃんペット」の新ホームページ。

## 公開ページ

- **新HP（お客様向け）**: `/`（`index.html`）
- **提案資料 見本ページ（社内確認用）**: `/proposal/`

## 構成

```
/
├── index.html          新HP（1ファイル完結・ピンク基調・簡易見積もり付き）
├── proposal/
│   ├── index.html      提案資料の見本ページ（noindex・関係者確認用）
│   └── img/            各図版（スイムレーン・マスタ・LINE導線等のPNG）
└── README.md
```

## 技術メモ

- HPは外部依存なしの単一HTML（Google Fontsのみ読込）
- GitHub Pagesでそのまま公開可能
- 本番は独自ドメイン（aichanpet1122.web.fc2.com 等）への載せ替えも可能

作成: 2026年5月 / 提案バージョン v4
