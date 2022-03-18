# autumn_frontend
旧カリキュラム用作業リポジトリ

<br>
## ドキュメント（運用マニュアル）
https://github.com/Kurogoma939/autumn_curriculum_docs

### !! 命名規則もあるので必ず上記リポジトリのREADMEは一読すること !!
<br /><br />

## 管理スプレッドシート
https://docs.google.com/spreadsheets/d/1U9LFo-4XtFK7y10jNKO7snRLKP6k1mmWKzxaAkMWv1I/edit?usp=sharing
<br /><br />

## カリキュラムの導入

### 1.作業フォルダの作成 & 移動
1. リポジトリをcloneする
2. VSCodeでcloneしたフォルダを開く
3. 左下でブランチ切り替えもしくは以下のコマンドでブランチを切り替え、作業を行う。

各コマンドは以下の通りです。
```
// cloneする
git clone リポジトリURL

// ブランチ切り替え
git checkout ブランチ名
```
ーこれ以降の環境構築はカリキュラムの進捗に合わせて適宜行ってください。

<br />
<br />


### ＜中級課題の環境構築＞
中級課題の環境構築で使うと思うので、手順だけこちらにも掲載しておきます。<br>
必要な段階でやって下さい。本体カリキュラムはリポジトリ内に格納してあるので参照してください。

<br>
#### 00_環境構築
こちらはNode.jsを入れるだけで、上記の環境構築の段階でできているので特に作業はありません。
動作確認として、仮想環境にある状態で`$ node -v` と打ってバージョンが表記されれば問題ありません。

#### 01_webpack

###### 作業フォルダまで移動
`$ cd work/01-webpack`

###### 初期化・package.jsonの生成
`$ npm init -y`

###### webpackのインストール
`npm install webpack webpack-cli --save-dev`

#### 02_ejs
###### フォルダの移動
`$ cd .. && cd 02_ejs`
###### npm install & 実行
`$ npm install`
`$ npm run start`

###### 次に行くために一旦サーバー停止
サーバーを停止するためには **control + c** で止まります。

動作確認  [localhost:9000](http://localhost:9000)

#### 03_sass
###### フォルダの移動
`$ cd .. && cd 03_sass`
###### npm install & 実行
`$ npm install`
`$ npm run start`



