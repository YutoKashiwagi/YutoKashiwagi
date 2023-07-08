<!--
**YutoKashiwagi/YutoKashiwagi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# 柏木優人(カシワギ ユウト)

## 職務要約
2020/07 ~ Webエンジニア

## 技術経歴

### Ruby(主に2.7.x)

- 2020/07 ~ 2023/07あたりに主にHanami上で利用
- Ruby on Railsは個人開発と業務で数ヶ月利用した程度

### JavaScript(ES6), TypeScript(3.9)

- 2020/07 ~ 2021/06あたりに主にNuxt.js上で利用
- TypeScriptは開発体験が非常に良かった

### PHP

- 2021/03 ~ 2021/06あたりに主にLaravel上で利用
- PHP自体はそれほど勉強しておらず、Laravelを使って開発する上で適宜ググったり、他言語と類推しながら雰囲気で利用していた程度

## 興味がある/勉強していきたい分野

- 設計
- テスト
- DB設計
- インフラ

## SNS
- [GitHub](https://github.com/YutoKashiwagi)

- [Twitter](https://twitter.com/kashiwakikanko)

- [Qiita](https://qiita.com/kashiwamochi_ruby_rails)


## 大事にしている考え方

### マインド面
- 他者尊重
- ギブアンドテイク
- 主体性をもって行動すること
- 素直であること
- 成長するために苦しみと積極的に向き合う

### 開発面
- まず要件をしっかり固める
- TODOを整理してからコードを書く
- 後々の保守性、可読性を考える
  - その場しのぎは避ける
- 言語、フレームワークの知識より基礎知識
- インターフェースとコメント→テスト→実装の順番で開発するのが好み
  - [A Philosophy of Software Design](https://www.amazon.co.jp/Philosophy-Software-Design-2nd-English-ebook/dp/B09B8LFKQL/)、[テスト駆動開発](https://www.amazon.co.jp/%E3%83%86%E3%82%B9%E3%83%88%E9%A7%86%E5%8B%95%E9%96%8B%E7%99%BA-%EF%BC%AB%EF%BD%85%EF%BD%8E%EF%BD%94%EF%BC%A2%EF%BD%85%EF%BD%83%EF%BD%8B-ebook/dp/B077D2L69C/)に影響を受けてこのスタイルで開発するようになった

# 職務経歴

## 株式会社LegalOn Technologies (2021/08 ~ 現在)

### 法務向けナレッジマネジメントサービス
2021/09 ~ 2023/07

#### 使用技術

- Hanami
- Ruby
- RSpec
- Sidekiq
- Swagger
- AWS
- Datadog
- Docker
- Git

#### 業務内容

法務向けナレッジマネジメントサービスのバックエンドの開発を担当
- アプリで発行したメールアドレスを宛先に含めてメールすると、その内容をアプリに保存できる機能の継続的な開発
  - この開発を通してメールの仕様（[RFC5322](https://datatracker.ietf.org/doc/html/rfc5322)）についての理解が深まった
- ナレッジマネジメントサービスの基本的な機能の継続的な開発
- バックエンドの設計改善
- ドメイン駆動設計で開発

## 受託開発企業 (2020/07 ~ 2021/06)

### 農家向け農業資材関連ECサイトの新規開発
2021/04 ~ 2021/06

#### 使用技術
- Nuxt.js(SSR)
- TypeScript
- Cypress
- Swagger
- Laravel
- Docker
- Git

#### 業務内容
- Laravelを用いたREST APIの開発
  - ユーザー認証、カート、住所などのコア機能の開発

#### 複数事業部を持つ企業様の統合ECサイト開発
2020/10 ~ 2021/06

#### 使用技術
- Nuxt.js(SSR)
- TypeScript
- Cypress
- Swagger
- Laravel
- Docker
- Git

#### 業務内容
- 事業部ごとに分散しているECサイトの統合
- フロントエンドのリーダーとして開発を主導
- Nuxt.jsを用いたフロントエンドの開発をメインで実装
  - 認証、既存機能の再実装、新機能の実装など
  - フロントの決済機能
    - 通常決済
    - Amazon Pay V2

### 老舗酒造の自社ECサイトのフルリプレイス
2020/07 ~ 2020/10

#### 使用技術

- Nuxt.js(SSR)
- Laravel
- Docker
- Git

#### 業務内容
- 可動中のECサイトのフルリプレイス
- Nuxt.js(SSR)を用いたフロントエンドの実装をメインで担当
- 認証、既存機能の再実装、新機能の実装など、決済周り以外のほぼ全てを一人で担当
- 既存の要件、デザインを反映しつつ、新規機能の実装、変更が容易に行えるように改善
  - 1000行近くある責務盛り盛りのコンポーネントを単一責任の原則に則りリファクタリング
  - ネストが深くなり、再利用不可能になっているSCSSのリファクタリングなど
