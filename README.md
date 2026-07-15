# Atlantis Editor 2026

「アトランチスの謎」のROMファイル解析・改造を扱いやすくするための、Windows向け非公式ツールです。

最新版はVer.0.6.0（2026/07/15公開）です。

## ダウンロード

**[最新版をダウンロード](https://github.com/fondjp/AtlantisEditor2026/releases/latest)**

配布ZIPはReleaseページのAssetsにあります。GitHubが自動表示する「Source code」はアプリ本体ではありません。
`AtlantisEditor2026_Ver.x.x.x_Windows.zip`を選んでください。ROMファイルは含まれていません。

## 対応環境

- Windows 10 / 11
- Windows 7 / 8 / 8.1は動作保証外です。

## 使い方

1. Release AssetsからZIPをダウンロードして展開します。
2. `AtlantisEditor2026.exe`を起動します。
3. ご自身で用意したROMファイルを開きます。
4. 編集前に元ROMを必ずバックアップしてください。

## 主な機能

- Zone表示と表示範囲の切り替え
- 地形、扉、宝箱／アイテム、敵、特殊処理の確認と対応項目の編集
- 描画パターン、BGM、ステージ特性、敵リスト、オプションの確認と対応項目の編集
- 編集モードとUndo／Redo
- ROM差分表示
- 敵リスト、扉No.、宝箱／アイテムNo.、未使用パターンの整理・最適化
- タイトルデモで使用する扉の設定

## 未実装・制限

- カラーパレット編集
- 「Atlantis Reformer」にあるタイル編集
- IPSパッチ出力
- FINAL特殊演出の完全再現・完全編集
- NES 2.0は対象外

## 更新方法

新しいバージョンは上書きせず、別の新しいフォルダへ展開してください。Ver.0.6.0以降は表示枚数やウィンドウ配置などのUI設定を自動的に引き継ぎます。動作確認後は古いバージョンのフォルダを削除できます。

## 不具合報告

Xの`@fondjp`まで、スクリーンショット、操作手順、状況説明を添えてお知らせください。`latest_error_report.txt`がある場合は添付してください。ROM、セーブデータ、パッチファイルは送らないでください。

## 開発について

ChatGPT・Codexとの共同開発です。開発ソースはこの公開用リポジトリには含まれません。

## 謝辞・参考

- [Atlantis Editor 2008](https://web.archive.org/web/20221220174705/https://geolog.mydns.jp/heartland.geocities.jp/frescohunter/Atlantis/Atlantis.html)
- [Atlantis Reformer (アトランチスの匠) Ver1.11](https://web.archive.org/web/20181003185821/http://island.geocities.jp/bug_9pazo/index.html)

## 非公式表記

本ツールは非公式の個人制作ツールです。権利者各位とは関係ありません。
