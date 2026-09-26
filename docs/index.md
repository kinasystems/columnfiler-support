---
title: "COLUMN Filer サポート / Support"
---

<p style="font-size:0.9em"><a href="{{ '/' | relative_url }}">サポート / Support</a> · <a href="{{ '/privacy/' | relative_url }}">プライバシー / Privacy</a> · <a href="{{ '/terms/' | relative_url }}">使用許諾 / Terms</a></p>

# COLUMN Filer サポート

（English version follows below / 英語版は下部にあります）

**COLUMN Filer** は、Mac 用のシンプルな 2 ペイン型ファイルブラウザです。現在地と操作対象が分かりやすく、ファイルを誤って失いにくいことを重視して作られています。

## 動作環境

- macOS 26 以降
- Apple Silicon 搭載の Mac

## お問い合わせ

不具合の報告、ご要望、ご質問は以下までお寄せください。返信までお時間をいただく場合があります。

- 連絡先: {{ site.email }}

不具合を報告いただく際は、次の情報があると調査が早くなります。

- お使いの macOS のバージョンと Mac の機種
- 操作の手順（何をしたら、何が起きたか）
- 対象がローカルディスク・外部ドライブ・ネットワーク（NAS）のいずれか

## よくある質問

### 初めて開くフォルダで「アクセスを許可しますか」というダイアログが出ます

COLUMN Filer は macOS の App Sandbox の中で動作します。まだアクセスを許可していない場所（初めて開く外付けドライブ、NAS の共有、ホームフォルダの外にあるフォルダなど）を最初に開くとき、macOS 標準の許可ダイアログが 1 回だけ表示されます。一度許可した場所は、その中のフォルダも含めて、次回以降は確認なしで開けます。これはセキュリティのための macOS の仕組みで、アプリが回避することはできません。

### 30日間の試用はどうやって始めますか

アプリメニュー「COLUMN Filer」→「COLUMN Filer を購入…」から試用を開始できます。初回起動時にも案内が表示されます。試用中は、ファイルへの書き込みを含むすべての機能を利用できます。

### 試用期間が終わるとどうなりますか

閲覧・検索・Quick Look・AirDrop 送信・他アプリへの書き出しは引き続き無料で利用できます。コピー・移動・名前の変更・削除・圧縮・解凍などファイルを変更する操作を続けるには、「フルアンロック」の購入が必要です。

### 別の Mac で購入を引き継ぎたい

同じ Apple ID でサインインした状態で、アプリメニューの購入画面から「購入を復元」を選んでください。

### 表示言語を変えたい

COLUMN Filer は通常、macOS の言語設定に従います。アプリだけ別の言語で使いたいときは、環境設定（「COLUMN Filer」→「設定…」または ⌘,）の「言語」タブで「システムに合わせる」または特定の言語を選べます。変更は次回 COLUMN Filer を起動したときに反映されます。

### 一覧表示でフォルダのサイズが「—」と表示されます

一覧表示では、フォルダの中身を再帰的に集計する処理は行いません（大きなフォルダで表示が遅くなるのを避けるため）。フォルダのサイズを知りたいときは、そのフォルダを右クリックして「情報を見る」を選ぶと、その場で集計して表示します。

### NAS 上の項目で「ゴミ箱に入れる」が選べません

ネットワークボリューム（NAS など）では、復元可能なゴミ箱が保証されないため、「ゴミ箱に入れる」を無効にしています。必要な場合は「完全に削除…」（不可逆の確認あり）をご利用ください。

### スキャンしたファイルが保存されたときに COLUMN Filer で開きたい

環境設定（「COLUMN Filer」→「設定…」または ⌘,）の「一般」タブにある「監視フォルダ」で、監視したいフォルダ（スキャンの保存先など）を追加できます。そのフォルダに新しいファイルが増えると、COLUMN Filer が通知したり、そのフォルダを開いたりします（動作は選べます）。この機能は COLUMN Filer が起動している間に動作します。

## プライバシー

COLUMN Filer は、利用者の情報・ファイル・利用状況を一切収集・送信しません。詳しくは[プライバシーポリシー]({{ '/privacy/' | relative_url }})をご覧ください。

## 使用許諾・免責事項

[使用許諾・免責事項]({{ '/terms/' | relative_url }})をご覧ください。

---

# COLUMN Filer Support

**COLUMN Filer** is a simple dual-pane file browser for the Mac. It is built to make your current location and the target of an operation clear, and to make it hard to lose files by mistake.

## Requirements

- macOS 26 or later
- A Mac with Apple silicon

## Contact

Please send bug reports, requests, and questions to the address below. A reply may take some time.

- Contact: {{ site.email }}

When reporting a bug, the following information helps speed up investigation:

- Your macOS version and Mac model
- The steps to reproduce (what you did, and what happened)
- Whether the target is on a local disk, an external drive, or a network share (NAS)

## Frequently Asked Questions

### A dialog asks whether to allow access when I open a folder for the first time

COLUMN Filer runs inside the macOS App Sandbox. The first time you open a location it has not been granted access to (an external drive you are opening for the first time, a NAS share, a folder outside your home folder, and so on), macOS shows its standard permission dialog once. A location you have allowed once — including the folders inside it — opens without asking on subsequent occasions. This is a macOS security mechanism that the app cannot bypass.

### How do I start the 30-day trial?

Choose the app menu "COLUMN Filer" → "Purchase COLUMN Filer…" to start the trial. A prompt is also shown on first launch. During the trial, all features, including writing to files, are available.

### What happens when the trial ends?

Viewing, search, Quick Look, sending via AirDrop, and dragging out to other apps remain available for free. To continue with operations that modify files — copy, move, rename, delete, compress, extract — you need the "Full Unlock" purchase.

### I want to carry my purchase over to another Mac

While signed in with the same Apple ID, choose "Restore Purchases" from the purchase screen in the app menu.

### I want to change the display language

COLUMN Filer normally follows your macOS language setting. To use the app in a different language, open Settings ("COLUMN Filer" → "Settings…", or ⌘,) → the "Language" tab and choose "Match System" or a specific language. The change takes effect the next time you launch COLUMN Filer.

### Folder sizes show as "—" in list view

In list view, the app does not recursively total the contents of a folder (to avoid slow display for large folders). To see a folder's size, right-click it and choose "Get Info"; the size is calculated on the spot and shown there.

### "Move to Trash" is unavailable for items on a NAS

On network volumes (such as a NAS), a recoverable Trash is not guaranteed, so "Move to Trash" is disabled. If you need to remove such items, use "Delete Permanently…" (with its irreversible confirmation).

### I want scanned files to open in COLUMN Filer when they are saved

In Settings ("COLUMN Filer" → "Settings…", or ⌘,) → the "General" tab → "Watched Folders," you can add a folder to watch (such as your scanner's save destination). When a new file appears in that folder, COLUMN Filer can notify you or open the folder (the behavior is configurable). This feature works while COLUMN Filer is running.

## Privacy

COLUMN Filer does not collect or transmit any of your information, files, or usage data. See the [Privacy Policy]({{ '/privacy/' | relative_url }}) for details.

## Terms & Disclaimer

See [Terms & Disclaimer]({{ '/terms/' | relative_url }}).
