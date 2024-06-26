# portfolio

- ポートフォリオサイト
- リンク
  - [portfoliosite](https://kurospica.link/)
  - [ComnityPost](http://kurospica.link:8080/CommunityPost/)

## ローカル開発

### 開発経緯

- 職業訓練の卒業発表として制作しました。
- 初めてのグループ開発ということもあり貴重な経験ができましたが課題もたくさん残りました。
  - 制作物は自分の関与したもののみの範囲を公開です。 

### 使い方
- ①まず最初の画面で新規登録
- ②管理者orユーザーで登録にチェックを入れ、任意の名前、ID、パスワードを入力(次回以降はIDとパスワードでログイン)
- ③管理者では投稿の削除や登録したIDなどの管理が可能。ユーザーではテキストや画像の投稿が可能。


### 各種コマンド

## 実装完了までの手順

1. デザイン検討　コンテンツ企画 (約 3 時間)

- ２～３週間は思いついたことなどをノートにまとめていた
- その中から実現できそう、拡張性のありそうなものをピックアップ

2. 制作 (約 10日間)

- 下記を参考に検討
  - 「エンジニア ポートフォリオ」で Goolge 検索して出てきた転職サイト
  - 実際のエンジニア・デザイナーのポートフォリオ
- 画像などの素材
  - 生成AI、フリー素材（利用規約に則り）

3. サーバー構築・デプロイ (約 3週間)

- クラウドサービスに興味があり、話題のAWSに目を付けた。
　- 実はサービス開始して5年以上経過していることに驚いた。
- 全く知識がないところから始めたためかなりの時間を要した。   
  

3. コーディング (約 3 日間)

4. Web サイトを公開 

- 

## 工夫したこと

- グローバルメニューを固定配置し、どのページにいてもすぐ別のコンテンツをみることができる
- レスポンシブ対応を行った
- コンテンツごとの切り口で色の変更
- 動きをつけて単調さをなくすようにした
- テキストと画像を格納するテーブルは一緒にしたほうが良いけれど、勉強のためにあえて2つのテーブルにわけてSQLを書いた
- 


## 開発環境

### 言語

- HTML
- CSS
- Java
- SQL

### ライブラリ

- commons-fileupload-1.5
- commons-io-2.8.0
- h2-2.2.224
- jsoup-1.17.2
- jstl-api-1.2
- jstl-impl-1.2

### ツール

- Eclipse
- H2database
- AWS/Lightseil/Linux
- wordpress
- ApacheTomcat
