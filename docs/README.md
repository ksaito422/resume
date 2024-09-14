# 職務経歴書

<p class="updated-date">最終更新: 2024/09/14</p>

## 基本情報

| key      | value                 |
| -------- | --------------------- |
| 氏名     | 齋藤啓太(Saito Keita) |
| 生年月日 | 1991/04/22            |
| 居住地   | 東京                  |
| 最終学歴 | 専門学校卒            |

## 職務経歴(概要)

- Web・スマホアプリケーションの開発
  - RubyOnRails, React を 1 年ほど経験
  - 過去に Go1.18〜1.20, PHP7 系、 Laravel8, ReactNative あわせて 1 年半
- インフラ設計・構築・ログ収集基盤の構築
  - Google Cloud, Terraform あわせて 1 年ほど経験
  - 過去に AWS でのインフラ設計・構築 1 年
  - Google Cloud の利用サービス
    - Cloud Storage, Cloud Load Balancing, Cloud CDN, Cloud Logging
  - AWS の利用サービス（業務利用）
    - EC2, ECS(Fargate), ECR, RDS(MySQL, Aurora), CloudFront, S3, WAF, Route53
    - ALB, AutoScaling, KinesisDataFirehose, SES, SNS, CloudWatch
- 医療事務
  - FileMaker や VBA での院内システム開発・運用
  - 診療報酬請求や医療統計の作成

## 意欲・興味

- バックエンド・インフラ（パブリッククラウド）領域の技術に対して関心が強いです

## 技術スタック

### 言語

<p>
  <img src="https://img.shields.io/badge/-Ruby-CC342D.svg?logo=ruby&style=plastic">
  <img src="https://img.shields.io/badge/-Go_v1.18-76E1FE.svg?logo=go&style=plastic">
  <img src="https://img.shields.io/badge/-PHP_v7.2~8.0-777BB4.svg?logo=php&style=plastic">
  <img src="https://img.shields.io/badge/-TypeScript-007ACC.svg?logo=typescript&style=plastic">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E.svg?logo=javascript&style=plastic">
</p>

### フレームワーク・ライブラリ

<p>
  <img src="https://img.shields.io/badge/-RubyOnRails-CC342D.svg?logo=ruby&style=plastic">
  <img src="https://img.shields.io/badge/-Laravel_v6.8~8.0-E74430.svg?logo=laravel&style=plastic">
  <img src="https://img.shields.io/badge/-React-61DAFB.svg?logo=react&style=plastic">
  <img src="https://img.shields.io/badge/-ReactNative_v0.64-61DAFB.svg?logo=react&style=plastic">
</p>

### ミドルウェア

<p>
  <img src="https://img.shields.io/badge/-PostgreSQL-336791.svg?logo=postgresql&style=plastic">
  <img src="https://img.shields.io/badge/-MySQL_v8.0-4479A1.svg?logo=mysql&style=plastic">
  <img src="https://img.shields.io/badge/-Nginx-009639.svg?logo=nginx&style=plastic">
</p>

### その他

<p>
  <img src="https://img.shields.io/badge/-GoogleCloud-4285F4.svg?logo=google-cloud&style=plastic">
  <img src="https://img.shields.io/badge/-AWS-232F3E.svg?logo=amazon-aws&style=plastic">
  <img src="https://img.shields.io/badge/-Terraform-844FBA.svg?logo=terraform&style=plastic">
  <img src="https://img.shields.io/badge/-Docker-2496ED.svg?logo=docker&style=plastic">
  <img src="https://img.shields.io/badge/-Neovim-57A143.svg?logo=Neovim&style=plastic">
</p>

## アウトプット

- [Tech blog](https://blog.saito.page/)
- [Zenn](https://zenn.dev/saito9)
- [GitHub](https://github.com/ksaito422)

## 職務経歴(詳細)

### 株式会社SmartHR（2023/06~在籍中)

#### プロジェクト外での社内活動

- プロダクト上の画層参照を効率化するためのアプリケーションからインフラまで含めた改修（現在進行系）
- Google Cloud の利用コスト削減活動
  - 過剰な設定の見直しなど
- 採用活動（主にカジュアル面談の実施）

#### 申請機能の追加開発

- 担当業務
  - バックエンド実装、テストコードの実装
  - フロントエンド実装
  - QA、ライティング業務

### 株式会社インプル（2021/03~2023/05)

#### プロジェクト外での社内活動

- 中途エンジニア向けのインターンのメンター業務を担当
- ナレッジ共有や品質向上のため、他プロジェクトのインフラ設計レビューの実施

#### 在来線タブレット用業務アプリのリプレイス

- 担当業務
  - DB 設計、API 設計、バッチ処理の設計を担当
  - アプリチームと連携して proto ファイルにスキーマの定義
  - gRPC を使用した API の実装（主にビジネスロジックや SQL の組み立て）
  - gomock を使用してテストコードの実装
- 成果や意識した点
  - 経験の浅いメンバーに対してペアプロを実践して、約 1 ヶ月でプロジェクトで自走できるレベルになるまでサポートしたこと

#### 会員制 Web サイトの開発

- 担当業務
  - AWS, Terraform(AWS Provider 4.3.0) でインフラ設計・構築を担当
  - CloudFront, S3, WAF でウェブサイトのホスティング環境の構築
  - CloudWatch, Firehose, S3 でログモニタリングとログ保存用バケットへの配信ストリームの構築
  - Firehose, CloudWatchLogsSubscriptionFilter で Datadog へのログ配信ストリームの構築
  - Datadog でメトリクスやログレベルによるアラートの構築
- 成果や意識した点
  - IAM の過剰な権限付与を防ぐために最小権限で IAM を作成し、開発速度と引き換えに最小権限の原則に則って、クラウドのセキュリティ向上に努めたこと

#### NFT 販売プラットフォームのアプリ開発

- 担当業務
  - フロントエンド側の開発、画面設計、デザインチームとの調整を担当
  - Firebase Authentication / Dynamic Links を利用した認証機能とダイナミックリンクの実装
  - イーサリアム決済導入のため、WalletConnect で Metamask 連携の実装
  - Stripe 決済の導入のため、Stripe-ui を利用した画面実装
- 成果や意識した点
  - バック・フロントの担当領域が不明瞭な機能（Stripe, Firebase）の実装時にチーム間で認識齟齬が発生しないように、シーケンス図を作成して、責務を明確にし手戻りの発生を削減したこと
- 苦労した点
  - Metamask 連携の実装で自分の知識不足や社内に相談できるエンジニアが不在のため、実装に工数を要したが、ライブラリのドキュメントなどを参考に自己解決し イーサリアムに関する知見を得られたこと

#### スポーツ関連のスマホアプリ開発

- 担当業務
  - バックエンドの開発（Web API・管理画面）を担当
  - API 設計、DB 設計、画面設計を担当
  - Stripe を利用して決済機能の実装（Stripe Checkout)
  - ElastiCache for Redis を利用してランキングボードの実装
  - 認証機能の実装（jwt-auth)
- 成果や意識した点
  - チーム全体でバックエンドの開発経験が浅いため、雛形となるコードの実装などを行い、スキルアップして開発速度向上のための取り組みをして、円滑にプロジェクトを進めることに貢献したこと

### 病院事務（2013/04~2021/01）
システム開発歴とほぼ無関係なので割愛します。

## 保有資格

- 基本情報技術者（2019/11）
- AWS Certified Solutions Architect Associate（2021/10）
- AWS Certified Solutions Architect Professional（2022/04）
- AWS Certified Security Specialty（2022/05）
- AWS Certified Database Specialty（2022/06）
- AWS Certified Developer Associate（2022/10）
- AWS Certified SysOps Administrator Associate（2022/11）
