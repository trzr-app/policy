---
layout: default
title: TRZR Privacy Policy
---

# TRZR Privacy Policy / プライバシーポリシー

**Effective Date / 施行日**: 2026-05-20
**App**: TRZR (Bundle ID: `app.trzr`)
**Developer**: Soya Matsumura
**Contact**: trzr.app@gmail.com

[English](#english) · [日本語](#日本語)

---

## English

### What we collect

TRZR is a personal diary app. **All your data — posts, location, tags, themes, link previews — is stored in your own iCloud account using Apple's CloudKit private database.** We do not run any servers, and we do not collect, store, or transmit your content to any third party.

### How your data is used

- **Posts and metadata** (text, tags, themes, location, link previews) sync between your own devices via Apple iCloud.
- **Reminder notifications** are scheduled locally on your device using Apple's standard notification system.
- **Location data** (optional, opt-in) is read only when you explicitly tap the location button. We do not track your location in the background.
- Photo attachment is **planned for v1.1** (iCloud sync via CKAsset).

### Third-party services

TRZR uses the following services:

- **iCloud / CloudKit** (Apple): stores your posts in your private iCloud database. Subject to [Apple's iCloud Privacy Policy](https://www.apple.com/legal/privacy/data/en/icloud/).
- **LinkPresentation framework** (Apple): when you paste a URL, TRZR fetches the link's title and image preview using Apple's framework. The fetch goes directly from your device to the linked website.
- **MapKit / CoreLocation** (Apple): when you tap the location button, your location is queried by your device.
- **TelemetryDeck** (Switzerland): anonymous app usage signals are sent to help us understand which features are used. Only abstract events like "post created" or "settings opened" are sent — never your post body, photos, tags, theme names, location coordinates, or any identifier. We do not use IDFA, and no AppTrackingTransparency prompt is needed. See [TelemetryDeck's privacy policy](https://telemetrydeck.com/privacy/).

We use **anonymous, aggregate-only TelemetryDeck signals**. No advertising SDKs, no tracking, no IDFA.

### Data deletion

- **Soft delete (trash)**: deleted posts move to the trash, retained for 30 days.
- **Permanent delete**: trash is automatically swept after 30 days.
- **All data**: to delete all TRZR data, open iOS Settings → Apple ID → iCloud → Manage Storage → TRZR, and delete.

### Children

TRZR is not directed at children under 13. The app rating is 4+.

### Changes to this policy

We may update this policy. The effective date will be revised at the top.

### Contact

For questions, please contact: trzr.app@gmail.com

---

## 日本語

### 収集する情報

TRZR は個人用日記アプリです。**投稿・位置情報・タグ・テーマ・リンクプレビューといったあなたのデータはすべて、Apple の CloudKit プライベートデータベース経由で、あなた自身の iCloud アカウントに保存されます。** 開発者側はサーバーを運営しておらず、あなたのコンテンツを収集・保存・第三者に送信することは一切ありません。

### データの利用方法

- **投稿とメタデータ**（本文、タグ、テーマ、位置情報、リンクプレビュー）は、Apple iCloud 経由であなた自身のデバイス間で同期されます。
- **リマインダー通知**は端末ローカルで Apple の通知システムによりスケジュールされます。
- **位置情報**（オプション、明示的に許可した場合のみ）は、ユーザーが位置情報ボタンをタップしたときのみ読み取られます。バックグラウンドで位置を追跡することはありません。
- 写真添付は **v1.1 で追加予定**（CKAsset での iCloud 同期込み）。

### 第三者サービス

TRZR は以下のサービスを利用します:

- **iCloud / CloudKit**（Apple）: 投稿を自身の iCloud プライベートデータベースに保存。[Apple iCloud プライバシーポリシー](https://www.apple.com/jp/legal/privacy/data/jp/icloud/)が適用されます。
- **LinkPresentation フレームワーク**（Apple）: URL を貼り付けた際、Apple のフレームワーク経由でリンク先のタイトル・画像を取得します。取得はあなたのデバイスからリンク先サイトへ直接行われます。
- **MapKit / CoreLocation**（Apple）: 位置情報ボタン押下時にデバイス側で位置情報を取得します。
- **TelemetryDeck**（スイス拠点）: アプリ利用状況の匿名 signal を送信し、どの機能がよく使われているかを理解する目的で利用します。送信されるのは「投稿が作成された」「設定画面が開かれた」といった抽象的なイベント名のみで、**投稿本文・写真・タグ名・テーマ名・位置情報の座標・識別子は一切含まれません**。IDFA は使用しておらず、AppTrackingTransparency のプロンプトも不要です。詳細: [TelemetryDeck プライバシーポリシー](https://telemetrydeck.com/privacy/)。

**匿名・集計のみの TelemetryDeck signal を利用しています。広告 SDK・トラッキング・IDFA は一切使用していません。**

### データの削除

- **ソフト削除（ゴミ箱）**: 削除した投稿はゴミ箱に移動し、30 日間保持されます。
- **完全削除**: 30 日経過後、自動的に物理削除されます。
- **すべてのデータ**: TRZR のデータをまとめて削除するには、iOS の設定 → Apple ID → iCloud → ストレージを管理 → TRZR から削除してください。

### 子どもについて

TRZR は 13 歳未満を対象としていません。年齢区分は 4+ です。

### このポリシーの変更

ポリシーは更新される場合があります。施行日は冒頭に記載します。

### お問い合わせ

ご質問は trzr.app@gmail.com までご連絡ください。
