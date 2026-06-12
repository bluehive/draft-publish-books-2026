# Draft Publish Books 2026

**2026年9月11日** Kindle出版を目標とした、書籍目次ドラフト集です。  
Google Drive の PDF・メモを参照しながら、Grok Build で本文執筆へ進める前提の「設計図」リポジトリです。

本番原稿は [`bluehive/mypublish-books`](https://github.com/bluehive/mypublish-books) で管理し、本リポジトリは**企画・目次・章構成**に特化します。

---

## 書籍一覧（8冊）

| ファイル | 書名 | ジャンル | 目次 | Drive参照 |
|----------|------|----------|------|-----------|
| [japanism-outsiders.md](japanism-outsiders.md) | 日本主義のアウトサイダー達 | 思想・文化史 | ✅ 拡充済 | 文化防衛論PDF |
| [eugenics-history.md](eugenics-history.md) | 優生思想の歴史 | 近現代史 | ✅ 拡充済 | 優生・人種改良PDF |
| [kindle-publishing-guide.md](kindle-publishing-guide.md) | 電子書籍の作り方 | 実用・出版 | ✅ 拡充済 | — |
| [jin-eight-kings-chaos.md](jin-eight-kings-chaos.md) | 晋・八王の乱と混沌 | 中国史 | ✅ 新規 | — |
| [seven-sages-bamboo-grove.md](seven-sages-bamboo-grove.md) | 竹林七賢 | 中国思想・文化史 | ✅ 新規 | — |
| [trigonometry-problem-book.md](trigonometry-problem-book.md) | 三角法問題集 | 数学・問題集 | ✅ 新規 | — |
| [racket-game-of-life.md](racket-game-of-life.md) | Racketで学ぶ生命のゲーム | プログラミング | ✅ 新規 | — |

---

## 各ファイルの書き方

各 `*.md` は次の構成を共通とします。

1. **メタ情報**（副題・出版目標・参照Drive・関連リポジトリ）
2. **目次ドラフト**（章・節レベルまで）
3. **付録案**
4. **執筆ステータス表**

目次が固まったら、Grok に「`japanism-outsiders.md` の第2章を執筆」と指示し、成果物を `mypublish-books/manuscript/` へ移します。

---

## ワークフロー

```
draft-publish-books-2026（目次・企画）
        ↓ Grok 執筆
mypublish-books（原稿・用語集・レビュー）
        ↓ Pandoc / Calibre
KDP アップロード（9/11目標）
```

詳細は [kindle-publishing-guide.md](kindle-publishing-guide.md) を参照。

---

## 関連リポジトリ

- https://github.com/bluehive/mypublish-books — 原稿管理
- https://github.com/bluehive/draft-publish-books-2026 — 本リポジトリ

---

## 次のタスク（優先）

1. `eugenics-history.md` 付録B — Drive PDF ファイル名のインデックス化
2. `japanism-outsiders.md` 第2章 — 文化防衛論PDFからの引用整理
3. `racket-game-of-life.md` — `my-racket/` のコードを章ごとに分割

---

*最終更新: 2026-06-12*