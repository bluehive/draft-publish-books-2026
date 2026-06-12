---
name: 原稿リポへの移行準備
about: 目次が固まった書籍を mypublish-books で執筆開始するための準備
title: "[移行] "
labels: migration
assignees: ''
---

## 対象

- **書籍名**:
- **目次ドラフト**: `draft-publish-books-2026/*.md`
- **移行先リポ**: [`bluehive/mypublish-books`](https://github.com/bluehive/mypublish-books)

## 移行の前提

- [ ] 目次が章・節レベルまで確定している
- [ ] メタ情報・参照Driveが整理済み
- [ ] 執筆ステータス表で「執筆開始可」になっている

## タスク

- [ ] `mypublish-books` に manuscript / drafts / notes ディレクトリを作成
- [ ] 目次を章ドラフトの骨子として展開（`ch00`〜`ch99`）
- [ ] 用語集・データパック用の `notes/` を用意
- [ ] `mypublish-books` 側で章執筆 Issue を起票
- [ ] 本リポの執筆ステータス表を「執筆中」に更新

## Grok への指示メモ

```
例：
- japanism-outsiders.md の目次をもとに ch01〜ch04 の空ドラフトを作成
- mypublish-books の README に書籍エントリを追加
- 第1章から執筆 Issue を起票
```

## 関連リンク

- 目次ドラフト Issue:
- mypublish-books 執筆 Issue:

## 完了条件

- [ ] `mypublish-books` に初期ディレクトリ構成がある
- [ ] 章ごとの執筆 Issue が起票済み
- [ ] 両リポの README / ステータスが同期している

## メモ