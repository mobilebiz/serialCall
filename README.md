# serialCall

## 概要

- Twilio Functionsを使った連続架電スクリプトです。
- callListの中に架電したい電話番号をE.164形式で列記します。リストの上限はありません。
- callFromには、購入したTwilioの番号を指定してください。
- AMDは、留守番電話を検知するときにtrueにします。ただし、現在この機能は日本では正式にサポートされてはいません。また、AMDをtrueにすると、１コールにつき、1.125円が課金されます。
- domainには、Twilio Functionsで割り当てられたドメインを指定します。

## サポート

- 本スクリプトはサンプルです。実行にあたり発生するリスクについては、当社では一切責任を追いませんので、あくまでもお客様自身の責任においてご利用ください。

## 導入手順

以下の記事を御覧ください。
http://qiita.com/mobilebiz/items/caf5a4d1889da4cc8dfd
