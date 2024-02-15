# Airflow_tutorial

Apache Airflowについて学習するリポジトリ

## 経緯
データエンジニアとして求人を探す中、求められるスキル・扱う事になるであろうスキルとして、Airflowを学びたいと感じた
タスクスケジューラやcronでの実行ではなく、Apache Airflowを導入してデータ処理をワークフロー化したいと思った。

## 目的
Airflowとはなにか？概要を掴み簡単なワークフローを実装できるようになること

## 参照
1. [公式ドキュメント](https://airflow.apache.org/docs/apache-airflow/stable/index.html)


## 学習メモ
### 1. Airflowとは？
バッチ処理をワークフロー化し、スケジューリングと監視を行うプラットフォームらしい。

### 1.1 DAG

    > Airflow™ is a batch workflow orchestration platform. The Airflow framework contains operators to connect with many technologies and is easily extensible to connect with a new technology. If your workflows have a clear start and end, and run at regular intervals, they can be programmed as an Airflow DAG.


DAGを使ってワークフローを記述するらしい。DAGというと因果推論で使われるイメージがあった。依存関係を表すのにも効果的という事かしれない。方向性のある関係性の記述に広く使えそう。
またGitHub ActionsやPowerAutomateのようなワークフローの記述はアローダイアグラムで記述されるが、DAGを採用する理由はあるのだろうか？

### 2. 

## 疑問点
1. Apache Airflowはプラットフォームらしい。ライブラリやフレームワークではなく？

2. タスクスケジューラやcronと比較したメリット・デメリット


3. 開発された経緯。どんな問題を解決しようと開発されたものか？どんなニーズがあったのか?