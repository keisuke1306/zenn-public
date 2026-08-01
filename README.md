# zenn-public

公開用のZennリポジトリです。

https://zenn.dev/

## 目的

公開済みの記事のみを管理します。

このリポジトリは公開用のため、執筆・下書きは行いません。

## 正本

記事の正本は

```
zenn-private
```

です。

修正が必要な場合も、まず `zenn-private` を更新し、その後こちらへ反映してください。

## ディレクトリ構成

```text
articles/
books/
images/
```

## 公開フロー

```text
zenn-private
      ↓
完成
      ↓
コピー
      ↓
git push
      ↓
Zenn公開
```

## 運用ルール

- このリポジトリでは直接執筆しない
- 公開済み記事のみ配置する
- 履歴は公開されることを前提とする
