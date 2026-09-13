---
title: "COLUMN Filer プライバシーポリシー / Privacy Policy"
permalink: /privacy/
---

<p style="font-size:0.9em"><a href="{{ '/' | relative_url }}">サポート / Support</a> · <a href="{{ '/privacy/' | relative_url }}">プライバシー / Privacy</a> · <a href="{{ '/terms/' | relative_url }}">使用許諾 / Terms</a></p>

# COLUMN Filer プライバシーポリシー

最終更新日: 2026-09-09

（English version follows below / 英語版は下部にあります）

## 要点

COLUMN Filer は、利用者の個人情報・利用状況・ファイルの内容やファイル名を **一切収集・送信しません**。開発者（Masaru Kinashi）や第三者が利用者のデータを受け取ることはありません。アプリの動作に必要なデータ（下記「アプリが扱う情報と、その保存場所」）は利用者の Mac 内にだけ保存し、その内容が外部へ送られることはありません。

- 解析・トラッキング・広告の仕組みを **一切含みません**。
- 利用者アカウントの作成や、ログインは **ありません**。
- ファイル、フォルダ、ファイル名、メタデータを開発者や外部サーバーへ送信することは **ありません**。
- クラッシュレポートや使用統計を自動送信することは **ありません**。
- 利用者が明示的に指示した場合のファイル転送（AirDrop での送信、他アプリへのドラッグ書き出し、macOS 標準の「サーバへ接続」で開いたネットワーク共有への移動・コピー）は、利用者の操作としてそのとおり実行します。これは利用者自身によるファイル操作であり、COLUMN Filer が利用者のデータをどこかへ送るものではありません。

## アプリが扱う情報と、その保存場所

COLUMN Filer は 2 ペイン型のファイルブラウザです。利用者が選んだフォルダやファイルにアクセスして表示・整理する必要がありますが、その情報は利用者の Mac の外に出ることはありません。

| 種類 | 用途 | 保存場所 |
| --- | --- | --- |
| アクセスを許可したフォルダの記録（セキュリティスコープ付きブックマーク） | 一度許可した場所を次回以降も開けるようにするため | 利用者の Mac のアプリ専用領域（App Sandbox コンテナ内）。macOS の標準的な仕組みを利用します。 |
| 環境設定（表示モード、列幅、テーマ色、よく使う項目、色ラベル、検索履歴、監視フォルダの一覧など） | アプリの動作を利用者の好みに合わせるため | 同 Mac の `UserDefaults`（アプリ専用領域） |
| フォルダ容量の集計結果 | 「情報を見る」等での表示のため（セッション中のみ、再起動で消えます） | メモリ上のみ |

これらはいずれも利用者本人のためのローカルなデータであり、開発者や第三者に共有されることはありません。アプリを削除すると、これらのローカルデータも削除されます。

## ネットワークアクセスについて

COLUMN Filer には「ネットワーククライアント」の権限（`com.apple.security.network.client`）が付与されていますが、これは次の目的にのみ使用します。

- **同一ローカルネットワーク上のファイル共有サーバーの探索（Bonjour）**: サイドバーの「共有」欄に、近くの SMB / AFP サーバーの名前を一覧表示するため。
- **「サーバへ接続」の呼び出し**: 利用者がサーバーに接続したいとき、macOS 標準の「サーバへ接続」機能に処理を引き継ぐため。

いずれの場合も、COLUMN Filer 自身がインターネットへ通信したり、利用者のファイル・認証情報・利用状況を送信したりすることはありません。SMB / AFP の認証情報の入力・保存は macOS が行い、アプリは扱いません。

## 購入（App 内課金）について

COLUMN Filer は「無料ダウンロード＋30日間の試用＋買い切りのフルアンロック」というモデルで提供されます。購入・試用の処理はすべて Apple の App Store（StoreKit）が行います。

- 支払い情報（クレジットカード番号など）は Apple が処理し、開発者がこれを受け取ることはありません。
- 購入状況の判定は、Apple から端末に提供される購入情報（App Store のトランザクション）をアプリがその場で確認する方式です。独自のサーバーやレシート検証、独自の製品キーは使用しません。
- App Store での購入・返金・サブスクリプション（本アプリにサブスクリプションはありません）に関する情報の取り扱いは、Apple のプライバシーポリシーに従います。

## Apple の「Required Reason API」について

Apple のガイドラインに従い、COLUMN Filer が使用する以下の API とその理由を申告しています。いずれも取得した情報を端末外へ送信しません。

- **UserDefaults（理由コード CA92.1）**: アプリ自身の環境設定を読み書きするため。
- **ファイルのタイムスタンプ（理由コード DDA9.1）**: ファイルブラウザとして、ファイルの更新日時・作成日時を画面に表示し、並べ替えや期間での絞り込みに使うため。
- **ディスクの空き容量（理由コード 85F4.1）**: 画面のフッターに、現在のフォルダが属するボリュームの空き容量を表示するため。

## お問い合わせ

本ポリシーに関するご質問は、以下までご連絡ください。

- 開発者: Masaru Kinashi
- 連絡先: {{ site.email }}

## 変更について

本ポリシーを変更する場合は、このページを更新し、「最終更新日」を改めます。重要な変更がある場合はアプリのアップデート情報でもお知らせします。

---

# COLUMN Filer Privacy Policy

Last updated: 2026-09-09

## Summary

COLUMN Filer does **not** collect or transmit any personal information, usage data, file contents, or file names. Neither the developer (Masaru Kinashi) nor any third party ever receives your data. Data the app needs to function (see "What information the app handles, and where it is stored" below) is stored only on your Mac and its contents are never sent anywhere.

- No analytics, tracking, or advertising of any kind.
- No user accounts and no sign-in.
- Files, folders, file names, and metadata are never sent to the developer or to any external server.
- No automatic crash reports or usage statistics.
- File transfers that you explicitly initiate (sending via AirDrop, dragging out to another app, moving or copying to a network share you opened with the standard macOS "Connect to Server") are carried out exactly as you direct. That is your own file operation; it is not COLUMN Filer sending your data anywhere.

## What information the app handles, and where it is stored

COLUMN Filer is a dual-pane file browser. It needs to access the folders and files you choose in order to display and organize them, but that information never leaves your Mac.

| Type | Purpose | Where it is stored |
| --- | --- | --- |
| A record of folders you have authorized (security-scoped bookmarks) | So that a location you allow once stays accessible next time | In your Mac's app-private area (inside the App Sandbox container), using the standard macOS mechanism |
| Preferences (view mode, column widths, theme color, favorites, color labels, search history, list of watched folders, etc.) | To match the app's behavior to your preferences | In `UserDefaults` on the same Mac (app-private area) |
| Folder size calculation results | To show sizes in "Get Info" and similar (only during the current session; cleared on restart) | In memory only |

All of this is local data that exists for your benefit. It is never shared with the developer or any third party. Deleting the app also deletes this local data.

## Network access

COLUMN Filer holds the "network client" entitlement (`com.apple.security.network.client`), which is used **only** for:

- **Discovering file-sharing servers on your local network (Bonjour)**, so the sidebar's "Shared" section can list nearby SMB / AFP servers by name.
- **Invoking "Connect to Server"**, handing off to the standard macOS "Connect to Server" function when you want to connect to a server.

In neither case does COLUMN Filer itself communicate with the internet or send your files, credentials, or usage data anywhere. Entering and storing SMB / AFP credentials is handled by macOS, not by the app.

## Purchases (In-App Purchases)

COLUMN Filer is offered as a free download with a 30-day trial and a one-time "Full Unlock" purchase. All purchase and trial processing is performed by Apple's App Store (StoreKit).

- Payment information (such as credit card numbers) is processed by Apple; the developer never receives it.
- Entitlement is determined by the app checking the purchase information (App Store transactions) that Apple provides to your device, on the spot. There is no custom server, no custom receipt validation, and no custom license key.
- The handling of purchase, refund, and subscription information on the App Store (this app has no subscriptions) is governed by Apple's privacy policy.

## Apple "Required Reason API" declarations

In accordance with Apple's guidelines, COLUMN Filer declares the following APIs and the reasons for their use. None of the information obtained is sent off the device.

- **UserDefaults (reason code CA92.1)**: to read and write the app's own preferences.
- **File timestamps (reason code DDA9.1)**: as a file browser, to display file modification and creation dates and to use them for sorting and date-range filtering.
- **Disk space (reason code 85F4.1)**: to show the available space of the volume the current folder is on, in the window footer.

## Contact

For questions about this policy, please contact:

- Developer: Masaru Kinashi
- Contact: {{ site.email }}

## Changes

If this policy changes, this page will be updated and the "Last updated" date revised. Significant changes will also be noted in the app's release notes.
