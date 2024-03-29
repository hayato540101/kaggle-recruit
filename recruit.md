#### 概要

&nbsp;&nbsp;リクルートが提供するレビューサービスやPOSデータを活用し、未来のレストラン訪問者数を正確に予測するコンペティション

- URL: https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting
- 予測対象: 特定の日付の来訪者数
- データ形式: テーブルデータ ＞ 時系列
- データセットサイズ: 約数十万行*7テーブル
- 評価基準: RMSLE

#### Score

|       提出ファイル       |       詳細       |       Private Leaderboard       | Rank |
| ---------------------- | ---------------------- | ---------------------- | ---------------------- |
|  2021-08-13_23-03-27.csv  |  baseline  | 0.72230 | 1920/2148 |
|  2021-08-14_17-31-27.csv  |  クリッピングされた目的変数でリトライ | 0.72007 | - |
|  2021-08-14_22-44-00.csv  |  cvしてパラメータチューニング | 0.74184  | - |
|  2021-08-15_14-27-31.csv  |  再度パラメータチューニング | 0.72196 | - |
|  2021-08-15_16-27-35.csv  |  month_of_year | 0.72597 | - |
|  2021-08-15_18-46-11.csv  |  ['air_store_id', 'dow']別の統計量(min,max,mean,count,median)を特徴量として追加 | 0.54999 | - | 
|  2021-08-15_19-12-55.csv  |  ccross-validation を適用してモデルのチューニング | 0.54618 | - |
|  |  |  |  |