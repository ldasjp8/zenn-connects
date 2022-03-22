---
title: "【Google Colab】はてなブログのAtomPub APIを用いた記事一覧の取得"
emoji: "💬"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["はてなブログ", "googlecolab", "Python"]
published: true
---

はてなブログの AtomPub API を用いた記事一覧の取得用サンプルプログラムを作成しました。以下の Google Colab でお試しいただけます。

https://colab.research.google.com/drive/15z0Iime9Bbma7HW09__Fq_fRkcWP6nyS?usp=sharing

上記のプログラム実行後、以下に示すような Excel ファイルがダウンロードされます。

https://docs.google.com/spreadsheets/d/14myDqZTxocwOT0Mw3ZzKLO81E6r15R-49oUh2dG9Rbo/edit?usp=sharing

「metadata」シートにブログの情報、「items」シートに記事の一覧が格納されます。

他のアプリケーションとの接続のため、「metadata」シートの A 列や見出し行、「items」シートの見出し行の表記などでわかりにくい点がありますが、はてなブログの AtomPub API の利用にあたり、参考になりましたら幸いです。
