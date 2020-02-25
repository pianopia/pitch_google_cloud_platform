---

## Google Cloud Platform

---

Google Cloudは二つのサービス

- Google Cloud Platform（以後、GCP）
- G Suite・・・Google DocumentsやSpread Sheet, Gmailなど

---

### GCPとは

Googleのインフラをそのまま公開した、

プロダクトアウトのサービス

---

### GCPとは

- 世界のネットワークトラフィックの約40%がGoogle
- Google独自の海底ケーブルがある（他社はなし）
- インフラのハードウェアも自社開発のもの
- LivwMigration・・・ダウンタイムのない運用
- 3年間で5兆円の技術投資を行っている

---

### GCPとは

- 強みは***ネットワーク***

---

## GCEとGAE

---

GCE・・・Google Compute Engine

GAE・・・Google App Engine

---

## その他のサービス

---

- Cloud SQL
    - データ分析基盤
- Spanner
- Cloud Storage
- Cloud Function
    - AWS Lambdaのようなサーバーレス
- Cloud Database
    - NoSQL
- AutoML VISION

---

## Kurbenetes

---

### Kurbenetesとは

サーバーコンテナ管理ツール

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

### コード例）クエリを投げて、新しくデータセットを作成する

```
import bigquery

def createBigQueryDataSet():
    
```

