# README
# ポートフォリオ/クラウドファンディングサイト
- サービス概要: 利用者がプロダクトを投稿しユーザがそのプロダクトに対して出資をするサービスです。  
## 知り合いの方に協力して頂き実務を想定,GitHub Flowを用いIssuesでのタスク管理,コードレビュー後にmergeを実施。  
 - 独自のメソッドなど自身で考え構築し細かくcommitしていき修正,改善。また、進捗状況など合わせて意識的に管理。
 - 質問などSlackでのやりとりも相手の時間を使わせない事などチームで開発する意識し開発を行いました。  
※ 現在、主要のバックエンドのみ実装。重要なモデル周りの理解を深める為にも極力Gemを使用しておりません。  

## 使用技術
 - Ruby 2.6.5
 - Rails 6.0.3
 - MySQL 5.7
 - Docker 19.03.12
 - Docker-compose 1.27.2
 - Rspec
 - Rubocop/per-commit

## 機能
 - ユーザ登録, ログイン機能(devise)
 - 運営管理者機能(enumを用い判断,ルーティングをネームスペースで分けサービスの管理)
 - プロダクトの投稿機能(画像投稿にActiveStorageを使用)
 - プロダクトへの出資機能
 - カテゴリー機能
 - いいね機能
 - メッセージ機能
 - 検索機能(車輪の再開発になりますがよりモデル周りの理解を深める為Gemは使用していません。)

## テスト
- Rspec
  - 単体テスト(model)自身で考えたメソッドのテストを重点的にテストしました。
