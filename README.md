# 2Dシューティングゲーム 
執筆者 伊東聖矢 最終更新日2021/12/17
# 制作意図

**「大前提として人にゲームを届けたいという想いは確かです」**

元々クラスの中にはライバルがいませんでした

そのため自分が技術的にも成長する刺激が少なく困っていました

そのためライバルを作るために技術やチーム開発をするうえで必要な知識(Github, Sourcetree)を教えたかったのです

バンタンゲームアカデミー1年次の審査会(学んできた技術をゲームを発表するという形で発表する場)が近かったこともありこのプロジェクトを立ち上げました

# 概要

制作進行中です

2021バンタンゲームアカデミー1年次後期審査会に向けたチーム制作の2D-シューティングゲームです

Githubをフル活用した制作です

タスク振り分, 進行管理をIssuesやProjectsを用いて行いました

## プレイ動画

[未完成ですので完成後記載予定です](https://github.com/ItoSeiy/2DShooting-first-grade/blob/develop/README.md)

## 作業内容(伊東聖矢) こだわり

**ここにゲーム面での作業内容を記載すると莫大な分量になりますので[こちらのIssue](https://github.com/ItoSeiy/2DShooting-first-grade/issues?q=is%3Aissue+is%3Aclosed+assignee%3AItoSeiy)をご覧ください**

基底クラスやゲームマネージャーを作る際はとにかく汎用性が高く扱いやすいものを意識してつくりました

[EnemyBase](https://github.com/ItoSeiy/2DShooting-first-grade/blob/feature/enemy_bese_class/Assets/1Ito/Scripts%20Ito/Enemy/EnemyBese.cs)
[BulletBase](https://github.com/ItoSeiy/2DShooting-first-grade/blob/feature/bullet_bese_class/Assets/1Ito/Scripts%20Ito/Bullet/BulletBese.cs)
[GameManager](https://github.com/ItoSeiy/2DShooting-first-grade/blob/feature/game_maneger/Assets/1Ito/Scripts%20Ito/GameManager.cs)

プロジェクトメンバーへの技術的なことを教える(プログラミング, Unityの知識)

Issueの作成

**Issueへのこだわり**

例)誰がどのブランチ名のブランチで作業するかを確実に明記する

例)書体,大きさなどを要点とそうでは無いもので相違点をつくる

例)**ファイル整理が大事なので**ファイル名の指定やオブジェクト名の指定を記載した

==================================================================

オブジェクト名やファイル管理が大事だと思った経緯

   ↓

以前に[ゲームジャム](https://github.com/ItoSeiy/1124GameJam)を行った際ゲームが時間内に完成できなかった
   
   ↓　

理由は最後に行う機能同士の組み込みで時間がかかりすぎたため

   ↓
    
機能同士の組み込みで時間がかかった理由はオブジェクト名やファイルの管理が甘く組み込む際に混乱を招いたため

   ↓
   
オブジェクト名やファイル管理が大事だと気づいた

==================================================================

例)技術的なことが分からない人のために参考文献等を記載した

例)Assigneesを設定することで均等にタスクを振り分けられているか確認する

例)IssueやPull requestsにラベルを付けることでどのような作業かを一目でわかるようにした

プロジェクトメンバー全員へのタスク振り分け

キャラクター等のイラスト発注書チェック

コミュニケーションが円滑にとれるようにコミュニケーションツール「ディスコード」のサーバーの管理

## 制作人数

バンタンゲームアカデミー高等部1年 6名

バンタンゲームアカデミーキャラクターデザイン専攻 1名

**リードプログラマー, プロジェクト管理　伊東聖矢(自分)**

ゲームイラストレーター　****

プログラマー 神原琉成

プログラマー 和田有矢 (ゲーム原案, 弾幕等の絵の作成, シナリオ [仕様書の作成](https://docs.google.com/spreadsheets/d/1pmrL_Shegj_XCRdpgxkk6T44g7faOuid/edit#gid=861402618))

プログラマー 近藤倫太 (プレイヤーのボムの絵の作成)

プログラマー 安達青　([キャラクター発注書の作成](https://docs.google.com/spreadsheets/d/1sF1S3a3Yge3sxgV-ppf4J7LAbr12b9YN/edit?rtpof=true&sd=true))

小島智祐　([キャラクター発注書の作成](https://docs.google.com/spreadsheets/d/1sF1S3a3Yge3sxgV-ppf4J7LAbr12b9YN/edit?rtpof=true&sd=true), シナリオ)

## 制作形式　

Unity,
Github,
Sourcetree

上記の3点を用いて制作しました
