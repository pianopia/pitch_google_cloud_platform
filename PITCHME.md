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

### GCPとは

Googleのインフラをそのまま公開した、

プロダクトアウトのサービス

---

### GCPとは

- 世界のネットワークトラフィックの約40%がGoogle
- Google独自の海底ケーブルが8本ある（他社はなし）
- インフラのハードウェアも自社開発のもの
- LivwMigration・・・ダウンタイムのない運用
- 3年間で5兆円の技術投資を行っている

---

### GCPとは

- 強みは***ネットワーク***
- Regionは大阪と東京
- 同国に複数Regionがあるのは日米だけ

---

## GCEとGAE

---

GCE・・・Google Compute Engine

GAE・・・Google App Engine

---

## その他のサービス

---

- Cloud Storage
- Cloud SQL
    - データ分析基盤
- Spanner
- Google Datastore
- Cloud Function
    - AWS Lambdaのようなサーバーレス
- Cloud Database
    - NoSQL
- AutoML VISION

---

## GKE

---

### GKEとは

- Kubernetesによるコンテナ管理を行えるVM

---

### Kubernetesとは

- クーバネティス、クバネティスと呼ぶ
- サーバーコンテナオーケストレーションツール
- k8sと略される

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

1. にアクセス
2. Googleアカウントでログイン
3. 

---

### BigQuery Sandbox

BigQueryの無料枠と同様の環境を、クレジットカード登録なしで使用できるサービス

---

## 実際のDB

---

## PythonでBigQuery

---


```
# 1. google cloud ライブラリを実行
$ pip3 install google-cloud


# 2. BigQueryをインポート
from google-cloud import bigquery
```

---

コード例：クエリを投げて、新しくデータセットを作成する

```
import bigquery

def createBigQueryDataSet():
    
```

