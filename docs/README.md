# 職務経歴書

<p class="updated-date">最終更新: 2023/04/01</p>

## 基本情報

| key      | value                 |
| -------- | --------------------- |
| 氏名     | 齋藤啓太(Saito Keita) |
| 生年月日 | 1991/04/22            |
| 居住地   | 札幌                  |
| 最終学歴 | 専門学校卒            |

## 職務経歴(概要)

- Web・スマホアプリケーションの開発
  - Go, PHP, Laravel, ReactNative あわせて 1 年半
- インフラ設計・構築・ログ収集基盤の構築
  - AWS, Terraform あわせて半年
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
  <img src="https://img.shields.io/badge/-Go-76E1FE.svg?logo=go&style=plastic">
  <img src="https://img.shields.io/badge/-PHP_v7.2~8.0-777BB4.svg?logo=php&style=plastic">
  <img src="https://img.shields.io/badge/-TypeScript_v3.8~4.1-007ACC.svg?logo=typescript&style=plastic">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E.svg?logo=javascript&style=plastic">
</p>

### フレームワーク・ライブラリ

<p>
  <img src="https://img.shields.io/badge/-Laravel_v6.8~8.0-E74430.svg?logo=laravel&style=plastic">
  <img src="https://img.shields.io/badge/-React_v17.0-61DAFB.svg?logo=react&style=plastic">
  <img src="https://img.shields.io/badge/-ReactNative_v0.64-61DAFB.svg?logo=react&style=plastic">
</p>

### ミドルウェア

<p>
  <img src="https://img.shields.io/badge/-MySQL_v8.0-4479A1.svg?logo=mysql&style=plastic">
  <img src="https://img.shields.io/badge/-Nginx-009639.svg?logo=nginx&style=plastic">
</p>

### その他

<p>
  <img src="https://img.shields.io/badge/-AWS-232F3E.svg?logo=amazon-aws&style=plastic">
  <img src="https://img.shields.io/badge/-Terraform_v1.1.6-844FBA.svg?logo=terraform&style=plastic">
  <img src="https://img.shields.io/badge/-Docker-2496ED.svg?logo=docker&style=plastic">
  <img src="https://img.shields.io/badge/-Neovim-57A143.svg?logo=Neovim&style=plastic">
</p>

## アウトプット

- [Tech blog](https://blog.saito.page/)
- [Zenn](https://zenn.dev/saito9)
- [GitHub](https://github.com/ksaito422)

## 職務経歴(詳細)

### 株式会社インプル（2021/03~在籍中）

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

#### 不動産のマッチングアプリ開発

- 担当業務
  - AWS でインフラ構築からアプリとの連携部分の開発を担当
  - Nginx, php-fpm で Laravel の実行環境の構築
  - SystemsManagerParameterStore でシークレット管理
  - AppSync, DynamoDB を利用したチャット機能の認可周りの修正
  - バックエンドの CD として、GitLab-CI + CodeDeploy で EC2 への自動デプロイの実装
  - フロントエンドの CI/CD として、GitLab-CI で ビルドと S3 へのファイルアップロード、CloudFront のキャッシュ削除を実装
- 成果や意識した点
  - プロジェクト終盤に自分が参画し、AWS に手動デプロイを行って開発速度に影響が出ていたため、自動デプロイのパイプライン構築を提案・実装し、属人化をなくし開発速度の向上に貢献したこと

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

- 社会医療法人医仁会 中村記念南病院（2018/06〜2021/01)
- 社会医療法人医仁会 中村記念病院（2016/08〜2018/05)
- 医療法人五月会 小笠原クリニック札幌病院（2013/04〜2016/07)

- 職種
  - 医事部 診療情報管理士
- 業務内容
  - ローコード開発ツールを利用して業務システムの開発・保守、データベース管理
  - 診療記録の管理、医療統計の作成、委員会の運営、診療録の開示、外部調査への協力

## 保有資格

- 基本情報技術者（2019/11）
- AWS Certified Solutions Architect Associate（2021/10）
- AWS Certified Solutions Architect Professional（2022/04）
- AWS Certified Security Specialty（2022/05）
- AWS Certified Database Specialty（2022/06）
- AWS Certified Developer Associate（2022/10）
- AWS Certified SysOps Administrator Associate（2022/11）
