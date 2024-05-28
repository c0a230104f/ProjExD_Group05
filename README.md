# 新無双こうかとん

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
新無双こうかとん

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* 第4回の課題で追加した機能

### 追加機能
* ボス追加
* 玉壁反射(C0A23010追加)
* 通常の敵を強く
* こうかとんの残機追加
* ゲームクリア画面の追加（追加完了）

### 自分が追加した機能
* ボスの出現機能
* scoreに応じてボスの出現間隔を短くした
* ボスが爆弾をたくさん吐き出してくる
* ゲームクリア画面の追加
* ビームの反射機能
### 自分が追加した技能
*  frame という引数の初期化
*  NeoBeamにあった複数のたまをあるスコアを超えたら使えるようにした
*  前回作ったgravity クラスの修正　K_LSHIFTをK_RSHIFTに変更
* gravity にあった　400を100に変更
* frameを使って敵の出現度を上げた
* 敵のパワーアップのためあるスコアが超えるとフレームが減り、敵の出現度が上がる
