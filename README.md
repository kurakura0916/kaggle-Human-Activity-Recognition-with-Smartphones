# [WIP]kaggle-Human-Activity-Recognition-with-Smartphones

## 概要
kaggleの[Human-Activity-Recognition-with-Smartphones](https://www.kaggle.com/uciml/human-activity-recognition-with-smartphones/home)を用いた行動分類問題を行う

## データセットの説明
スマートフォンに取り付けられたセンサー情報（計561の特徴量）に対して「歩いている」「登っている」「降りている」「座っている」「立っている」「寝ている」の6つ行動がラベリングされている。


## 環境
Python 3.6.4 :: Anaconda, Inc.

## 作業手順

1. データの読み込み
2. データの確認
3. データの前処理
  - 入力データと正解データを分割
  - 入力データの正規化
  - 入力データと正解データをタプル型でもつ
4. ミニバッチ用のデータを作成
5. モデルの定義
  - 隠れ層：7
6. 学習の実行
7. 損失関数とイテレーションのプロット
7. テストデータへモデルを当てはまめる
8. precision / recall / f1値 / accuracyの算出

## モデル
- 隠れ層:6層
- 活性化関数：ReLu
- パラメーター更新方法：Adam
