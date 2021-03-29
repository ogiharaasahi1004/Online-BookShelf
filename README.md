# My-BookShelf

## サービス概要

![My-BookShelf トップ](https://i.gyazo.com/33338cc4841856b1e2b6faca8e4d7096.png)

私は自ら積極的に学んだ知識を記録として残しておきたいと思いました。、だから私ははその本の知識を保存しておくために私なりの本棚を作りたいと思い、製作しました。

画像つきなので、表紙を見るだけで内容や本の情報を思い出せる、人間の逆らえない忘却曲線を意識したサービスです。

***
## 作る上で意識した事

文字だけだとわかりにくいので、視覚的に内容を思い出せるように画像を追加したり、シンプルですが簡単に登録と削除ができるようにアイコンを追加するなどユーザーのことを考えて作成しました。

一つ一つの機能自体はいたってシンプルなものばかりであり、画期的で面白みのある作品かどうかと問われればあまり自信はありません。

しかしながら、Rails最大の強みでもある「MVCアーキテクチャ」の概念にひたすら忠実に従い、何よりも基本を意識した構成を心掛けております。

## 制作したきっかけ

人は一日後に昨日の事を７４％も忘れてしまうという、人間の忘却の能力は恐ろしい能力を持っています。

私自身も、メンタルの本や技術書など、本をたくさん読むのですが、知識は復習しないと忘れてしまいます。

だから学習したことを保存しておき、どこでも思い出すためにも、オンライン上に自分なりの本棚がどうしてもほしかったからです。

読みきって保存していくと、本棚が増えていくのも読みがいがあると思ったからです。

私以外の本を読む人も同じ悩みを抱えていると思うので、その問題も解決します。

***
## 重視した点
- 本好きの人の悩みを解決することを、課題解決をテーマの中心にしました。
- 私も本好きなのでわかりますが、顧客の悩みを解決するために作りました。
- サービス自体は、なるべくシンプルに作り、基本に忠実に作り、動作が軽いことを大切にしました。
- 動作確認を、機能ごとと全体の動作確認も行う点をとても大切にしました。
- チーム開発を意識して、GitHubの機能をしっかりと活用し、「issueを確認 -> branchを切る -> 開発を行う -> pushする -> pull requestを送信する -> mergeする」といったチーム開発の流れを疑似的に再現するなど、より実践的な環境で作業を進めました。

　
## 技術内容
- フレームワーク:Ruby on Rails（ '5.2.2'）
- DB: 'mysql2', '>= 0.4.4', '< 0.6.0'
- DB：PostgreSQL (本番環境)
- バージョン管理:Git
- インフラ:Heroku
- Webサーバ:puma('3.11')
- スタイルシート:sass-rails', '~> 5.0'
- パスワードセキュリティ:'bcrypt', '~> 3.1.7'

***
## URL
https://my-bookshelf.herokuapp.com/

テストユーザーアカウント

メールアドレス：user@example.com
パスワード：password
***

# 開発環境
- Ruby  2.5.3
- Rails 5.2.2

***

# 実装した各種機能

『記事関連』
- 記事一覧表示機能
- 詳細表示機能
- 記事投稿機能
- 記事削除機能
- エラーメッセージ表示機能
- お気に入り機能（いいね機能）
- ヘージネーション機能（kaminari）

『ユーザー関連』
- ユーサー登録機能
- ロクイン/ログアウト機能
- ユーサーフォロー機能
- DBテーフルのリレーション機能
***


## ログインページ
![My BookShelf  ログインページ](https://i.gyazo.com/a015e8300b0c0414531ec3c7bf19ce64.png)

## トップページ1（ログイン後）
![My BookShelf トップページ（ログイン後）](https://i.gyazo.com/05918fa4fb2cdac7e6d1c277feba914a.jpg)

## トップページ2（ログイン後）
![My BookShelf  投稿一覧ページ](https://i.gyazo.com/363c50b13c4c1f96afb007b204afc070.png)

## 書籍の登録ページ（ログイン後）
![My BookShelf 書籍の登録ページ](https://i.gyazo.com/5ce3466ee39011d496d9cf857365b56b.png)

# 作成者の自己紹介

新潟大学工学部 新３年　荻原朝飛（２０歳）

*将来の夢 : 地方に全力で貢献する、ユーザーに喜んでもらえるエンジニアになること。*

- 得意な分野: 
チーム活動、コミュニケーション、プレゼンテーション
- スキルセット: 
HTML/CSS、Ruby、JavaScript、Vue.js、Firebase、MySQL、Git、GitHub
- やりたいこと: 
ヒトとヒトが繋がれる場所を作りたかった。
- Ruby選んだ理由: 
まず、Webアプリケーション開発の知見と動的型付け言語の知見をつける。
- Goをやる理由: 
今、最も価値の高い静的型付け言語は「Go」だと思うから。
- 目標: 
静的型付け言語の知見とマイクロサービス方式での開発手法に関する知見をつけて、お客さまを喜んでもらえるエンジニアになる。

『想いが伝わると非常に嬉しいです！ありがとうございました！』

***


