---
# スライドのタイトル、ファイルの情報として記録されます。
title: スライドのタイトル
# ファイルの情報として記録されます。
description: スライド
# テーマ設定 default gaia uncover
theme: "template"
# ページ番号を表示する
paginate: True
# ヘッダー文字列
header: "abc"
# フッター文字列
footer: "conf"
# サイズ指定
size: "16:9"
# marpの使用
marp: true
    
---
<!-- _class: titlepage -->
<!-- _header: 「社内資料」とか「社外秘」とかそういうやつ -->
<!-- _paginate: False -->
# スライドのタイトルを # で入力しています

`書いた人：@tel-bitstar`

--- 
<!-- _class: toc -->
<!-- _footer: "個人で使用するなら設定の toc:level を変更して目次の対象となるレベルを固定してしまったほうが楽かもしれません。" -->
## 目次<!-- omit in toc -->
- [スライドのタイトルを # で入力しています](#スライドのタイトルを--で入力しています)
  - [はじめに](#はじめに)
  - [Markdownによる特殊記載](#markdownによる特殊記載)
  - [リスト](#リスト)
  - [テーブル](#テーブル)
  - [画像](#画像)
  - [画像(背景)](#画像背景)
  - [画像(背景として右半分に貼り付け)](#画像背景として右半分に貼り付け)
  - [画像(左側に 20% のサイズ指定)](#画像左側に-20-のサイズ指定)
  - [穴埋めページ](#穴埋めページ)

 このページは Markdown All in One の 機能で作っています。

---
## はじめに
### この部分はh3です<!-- omit in toc -->
必要なことは[マニュアル](https://marpit.marp.app/)を参照したほうが早いと思います。

また、[Marp for VS Code プラグイン](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)で作成することを想定しています。

---
## Markdownによる特殊記載

_Markdown_ の __記法__ により *斜体* や **太字** ~~打ち消し~~ などが書けます。

> blockquote
> 引用も書くことができます。

---
## リスト

- 1つめ
- 2つめ
1. 1つめ
2. 2つめ

<span style="color: blue">abc</span>
<div class="textbox">ここにテキストを記入</div>

---
## テーブル

テーブルも表示できます。

|left|center|right|
|:-|:-:|-:|
|odd |200,000|300,000|
|even|123,456|2,000|
|odd |999,999|-50,000|

---
## 画像
通常通り指定可能。
<style scoped>
  table {
    /* table-layout: fixed; */
    bottom: 150px;
    width: 1000px;
    display:table;
    font-size: 8pt;
  }
  thead th {
    background: white;
    border: none;
  }
  tbody td, tr {
    border: none;
  }
  tbody tr:nth-child(n) {
    background: #fff;
  }
</style>
||
|:-:|
|![w:200](logo.png)<td width="70%">![w:50](logo.png)</td>|
|hidarigawa<td width="70%">migigawaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</td>|

---
## 画像(背景)
<!-- _class: bgpage -->
<!-- _color: #f00 -->
![bg](logo.png)

背景画像を設定した例。
読みにくいのでPタグに背景色をつけています。

---
## 画像(背景として右半分に貼り付け)
<!-- _footer: "全画面ではない背景指定をした場合には長いフッターは折り返して表示される。" -->
![bg right](logo.png)

長い本文があった場合は折り返して表示される。

---
## 画像(左側に 20% のサイズ指定)

![bg left:20%](logo.png)

毎回左側に画像を入れるのであれば、スタイルシートで指定したほうがいいと思う。

---
## 穴埋めページ

このページは特別なことは書いていませんが、ページの数を増やしてキリを良くするために書いています。
そういえば、コードブロックの表示も問題なく反映されますが ```Qiitaに載せるときにエスケープとか面倒なので``` 今回は使っていません。

---
<!-- _class: lastpage -->
<!-- _footer: "　" -->
<!-- _paginate: false -->
## 最終ページ<!-- omit in toc -->

ITで、こまったを、よかったに。


