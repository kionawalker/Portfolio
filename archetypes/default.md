---
# 記事タイトルの設定
title: "{{ replace .Name "-" " " | title }}"
summary: ""
# 記事の説明
description : ""
# 作成日付の設定
date: "{{ now.Format "2006-01-02" }}"
# 更新日
lastmod: "{{ now.Format "2006-01-02" }}"
#アーカイブの設定を作成日付で設定する
# archives: [{{ dateFormat "2006/01" .Date }}]
# 下書きモード（true=下書き、false=公開）
draft: true
# タグ
tags: [""]
# サムネイルの保存場所を/static/thumbnailにする
# thumbnail: "./img/thumbnail/"
# 公開終了日付の設定(限定記事以外特に使わない)
# expiryDate: "2020-12-31"
# URLのファイル名部分を変更するパラメータ。基本使わない
# slug: "xxxxx"
# カテゴリ
categories: [""]
# 目次設定（true=表示、false=非表示）
toc: true
---

arxivへのリンク  [paper]()  
掲載した画像は全て原著論文からの引用

## **どんなもの？**


## **先行研究と比べてどこがすごい？**


## **技術や手法のキモはどこ？**


## **どうやって有効だと検証した？**


## **議論はある？**


## **次に読むべき論文は？**