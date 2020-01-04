---
title: プロフィール
date: 2020-01-01 14:05:31
editLink: false
tags:
  - profile
  - about this site
description: 筆者プロフィールとブログの発信内容、ブログの由来について
---

# プロフィール
## 筆者について
こんにちは。栗原真太郎です。
WEB系ベンチャー企業2社を経て、現在は外資系ITコンサルティングファームにてクアーキテクトとして従事しています。WEBアプリケーションエンジニアとして10年以上のキャリアを積んできましたが、どうすれば品質と生産性を最大化できるのかを考え続けた結果、開発者エクスペリエンスの重要性を強く感じるようになってきました。私自身はバックエンドの開発を主に、インフラ、クラウドコンピューティング、DevOps系ツールの管理などWEBアプリケーションの構築に必要なアクティビティを業務、個人での開発を通じて経験してきました。そこに生産性最優先のベンチャー企業での視点と、システムインテグレーターとしてエンタープライスシステム開発の視点を加え、多角的な視点で開発者エクスペリエンスを最大化するプラクティスを本ブログを通して発信しています。技術に特化した記事だけでなく、受託開発の改善点についても言及しているので、開発者だけでなく、システム開発に関わる方全般に少しでも価値ある情報が発信できれば幸いです。

## 開発者エクスペリエンス
本ブログでの最大のテーマは`開発者エクスペリエンス(Developer Experience)`です。
開発者エクスペリエンスと言っても見解は色々とあると思いますが、私は以下のように定義しています。

* 開発者がモノ作りに集中できること
* 開発者のキャリアにとって価値のある技術選定が行われていること
* コストが安いこと

### 開発者がモノ作りに集中できること
最も重要な要素として、モノ作り。つまりビジネスロジックの開発に注力できることであると考えています。クラウドコンピューティング、SaaS等の隆盛によりビジネスの差別化を生みづらい要素は開発をする必要がなくなってきています。言い換えるならば`DRY`の原則を守ることによって注力すべき領域を最小化できるアーキテクチャーを策定するということです。

### 開発者のキャリアにとって価値のある技術選定が行われていること
開発者にとって技術のキャッチアップは避けては通れない道です。誤った技術選定をすると、開発者の市場価値にメリットがない経験になってしまいます。特に近年では同じ様な技術でも選択肢が多いので、より寿命が長く、一般的な技術を採用することが重要です。より一般に受け入れらている技術を選択することで関連エコシステムを利用できる機会が増えたり、WEBでの情報収集も容易になります。もう一点重要な点としては、多機能系の肥大なプロダクトは選ばないことです。特定領域に特化したプロダクトは、その領域のDeepな知見が得られることが多いのと、それ自体の教育コストは高くなりずらい傾向があります。特にAWSのサービス群などはちょうどいい分割単位だなと思います。あとは各ピースをパズルのように組み立ていけばよいので、一般的かつ薄い技術を採用していくことで、そのプロジェクトに参画した開発者のツールボックスは充足されていきます。

### コストが安いこと
とどのつまりシステム開発とはコストカットである。ということは絶対的な原則であると考えています。そして我々開発者にとって唯一といっても良い定量的な指標です。ランニングコストは当然のこと、人件費や教育コストも含まれます。安易にOSSを使おうという意味ではなく、上記二つの要素の最終判断をするときの判断材料として重要な要素になってくるイメージです。また`DevOps`のプラクティスと、`一般的なプラウティスを採用`するということも非常に重要です。例を挙げるならば、[IaC](https://ja.wikipedia.org/wiki/Infrastructure_as_Code)を実施することでドキュメントメンテナンスのコストを最小減にする。[The TWELEVE-Factor App](https://12factor.net/)の原則に則ることでシステム全体のカバナンスを効かせることで、プロジェクトメンバーの新規参画コストを下げる。などが挙げられます。

上記の結果、[サーバレスアーキテクチャー](https://en.wikipedia.org/wiki/Serverless_computing)、[Jam Stack](https://jamstack.org/)こそが開発者エクスペリエンスを最大化するアーキテクチャーであると結論付け、日々キャッチアップに勤しんでいます。本ブログでは同アーキテクチャ関連の技術をメインに発信していきます。

## 3code TechBlog について
{{ $siteTitle }}は私個人で運営している技術ブログで、ブログも個人で開発し、AWSのCloud Front(CDN)経由で公開しています。

前述したように、[サーバレスアーキテクチャー](https://en.wikipedia.org/wiki/Serverless_computing)、[Jam Stack](https://jamstack.org/)をベースに開発者エクスペリエンスを最大化するための情報発信をしています。

### 記事のフォーマット
各記事にガバナンスを効かせることで読者の方の情報収集コストを最小化できればと考えています。

テック系の記事はいわゆるCookBookであると考えています。DRYの原則に従い記事のフォーマットは[O'Reilly Problem/Solution/Discussion CookBook format ](https://guides.emberjs.com/v1.12.0/cookbook/contributing/understanding_the_cookbook_format/)を、記事に記載すべき内容は[Vue.js CookBook Introduction](https://jp.vuejs.org/v2/cookbook/index.html)を参考にしています。

記事の内容によっては完全に準拠できてはいませんが、{{ $siteTitle }}の各記事は以下のフォーマットで構成されます。各章は更に細かい章立てで構成される場合があります。

#### Problem 必須
記事で扱う問題、ゴールのアウトラインを説明します

#### Solution 必須
Problemで提起した問題の解決案のサマリーを説明します。解決方法だけを探している場合、ここまで読んでいただければ目的を達成できるようにしています

#### Discusion 任意
Solutionの内容、そこに至った背景などを深掘りします。より深い理解の手助けができるようこの章を充実させるよう努めています。記載する内容は[Vue.js CookBook Introduction](https://jp.vuejs.org/v2/cookbook/index.html)で推奨されている項目から適切なものをピックアップしています。

#### See Also 任意
参考リンクの一覧です。

テック系の記事には極力サンプルコードとあわせて提供しています。サンプルコードと記事はそれぞれGithubで公開しており、レポジトリーのディレクトリ構造は[README.md](https://github.com/creep32/3code-tech-blog/blob/master/README.md)をご確認下さい。

### サイト名の由来
ブログには`3code`と名前をつけました。これには私の趣味であるPUNK ROCKが由来しています。
PUNK ROCKは文化的要素、精神的な要素、音楽的な要素とそれぞれ特徴がありますが、音楽的な要素としてはスリーコードのギターリフをかき鳴らすシンプルな点が挙げられます。スリーコードのシンプルなリフの代表格は3大パンクバンドの一つThe Ramonesですが、彼らのインタビューを読んだところ、その音楽性が生まれたのは**楽器が弾けなかったから**というのが理由だそうです。とりあえずやってみる。ということですね。かっこよくないですか？

エンジニアにとってアウトプット、とりあえず手を動かしてみることは非常に重要だと考えます。そんなことから、このブログに`3code`と名づけることにしました。私はただのサラリーマンエンジニアですが、先人のエンジニアたちが発信してくれた情報に助けられた恩返しとして自身でもやってみようとこのブログを開設しました。もし自分でもやってみたいと思っているけど自信がなくて動けてない人がいたら一緒にとりあえずやりましょう！

最後にこのプログのスリーコードなテーマソーングのリンクを貼って終わりたいと思います。拝読ありがとうございます。

<iframe width="560" height="315" src="https://www.youtube.com/embed/TYh1lRR1m6Y" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

