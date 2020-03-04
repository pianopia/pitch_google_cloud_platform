---

## Google Cloud Platform
BigQueryハンズオン勉強会

---

## Google CLoud

---

### Google Cloud
Google Cloudは二つのサービス
@ul[list-spaced-bullets text-09]
- Google Cloud Platform（以後、GCP）
- G Suite・・・Google DocumentsやSpread Sheet, Gmailなど
@ulend

---

### GCP

Googleのインフラをそのまま公開した、

プロダクトアウトのサービス

---

### GCP
@ul[list-spaced-bullets text-09]
- 世界のネットワークトラフィックの約40%がGoogle
- Google独自の海底ケーブルが8本ある（他社はなし）
- インフラのハードウェアも自社開発のもの
- LivwMigration・・・ダウンタイムのない運用
- 3年間で5兆円の技術投資を行っている
@ulend

---

### GCP

@ul[list-spaced-bullets text-09]
- 強みは***ネットワーク***
- Regionは大阪と東京
- 同国に複数Regionがあるのは日米だけ
@ulend

---

## GCEとGAE

---

GCE・・・Google Compute Engine

GAE・・・Google App Engine

---

### GCE
@ul[list-spaced-bullets text-09]
- 仮想マシン (IaaS)
- Linux や Windows サーバを立ち上げることができる
- CPU のコア数やメモリを調整することも可能 (カスタムマシンタイプ)
@ulend

---

### GAE
@ul[list-spaced-bullets text-09]
- GCP における PaaS サービス。
- アプリをデプロイするだけで、インフラは GCP におまかせ
- 環境構築が不要なので、オートスケールも簡単
- 対応言語は Node.js、Java、Ruby、C#、Go、Python、PHP
@ulend

---

## その他のサービス

---

@ul[list-spaced-bullets text-09]
- Cloud Storage ストレージ
- Cloud SQL データ分析基盤
- Spanner 大規模データ分散が可能なRDB
- Google Datastorea 永続的な Key-Value ストア
- Cloud Function AWS Lambdaのようなサーバーレスa
- Cloud Scheduler 定期実行や予約実行が可能なスケジューラ
- AutoML Vision コードレスでAIや機械学習向け画像認識作成サービス
@ulend

---

## GKE

---

### GKEとは
- Kubernetesによるコンテナ管理を行えるVM

---

### Kubernetesとは
@ul[list-spaced-bullets text-09]
- クーバネティス、クバネティスと呼ぶ
- サーバーコンテナオーケストレーションツール
- 複数マシンで同じコンテナを動作
- 複数コンテナにロードバランシング
- リクエストが増えてきたらコンテナを増やしたり (オートスケール)
- コンテナが死んだら再起動したり
@ulend

---

## AutoML VISION

---

### AutoML VISIONの始め方

1. 一般データセットのインポート
2. ラベル選択
3. 学習開始ボタンを押す

---

## BigQuery

---

### データ分析に使用することができるNoSQL

---

### 実際にやってみよう！

---

### BigQuery Sandboxの使用

1. ChromeでGoogleアカウントにログイン
2. https://console.cloud.google.com/bigquery にアクセス

---

### BigQuery Sandbox

BigQueryの無料枠と同様の環境を、
クレジットカード登録なしで使用できるサービス

---

## 実際のBigQuery & FirebaseAnalyticsデータ

---

## PythonでBigQuery

---


```
# 1. google cloud ライブラリを実行
$ pip3 install google-cloud


# 2. BigQueryをインポート
from google-cloud import bigquery
```


