# titanic-kaggle-portfolio
Titanicコンペでの分析と提出ノートブック

KaggleのTitanicコンペにて、ランダムフォレスト＋特徴量エンジニアリングにより `0.77990` のスコアを達成しました。

## 🔍 分析の流れ
1. データの読み込みと可視化
2. 欠損値の処理（Age, Embarked, Fare）
3. 特徴量の作成（Title, FamilySize, IsAlone）
4. モデリング（RandomForest, 他モデルとの比較）
5. 提出用ファイルの作成

## 📊 モデル比較
- RandomForest：0.77990（ベスト）
- Logistic Regression：0.75程度
- XGBoost：0.70程度（未調整）

## 💡 学び
- 特徴量の工夫が精度に大きく影響する
- CVスコアとLeaderboardスコアは必ずしも一致しない
- アンサンブルは安定化に有効だが、必ずしもスコアが上がるわけではない

## 🔗 提出ファイル
- `submission.csv`：0.77990 の予測結果
