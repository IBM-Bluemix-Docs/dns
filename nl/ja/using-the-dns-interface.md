---
copyright:
  years: 1994, 2017
lastupdated: "2017-11-29"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# DNS インターフェースの使用法

IBM Cloud カスタマー・ポータルで DNS インターフェースを使用するには、以下の手順に従ってください。

* [カスタマー・ポータル ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://control.softlayer.com/) にナビゲートします。
* **「ネットワーク」->「DNS」->「前方ゾーン (Forward Zones)」**を選択します。
* 管理するドメインを選択するか、またはページの右側にある**「DNS ゾーンの追加 (Add DNS Zone)」**ボタンを選択します。

## DNS インターフェースの概説
カスタマー・ポータルにある DNS インターフェースを操作することによって、ご使用の DNS におけるすべての側面を管理するためのすべての機能が得られます。インターフェースのどの画面でも、その画面の静的メニュー・バーによって、すべてのタイプの DNS 管理を実行できます。

## DNS の管理
ポータルにある DNS インターフェースに到達すると、すぐに**「DNS の管理 (Manage DNS)」**画面が表示されます。この画面では、ご使用のアカウントに関連付けられている既存の 1 次 DNS を表示、編集、または削除できます。

* 新規レコードを追加するには、**「新規レコードの追加 (Add New Record)」** の下にあるフィールドに入力し、**「レコードの追加 (Add Record)」**ボタンをクリックのみです。
* 既存のレコードを変更するには、そのレコードが入っている行をクリックしてください。そのレコードは**編集**モードに変わります。設定を目的の値に変更して、**「更新」**をクリックします。
* レコードを削除するには、そのレコードの右側にある赤い円を選択し、プロンプトに対して**「はい (Yes)」**をクリックします。

## 2 次 DNS

* [カスタマー・ポータル ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://control.softlayer.com/) にナビゲートします。
* **「ネットワーク」->「DNS」->「2 次ゾーン (Secondary Zones)」**を選択します。

この画面で、2 次 DNS 設定を追加または変更できます。

* 新規レコードを追加するには、**「ゾーンの追加 (Add Zone)」**を選択し、フィールドに入力して**「追加」**を選択します。
* 2 次 DNS レコードを削除するか、または 1 次レコードに変換するには、ページの右上にある**「アクション」**ドロップダウンから該当するオプションを選択します。

## リバース DNS

ポータル・ナビゲーションで DNS インターフェースを使用するには、以下の手順に従ってください。

* [カスタマー・ポータル ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://control.softlayer.com/) にナビゲートします。
* **「ネットワーク」->DNS->「レコードの逆引き (Reverse Records)」**を選択します。
* ドロップダウン・メニューで、リバース DNS を変更する対象の IP アドレスを選択または入力して、**「IP の表示 (View IP)**を選択します。
  * レコードを追加するには、リバース DNS エントリーに使用するホスト名を入力します。
  * そのレコードの TTL (存続時間) を設定します。
  * 情報を確認したら、**「保存」**を選択します。

ページの右側にある**「このサブネット内のすべての IP の RDNS を編集 (Edit RDNS for all IPs in this Subnet)」**をクリックすると、サブネット全体を編集できます。

* このページで、更新する IP の行を選択します。
* 情報をフィールドに入力してから、**「更新」**を選択します。「メモ」フィールドはオプションです。

## 伝搬の確認

* [カスタマー・ポータル ![外部リンク・アイコン](../../icons/launch-glyph.svg "外部リンク・アイコン")](https://control.softlayer.com/) にナビゲートします。
* **「ネットワーク」->「ツール (Tools)」**を選択します。

ロードされたページで、複数のツールから選択することができます。DNS サーバーによるドメイン・ネームの伝搬を確認するには、下部のオプションを使用してください。

* 該当する情報をフィールドに入力してから、**「DNS の確認 (Check DNS)」**を選択します。
* しばらくすると、右側にあるボックスが、ドメインの現在の DNS 情報で更新されます。