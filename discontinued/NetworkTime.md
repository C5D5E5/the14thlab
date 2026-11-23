# プライバシーポリシーとサポート情報 - Network Time

![NetworkTime](https://c5d5e5.github.io/the14thlab/images/NetworkTimeU50.png)

## 本アプリについて

ネットワーク時刻を提供するサーバから時刻情報を取得し、本機の時刻とのずれを確認します。

## プライバシーポリシー

本アプリの製作者である The Fourteenth Lab (第十四工房) は、本アプリによって、お客様の個人情報およびプライバシーに関する情報を収集しません。

## サポート情報

ご質問や不具合のご連絡は、製作者のメールアドレス(C5D5E5@outlook.com) までお願いします。

## あらかじめのおことわり (FAQ)

1. 本アプリは、ネットワーク時刻を提供するサーバとの通信にUDP/IP上の通信手順（NTPプロトコル）を用いています。
この通信手順は、送達確認を行わないため、通信相手が結果を返さない場合でも、エラーは表示されません。

2. 平均通信時間は、往路と復路の通信時間の平均です。

3/ オプションで「詳細モード」を選択する場合の表示は、NTPプロトコルの仕様書が定める以下の内容に対応します。

* 時刻サーバの応答: leap
* 時刻の階層: stratum
* 時刻の同期間隔: poll
* 時刻の精度: precision
* 時刻の識別情報: reference id、stratumが0の場合は: kiss code

## 利用するツールや文献

1. RFC 5905, Network Time Protocol Version 4: Protocol and Algorithms Specification, June 2010

* * *

[第十四工房 Windows Store提供アプリのページ](https://c5d5e5.github.io/the14thlab/)