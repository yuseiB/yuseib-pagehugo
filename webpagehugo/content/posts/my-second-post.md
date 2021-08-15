---
title: "ビルドするまでの手順メモ"
date: 2021-08-15T23:42:22+09:00
draft: false
---


## 目的

* Hugo で走っているこのサイトに記事を投稿するまでの手順を整理しておく

## 環境

* Linux Mint 19.1 Tessa
* Hugo v0.87.0, extended

## 参照

* Hugo Quick Start : [https://gohugo.io/getting-started/quick-start/](https://gohugo.io/getting-started/quick-start/)
* Cloudflare Docs : [https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site](https://developers.cloudflare.com/pages/framework-guides/deploy-a-hugo-site)

## 手順

1. Cloudflare Docs の手順に従って作業ディレクトリを作る
1. Hugo Quick Start の手順に従って、ここでは `Ananke theme` を使用する
1. `hugo new posts/POSTNAME.md` を実行してファイル作成、編集、保存
1. `git commit`, `git push` などする

---

## Markdown のテスト

```math
\gamma = \frac{1}{\sqrt{1-\left(\frac{v}{c}\right)^2}}
```

追記：KaTeX 対応してない模様？

