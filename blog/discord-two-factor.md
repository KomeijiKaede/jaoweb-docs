---
title: Discordで二段階認証をする方法
category: tips
author: ekipa
image: 	https://storage.jaoafa.com/4c41a61904e2fe2924040ed16946e589.png
createdAt: 2021-03-21
updatedAt: 2021-04-13
---

## 二段階認証って何？

二段階認証(Two-Factor Authentication、2FA)は、簡単に言うと「**アカウントにログインするために、2度認証を行う**」ことを呼びます。  
Discordではパスワードに加えて、スマートフォンやタブレットを使ってコードを読み取り、発行されたコードを入力することによって二段階認証をすることができます。

## 二段階認証を有効化する

※現在、モバイル版のDiscordでは二段階認証を行うことができません。

### 1. 設定を開く

画面左下の歯車をクリックして、設定を開きましょう。
![設定を開く](https://storage.jaoafa.com/44d0f3d9c4f397585eb9c9b18a8d8819.PNG)

### 2. 二段階認証を有効化する

設定を開くと「マイページ」という画面が最初に出てきます。その中の「**二要素認証を有効化する**」をクリックしてください。パスワードが要求されるので入力して進んでください。
![二段階認証を有効化する](https://storage.jaoafa.com/efb2c253451eeb8ed42d8c1c54c79ccd.PNG)

### 3. 表示された内容を確認する

有効化ボタンをクリックすると、「3つのステップ」が表示されます。これに従って解説していきます。
![3つのステップ](https://storage.jaoafa.com/a41a4aeb88749425880b52b150624993.PNG)

### 4. アプリをダウンロードする

手持ちのスマートフォン、またはタブレットでアプリにダウンロードします。2通りありますが今回は「**Google Authenticator**」というアプリを用いて解説します。

* [Google Authenticato‪r (AppStore)](https://apps.apple.com/jp/app/google-authenticator/id388497605) / [(GooglePlay)](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=ja&gl=US)
* [Twilio Auth‪y (AppStore)‬](https://apps.apple.com/jp/app/twilio-authy/id494168017) / [(GooglePlay)](https://play.google.com/store/apps/details?id=com.authy.authy&hl=ja&gl=US)

### 5. QRコードをスキャン

ダウンロードしたアプリを開いて「**開始**」をタップ。
すると以下の画面が表示されるので、「**QRコードをスキャン**」をタップし、先程のQRコードを読み取ってください。

※QRコードが読み取れる環境がない場合はセットアップキーを入力してください。(先程の画面で「aaaa bbbb cccc dddd」と書かれていた部分がセットアップキーです)
![QRコードをスキャンをタップ](https://storage.jaoafa.com/16b13f8392a36ea4024885111b6a332d.png)

### 6. 表示されたコードをDiscordに入力

スキャンに成功すると以下のような画面になります。表示されている青色の数字をDiscordに入力し、「**有効にする**」をクリックしてください。
![認証コードを確認](https://storage.jaoafa.com/2af6a3877152b3d4ccc72551d0440d1b.png)
![認証コードをDiscordに入力](https://storage.jaoafa.com/83eb999255605aae6c3aff01adda03ca.PNG)

### 7. 指示に従う

以下のような画面が表示されたら認証は完了です！  
**バックアップコードのダウンロード**をおすすめします。

![認証完了メッセージ](https://storage.jaoafa.com/34eb6c529bd80751fc7816d6cadafe48.PNG)

## 二段階認証を解除する

### 1. 設定を開く

画面左下の歯車をクリックして、設定を開きましょう。
![設定を開く](https://storage.jaoafa.com/44d0f3d9c4f397585eb9c9b18a8d8819.PNG)

### 2. 二段階認証を解除する

設定を開くと「マイページ」という画面が最初に出てきます。その中の「**二要素認証を解除する**」をクリックしてください。
![連携解除をクリック](https://storage.jaoafa.com/ab2d41eea056a36f21c762ec65255d7b.png)

### 3. コードを入力する

先程のアプリで確認できる「**認証コード**」か、Discordの「**バックアップコード**」を入力してください。  
入力後、「**二要素認証を解除する**」をクリックで解除完了です。
![コードを入力して連携解除](https://storage.jaoafa.com/00725a6ad6a8366d021026d5241580b5.png)

## 二段階認証コードを忘れた！

* [二段階認証コードを忘れた場合 - Discord](https://support.discord.com/hc/ja/articles/115001221072-%E4%BA%8C%E6%AE%B5%E9%9A%8E%E8%AA%8D%E8%A8%BC%E3%82%B3%E3%83%BC%E3%83%89%E3%82%92%E5%BF%98%E3%82%8C%E3%81%9F%E5%A0%B4%E5%90%88)

## 参考記事

* [二段階認証のセットアップ - Discord (日本語)](https://support.discord.com/hc/ja/articles/219576828-%E4%BA%8C%E6%AE%B5%E9%9A%8E%E8%AA%8D%E8%A8%BC%E3%81%AE%E3%82%BB%E3%83%83%E3%83%88%E3%82%A2%E)
