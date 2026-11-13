# Release Now Connector

This repository is the distribution point for **Release Now Connector**, a WordPress plugin that connects a WordPress site to the Release Now news publishing app. It holds release files only: the plugin ZIP and `update.json` are attached to each entry under [Releases](../../releases). The source code is not hosted here.

## Install

1. Download `release-now-connector.zip` from the [latest release](../../releases/latest).
2. In the WordPress admin, open **Plugins → Add New Plugin → Upload Plugin**, choose the ZIP, then install and activate it.
3. Follow the `README.md` inside the plugin to connect the app.

## Updates

From version 1.3.0 on, the plugin checks this repository for new releases through the standard WordPress update screen. Updates appear in the plugin list, and automatic updates can be enabled there. The downloaded ZIP is verified against the SHA-256 value in `update.json`; if it does not match, the update is cancelled and the installed version stays in place.

Sites running 1.2.0 or earlier need one manual upload of a 1.3.0 or later ZIP first.

---

# Release Now Connector（日本語）

このリポジトリは、WordPress サイトをニュース投稿アプリ Release Now へ接続するプラグイン **Release Now Connector** の配布物置き場です。置いているのはリリースファイルだけで、プラグインの ZIP と `update.json` を [Releases](../../releases) の各版に添付しています。ソースコードはここにはありません。

## 導入手順

1. [最新のリリース](../../releases/latest) から `release-now-connector.zip` をダウンロードします。
2. WordPress 管理画面の **プラグイン → 新規プラグインを追加 → プラグインのアップロード** で ZIP を選び、インストールして有効化します。
3. プラグインに同梱の `README.md` に沿って、アプリと接続します。

## 更新

1.3.0 以降は、WordPress 標準の更新画面を通じてこのリポジトリの新しいリリースを確認します。プラグイン一覧に更新通知が表示され、自動更新も有効にできます。ダウンロードした ZIP は `update.json` の SHA-256 と照合され、一致しない場合は更新を中止し、導入済みの版がそのまま残ります。

1.2.0 以前を使っているサイトでは、最初の1回だけ 1.3.0 以降の ZIP を手動でアップロードしてください。
