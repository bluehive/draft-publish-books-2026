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

## Google Drive PDF インデックス

全量再走査（2026-06-14）: [`notes/drive-pdf-index.md`](notes/drive-pdf-index.md)  
マウント: `~/GoogleDrive`（`rclone gdrive`）／主要フォルダ: `創作の参照ファイル/`（74 PDF）

## データパック（執筆用）

| 書籍 | 章 | ファイル |
|------|-----|---------|
| 日本主義のアウトサイダー達 | 第2章 | [`notes/japanism-outsiders/ch02-data-pack.md`](notes/japanism-outsiders/ch02-data-pack.md) |
| 優生思想の歴史 | 第1章 | [`notes/eugenics-history/ch01-data-pack.md`](notes/eugenics-history/ch01-data-pack.md) |

## 次のタスク（優先）

1. `japanism-outsiders` 第2章本文執筆（data_pack → `mypublish-books/manuscript/`）
2. `eugenics-history` 第2章 data_pack（日本への輸入）
3. `sync-gdrive-pdfs.sh` で PDF ローカルキャッシュ化
4. `racket-game-of-life.md` — `my-racket/` のコードを章ごとに分割

---

*最終更新: 2026-06-14*