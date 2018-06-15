- 2 教師あり学習
  - 2.1 クラス分類と回帰
  - 2.2 汎化、過剰適合、適合不足
    - 2.2.1 モデルの複雑さとデータセットの大きさ
  - 2.3 教師あり機械学習アルゴリズム
    - 2.3.1 サンプルデータセット
    - 2.3.2 k-最近傍法
      - 理解しやすいが、処理速度が遅く多数の特徴量を扱うことができない
    - 2.3.3 線形モデル
      - Ridge回帰：L2正則化
      - Lasso回帰：L1正則化、いくつかの係数が完全に0になる
      - ロジスティック回帰
      - 線形SVM
    - 2.3.4 ナイーブベイズクラス分類器
    　- GaussianNB: 任意の連続データ
      - BernoulliNB: 2値データを仮定
      - MultinomiaNB: カウントデータを仮定、文章中の単語の出現数等
    - 2.3.5 決定木
      - 事前枝刈りや、枝刈りで過剰適合を防ぐ
      - 過剰適合しやすく、汎化性能が低い傾向がある
      - 可視化が容易で、小さい決定木であれば専門家でなくても理解可能
    - 2.3.6 決定木のアンサンブル法
      - ランダムフォレスト：ブートストラップサンプリングを行い、複数の決定木を作成、多数決
      - 勾配ブースティング回帰木：今までの結果を反映させつ複数の浅い決定木を作成する。ランダムフォレストより時間がかかる
    - 2.3.7 カーネル法を用いたサポートベクタマシン
      - サンプルの個数が大きくなるとうまく機能しない、また前処理（スケーリング）が必要。
    - 2.3.8 ニューラルネットワーク（ディープラーニング）
  - 2.4 クラス分類器の不確実性推定
    - 2.4.1 決定関数（Decision Function）
    - 2.4.2 確率の予測
    - 2.4.3 多クラス分類の不確実性
  - 2.5 まとめと展望