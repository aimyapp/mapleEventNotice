# 【非公式】メイプルイベント通知 LINE Bot
## 概要
メイプルストーリー公式サイトから最新のイベント情報を、LINE Botを通じて定期的にお知らせします。<br>

## システム構成図
![システム構成図](https://github.com/aimyapp/mapleEventNotice/blob/main/img/system_conf.png)
- システム構成
    - メイプルストーリー公式: 皆大好きメイプルストーリーの公式サイト
    - Google Colab: "TOP>お知らせ>イベント"から最新のイベント情報を取得して、LINEに送信するためのメッセージへ整形します。
    - Messaging API: LINEのサービスを利用して、ユーザーとのメッセージングやコミュニケーションを行うためのAPIです。
    - Github Actions: Google Colabで作成した処理を定期的に実行します。

## 使い方(WIP)
