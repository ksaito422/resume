# 職務経歴書

<p class="updated-date">最終更新: 2022/09/03</p>

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
    - EC2, ECS(Fargate), ECR, RDS(MySQL, Aurora), CloudFront, S3, WAF, Route53, ALB, AutoScaling, Firehose, SES, SNS, AppSync, DynamoDB
- 医療事務
  - FileMaker や VBA での開発・運用
  - 診療報酬請求や医療統計の作成

## 意欲・興味

- バックエンド・インフラ（パブリッククラウド）領域の技術に対して関心が強いです
- ナレッジの共有を積極的に行い、チーム全体のスキルアップに貢献したいと思っています
- 1→10 のプロダクトの成長フェーズに関わり、パフォーマンスの改善やサービスを安定稼働させるための活動に興味があります

## 技術スタック

### 言語

<p>
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
- [GitHub](https://github.com/saitooooooo)

## 職務経歴(詳細)

### 株式会社インプル（2021/3~在籍中）

#### プロジェクト外での社内活動

- 中途エンジニア向けのインターンのメンター業務を担当
- ナレッジ共有や品質向上のため、他プロジェクトのインフラ設計レビューの実施

#### 会員制 Web サイトの開発

- 担当業務
  - AWS, Terraform(AWS Provider 4.3.0) でインフラ設計・構築を担当
  - CloudFront, S3, WAF でウェブサイトのホスティング環境の構築
  - CloudWatch, Firehose, S3 でログモニタリングとログ保存用バケットへの配信ストリームの構築
  - Firehose, CloudWatchLogsSubscriptionFilter で Datadog へのログ配信ストリームの構築
  - Datadog でメトリクスやログレベルによるアラートの構築
- 成果や意識した点
  - 脆弱性診断などでは発見しにくい、IAM の最小権限の原則に沿った権限付与をして、クラウドのセキュリティを向上した

#### 不動産のマッチングアプリ開発

- 担当業務
  - AWS でインフラ構築からアプリとの連携部分の開発を担当
  - Nginx, php-fpm で Laravel の実行環境の構築
  - SystemsManagerParameterStore でシークレット管理
  - AppSync, DynamoDB を利用したチャット機能の認可周りの修正
  - バックエンドの CD として、GitLab-CI + CodeDeploy で EC2 への自動デプロイの実装
  - フロントエンドの CI/CD として、GitLab-CI で ビルドと S3 へのファイルアップロード、CloudFront のキャッシュ削除を実装
- 成果や意識した点
  - プロジェクト終盤での参画でステージング環境へ手動デプロイで属人化していたため、自動デプロイの仕組みを構築した
  - 秘匿情報の管理が適切に行われていなかったので、AMI から秘匿情報の切り離して、セキュリティを向上した

#### NFT 販売プラットフォームのアプリ開発

- 担当業務
  - フロントエンド側の開発、画面設計、デザインチームとの調整を担当
  - Firebase Authentication / Dynamic Links を利用した認証機能とダイナミックリンクの実装
  - イーサリアム決済導入のため、WalletConnect で Metamask 連携の実装
  - Stripe 決済の導入のため、Stripe-ui を利用した画面実装
- 成果や意識した点
  - バック・フロントの担当領域が不明瞭な機能（Stripe, Firebase）の設計時に、シーケンス図を作成して、スムーズに開発できるようにした
  - 顧客とデザイン・UI 実装後のレビューを行い、操作性や UI の表示サイズなどユーザビリティ向上のための取り組みを行なった
- 苦労した点
  - イーサリアムに対する知識不足やライブラリの情報の少なさから、イーサリアム決済の導入が非常に困難でした

#### ランニングアプリの開発

- 担当業務
  - バックエンド側の開発（Web API・管理画面）を担当
  - API 設計、DB 設計、画面設計を担当
  - Stripe を利用して決済機能の実装（Stripe Checkout)
  - ElastiCache for Redis を利用してランキングボードの実装
  - 認証機能の実装（jwt-auth)
- 成果や意識した点
  - バックエンド開発経験者が少なかったため、雛形となるコードの実装やコードレビューや実装方針の相談に乗り、チーム全体のスキルアップと開発速度を上げる取り組みを行なった
  - フロントが使いやすい API を作るために、フロントチームとコミュニケーションを取り、調整を行なった

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
- aws certified Solutions Architect Associate（2021/10）
- aws certified Solutions Architect Professional（2022/04）
- aws certified Security Specialty（2022/05）
- aws certified Database Specialty（2022/06）
