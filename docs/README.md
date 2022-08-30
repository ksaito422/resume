# 職務経歴書

## 基本情報

| key      | value                 |
| -------- | --------------------- |
| 氏名     | 齋藤啓太(Saito Keita) |
| 生年月日 | 1991/04/22            |
| 居住地   | 札幌                  |
| 最終学歴 | 専門学校卒            |

## 職務経歴(概要)

- Web・スマホアプリケーションの開発
  - PHP, Laravel, ReactNative あわせて 1 年
- インフラ設計・構築・ログ収集基盤の構築
  - AWS, Terraform あわせて半年
  - AWS の利用サービス
    - EC2, ECS, RDS, CloudFront, S3, WAF, ALB, AutoScaling, KinesisFirehose, SES, SNS, AppSync, DynamoDB
- 医療事務
  - FileMaker や VBA での開発・運用
  - 診療報酬請求や医療統計の作成

## 意欲・興味

- バックエンド・インフラ（パブリッククラウド）領域の技術に対して興味関心が強い
- ナレッジの共有を積極的に行い、チーム全体のスキルアップに貢献したいと思っています
- 1->10 のプロダクトの成長フェーズに関わり、サービスの安定した運用に貢献したい

## 技術スタック

### 言語・ランタイム

<p>
  <img src="https://img.shields.io/badge/-PHP-777BB4.svg?logo=php&style=plastic">
  <img src="https://img.shields.io/badge/-Typescript-007ACC.svg?logo=typescript&style=plastic">
  <img src="https://img.shields.io/badge/-Javascript-F7DF1E.svg?logo=javascript&style=plastic">
  <img src="https://img.shields.io/badge/-Node.js-339933.svg?logo=node.js&style=plastic">
</p>

### フレームワーク・ライブラリ

<p>
  <img src="https://img.shields.io/badge/-Laravel-E74430.svg?logo=laravel&style=plastic">
  <img src="https://img.shields.io/badge/-React-61DAFB.svg?logo=react&style=plastic">
  <img src="https://img.shields.io/badge/-ReactNative-61DAFB.svg?logo=react&style=plastic">
</p>

### その他

<p>
  <img src="https://img.shields.io/badge/-AWS-232F3E.svg?logo=amazon-aws&style=plastic">
  <img src="https://img.shields.io/badge/-Terraform-844FBA.svg?logo=terraform&style=plastic">
  <img src="https://img.shields.io/badge/-Docker-1488C6.svg?logo=docker&style=plastic">
  <img src="https://img.shields.io/badge/-NeoVim-3E93D3.svg?logo=Neovim&style=plastic">
</p>

## アウトプット

- [Tech blog](https://blog.saito.page/)
- [Zenn](https://zenn.dev/saito9)
- [GitHub](https://github.com/saitooooooo)

## 職務経歴(詳細)

### 株式会社インプル（2021/3~在籍中）

- 在来線タブレットシステムのリプレイス(2022/7 ~ 現在)

  - 業務内容
    - DB 設計書、API 設計書、バッチ設計書の作成
    - タブレットから呼ぶ API(gRPC)の実装
  - 使用技術
    - Go1.19, MySQL8.0, Docker

- ディーラーが提供するオーナーサイトのインフラ構築(2022/4 ~ 2022/7)

  - 業務内容
    - AWS でのインフラ設計・構築
      - 利用サービスは、ECS, ECR, ALB, Aurora, S3, CloudFront, WAF, Firehose, SES, Route53
    - Terraform によるコードベースでのインフラ構築
    - CloudWatch, Firehose, S3 でログモニタリングとログ保存用バケットへの配信ストリームの構築
    - Firehose, CloudWatchSubScriptionFilter で Datadog へのログ配信ストリームの構築
    - Datadog でのメトリクスやログレベルによるアラートの構築
    - Datadog でメトリクスダッシュボードの作成
  - 使用技術
    - AWS, Terraform1.1.6, Datadog

- 不動産 WEB アプリの開発・インフラ構築(2022/3 ~ 2022/3)

  - 業務内容

    - AWS でのインフラ構築
      - 利用サービスは、EC2, ALB, AutoScaling, RDS, DynamoDB, AppSync, S3, CloudFront, Route53, ACM, CodeDeploy, SystemsManager, WAF, SES
    - Nginx, php-fpm での Laravel の実行環境の構築
    - SystemsManagerParameterStore でのシークレット管理
    - AutoScaling 用のゴールデンイメージの取得
    - バックエンドの CD として、GitLab-CI + CodeDeploy で EC2 への自動デプロイの実装
    - フロントエンドの CI/CD として、GitLab-CI で ビルドと S3 へのファイルアップロード、CloudFront のキャッシュ削除を実装

  - 使用技術
    - AWS, Nginx1.18, Laravel8.0, MySQL8.0

- ブロックチェーン WEB ウォレットアプリ(PWA)のインフラ構築(2022/1 ~ 2022/2)

  - 業務内容

    - AWS でのインフラ構築を担当
      - 利用サービスは、EC2, RDS, AWS Backup, S3, CouldFront, Route53, ACM, SES, SNS
    - Node.js アプリケーションのため、Nginx でプロキシサーバーをたて、pm2 でプロセス管理をして、EC2 でアプリ実行
    - バックエンドの CD として、GitHub Actions で EC2 への自動デプロイの実装
    - フロントエンドの CD として、Github Actions で S3 へのファイルアップロード、CloudFront のキャッシュ削除を実装

  - 使用技術
    - AWS, Github Actions

- 業務用 Android ハンディアプリの開発(2021/11 ~ 2021/12)

  - 業務内容
    - Android の業務アプリ開発にてフロントエンドの開発支援
    - jcifs-ng のライブラリを使用して SMB プロトコルで、ファイル共有サーバーからのファイル取得機能の実装
  - 使用技術
    - Kotlin, SQLite, Hilt(DI)
  - 備考
    - 2 ヶ月のスポットでの参画のため、経験としては浅い

- ブロックチェーンアプリの開発(2021/8 ~ 2021/9)

  - 業務内容
    - 画面設計、デザインチームとの調整を担当
    - API の組み込みや画面の実装
    - Firebase Authentication を使用した際の処理フローをバックエンド側と共有し、実装
    - Firebase Dynamic Links を使用して、ダイナミックリンクの実装
    - イーサリアム決済導入のため、WalletConnect で Metamask 連携の実装
    - Stripe 決済の導入のため、Stripe-ui を利用した画面実装
  - 使用技術
    - ReactNative0.64, JavaScript, Recoil(状態管理）, Firebase Authentication/DynamicLinks

- ランニングアプリの開発(2021/4 ~ 2021/7)

  - 業務内容
    - バックエンド開発チームのリーダーとして、コードレビューや開発のサポート
    - API 設計、DB 設計、画面設計を担当
    - スマホアプリから呼ぶ Web API(Restful)・管理画面の開発
    - Stripe を利用しての決済機能の実装(Stripe Checkout)
    - ElastiCache for Redis でランキングボードの実装
    - 認証機能の実装(jwt-auth)
  - 使用技術
    - Laravel8.0, Docker, MySQL8.0, Redis, AWS

### 病院事務（2013/04~2021/01）

- 社会医療法人医仁会 中村記念南病院（2018/06〜2021/01)
- 社会医療法人医仁会 中村記念病院（2016/08〜2018/05)
- 医療法人五月会 小笠原クリニック札幌病院（2013/04〜2016/07)

- 職種
  - 医事部 診療情報管理士
- 業務内容
  - ローコード開発ツールを利用して業務システムの開発・保守、データベース管理
  - 診療記録の管理、医療統計の作成、委員会の運営、診療録の開示、外部調査への協力

## 資格

- 基本情報技術者（2019/11）
- aws certified Solutions Architect Associate(2021/10)
- aws certified Solutions Architect Professional(2022/04)
- aws certified Security Specialty(2022/05)
- aws certified Database Specialty(2022/06)
