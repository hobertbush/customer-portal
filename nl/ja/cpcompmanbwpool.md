---

copyright:

  years: 1994, 2018

lastupdated: "2017-12-06"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# 処理能力使用量の最適化
{: #cp_manbdwpool}

サーバーのすべての処理能力をまとめて 1 つの*処理能力プール* に「プーリング」することによって、処理能力使用を最適化できます。 処理能力プール内のサーバーの処理能力超過分は全体として合計されますが、超過分が計算されるのは、すべてのサーバーの処理能力合計が、すべてのサーバーの割り当て済み処理能力合計を超える場合のみです。
{:shortdesc}

## 処理能力プールの変更
{: #cp_modbdwpool}

処理能力プールが作成された後、許可されたユーザーはいつでもそのプールにアクセスできます。 処理能力プールにアクセスすることによって、プールに関連付けられたデバイスの表示、プールへのデバイスの追加、またはプールからのデバイスの削除を行うことができます。 プールにアクセスするには、以下の手順を使用します。

1. 固有の資格情報を使用してカスタマー・ポータルにログインします。
2. メニューから**「ネットワーク (Network)」** > **「処理能力 (Bandwidth)」** > **「プール (Pools)」**を選択して、「処理能力プール (Bandwidth Pools)」ウィンドウにアクセスします。
3. **プール名**をクリックしてプールにアクセスします。 プールに関連付けられた各デバイスが表示されます。
4. **「変更 (Modify)」**タブで、プールの名前変更、デバイスの追加、またはプールからのデバイスの削除を行うことができます。
  * プールの名前を変更するには、現行のプール名が入っているフィールドに新しいプール名を入力します。
  * プールにデバイスを追加するには、**「サーバーの追加 (Add Servers)」**リストからデバイス名を選択し、**「選択 (Select)」**をクリックします。
  * プールからデバイスを削除するには、**「サーバーの削除 (Remove Servers)」**リストからデバイスを選択し、**「選択 (Select)」**をクリックします。
5. **「ラックの変更 (Modify Rack)」**をクリックします。
6. **「すべての処理能力プールの表示 (View All Bandwidth Pools)」**リンクをクリックして「処理能力プール (Bandwidth Pools)」ウィンドウに戻ります。
