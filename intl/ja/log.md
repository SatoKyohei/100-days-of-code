# 100 Days Of Code - 学習ログ  \[計443h(26593m)\]

### ■ 155日目: 2024年11月26日　[Twitterリンク](https://x.com/kyohei_IT/status/1861446601807667686)

**今日の進捗**   120
- Node.js/Express編/初級
  - Express Web フレームワーク (Node.js/JavaScript) ⇨ 100%
  - Node.js + Express + MySQL で作る 安全な Webアプリケーション 実践講座 ⇨ 15%


**学んだこと**
- なし



**思ったこと**
- MongoDBやejs、pugなど、現場であまり使われない技術の学習ばかりで、且つ記事が2014~2018年のものばかりで参考にならない。正直不満。
- Node.js/Expressのカリキュラム改善してほしい。この記事はもうやらない。



<br>
<hr>
<br>


### ■ 154日目: 2024年11月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1861196138692653172)

**今日の進捗**   60
- Node.js/Express編/初級
  - Express Web フレームワーク (Node.js/JavaScript) ⇨ 70%


**学んだこと**
- MVCのcontrollerはModelを使って関数定義しているロジックの部分



**思ったこと**
- 難しく考えてましたが、シンプルにcontrollerでは呼び出して使う用の関数定義をまとめてる、みたいなことなんですね。ナットク



<br>
<hr>
<br>


### ■ 153日目: 2024年11月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1860714364178948203)

**今日の進捗**   60
- Node.js/Express編/初級
  - Express Web フレームワーク (Node.js/JavaScript) ⇨ 60%


**学んだこと**
- thisはインスタンス自身を表す



**思ったこと**
- 仮想プロパティ...またナゾの用語が出てきました。でも半分以上はMongoDBに関する知識。なんとか乗り越えよう



<br>
<hr>
<br>


### ■ 152日目: 2024年11月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1860357280899928162)

**今日の進捗**   175
- Node.js/Express編/初級
  - Express Web フレームワーク (Node.js/JavaScript) ⇨ 50%


**学んだこと**
- next()で次のルートハンドラーやミドルウェアの処理に進む
- mongoose.Promise = global.Promise;はmongooseに対し「Node.js標準のプロミスを使って」と指示している



**思ったこと**
- nodemon便利



<br>
<hr>
<br>


### ■ 151日目: 2024年11月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1859984174565990477)

**今日の進捗**   191
- Node.js/Express編/初級
  - node.js/expressでユーザ認証with JWT ⇨ 100%
  - Node.js + Express 4.x + MongoDB(Mongoose)でRESTfulなjsonAPIサーバの作成を丁寧に解説する．+ テストクライアントを用いたAPIテストまで ⇨ 100%


**学んだこと**
- MongoDBコンテナへのアクセス
  1. docker exec -it mongodb bash
  2. mongosh --username xxx --password xxx --authenticationDatabase admin
- JWTのpayloadは、toObject()メソッドをつけてプレーンなオブジェクトにする必要がある



**思ったこと**
- なし



<br>
<hr>
<br>


### ■ 150日目: 2024年11月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1859738638327914683)

**今日の進捗  82
- Node.js/Express編/初級
  - Node.js＋Express＋Passport を使ってみた ⇨ 100%
  - node.js/expressでユーザ認証with JWT ⇨ 50%


**学んだこと**
- passport.authenticate() には、post() で受け取った username と password が渡される
- dockerでの起動だと、mongoDBとの接続設定は'database': 'mongodb://ユーザー:パス@localhost:27017/server_oauth?authSource=admin'



**思ったこと**
- Docker便利✌️



<br>
<hr>
<br>


### ■ 149日目: 2024年11月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1859276519383892457)

**今日の進捗  75
- Node.js/Express編/初級
  - Node.js + Express + Socket.ioで簡易チャットを作ってみる ⇨ 100%
  - Node.js＋Express＋Passport を使ってみた ⇨ 30%


**学んだこと**
- socketioのonが受信でemitが送信
- websocketは双方向でリアルタイム通信を行うためのプロトコル



**思ったこと**
- なし



<br>
<hr>
<br>


### ■ 148日目: 2024年11月19日　[Twitterリンク](https://x.com/kyohei_IT/status/1858902193749062018)

**今日の進捗  120
- Node.js/Express編/初級
  - Node.js + Express 4.x + MongoDB(Mongoose)でRESTfulなjsonAPIサーバの作成を丁寧に解説する．+ テストクライアントを用いたAPIテストまで ⇨ 100%


**学んだこと**
- app.use(express.static(path.join(__dirname, 'public')));でクライアントからpublicフォルダ内のファイルにアクセス可能



**思ったこと**
- dockerでMySQLデプロイしてExpressサーバとSequelizeとの連携成功です✌



<br>
<hr>
<br>


### ■ 147日目: 2024年11月18日　[Twitterリンク](https://x.com/kyohei_IT/status/1858552595914391857)

**今日の進捗  120
- Node.js/Express編/初級
  - ローカルでExpress+Sequelize+SQLiteでバックエンドAPIを作る ⇨ 100%
  - Node.js + Express 4.x + MongoDB(Mongoose)でRESTfulなjsonAPIサーバの作成を丁寧に解説する．+ テストクライアントを用いたAPIテストまで ⇨ 50%


**学んだこと**
- require('dotenv').config()で.env読み込み



**思ったこと**
- MongoDBのカリキュラムが多い気がします...Prisma、Reactなどと組み合わせた教材がやりたい😭



<br>
<hr>
<br>


### ■ 146日目: 2024年11月17日　[Twitterリンク](https://x.com/kyohei_IT/status/1858304125211201713)

**今日の進捗  120
- Node.js/Express編/初級
  - サルでも分かるExpressでのjsonAPIサーバーの作り方 ⇨ 100%（見直しとGitにアップ）
  - ローカルでExpress+Sequelize+SQLiteでバックエンドAPIを作る ⇨ 70%


**学んだこと**
- module.exportsでエクスポート
- .use(パス, require(ルーター))でルーターを読み込みパスも決めれる



**思ったこと**
- sequelizeは初見👀 ORMってPrisma以外にもいっぱいありますな



<br>
<hr>
<br>


### ■ 145日目: 2024年11月16日　[Twitterリンク](https://x.com/kyohei_IT/status/1857939509348016521)

**今日の進捗  285
- Node.js/Express編/初級
  - サルでも分かるExpressでのjsonAPIサーバーの作り方 ⇨ 100%


**学んだこと**
- const router = require('./routes/v1/'); で任意のディレクトリをルーターとして指定可



**思ったこと**
- エラーにハマり1記事にとんでもない時間かけてしまいました….早く取り戻さないと！


<br>
<hr>
<br>


### ■ 144日目: 2024年11月15日　[Twitterリンク](https://x.com/kyohei_IT/status/1857572802666311736)

**今日の進捗  90
- Node.js/Express編/初級
  - サルでも分かるExpressでのjsonAPIサーバーの作り方 ⇨ 50%


**学んだこと**
- npmだけじゃなくbrewでインストールしないとmongodbは動かない


**思ったこと**
- mongodbの起動ができず調べまくってやっと解決しましたが、今度はInsertがうまくいかずMongoDB connection error...
- 数時間溶けてるのでそろそろメンターに頼ろっかな...😭


<br>
<hr>
<br>


### ■ 143日目: 2024年11月14日　[Twitterリンク](https://x.com/kyohei_IT/status/1857086549818548374)

**今日の進捗  60
- Node.js/Express編/初級
  - サルでも分かるExpressでのjsonAPIサーバーの作り方 ⇨ 50%
  - ローカルでExpress+Sequelize+SQLiteでバックエンドAPIを作る ⇨ 10%


**学んだこと**
- const router = require(apiのパス) して app.use(apiのパス, router)で任意のapiを読み込み


**思ったこと**
- 色んな記事をもとにトラシューしてみましたが、どうしてもmongodがcommand not found になってしまう。。。


<br>
<hr>
<br>


### ■ 142日目: 2024年11月13日　[Twitterリンク](https://x.com/kyohei_IT/status/1856735559357796495)

**今日の進捗  60
- Node.js/Express編/初級
  - 初めてのREST API【Re:ゼロから始めるWeb API入門実践編#1】 ⇨ 100%
  - サルでも分かるExpressでのjsonAPIサーバーの作り方 ⇨ 10%


**学んだこと**
- なし


**思ったこと**
- 写経したプロジェクトはGithubにUpして、成果物作る時の参考にしてます！
- これが意外と詰まった時の助けになってくれる✌️


<br>
<hr>
<br>


### ■ 141日目: 2024年11月12日　[Twitterリンク](https://x.com/kyohei_IT/status/1856357198752034941)

**今日の進捗  120
- Node.js/Express編/初級
  - 初めてのREST API【Re:ゼロから始めるWeb API入門実践編#1】 ⇨ 80%


**学んだこと**
- なし


**思ったこと**
- 古い教材だからかもですが、getElementbyIdとかhtml用意するとか即時関数とかは今は使わないような気がしました
- Reactの方が楽そうな箇所がちらほら👀
- バックエンドの勉強と割り切る！


<br>
<hr>
<br>


### ■ 140日目: 2024年11月11日　[Twitterリンク](https://x.com/kyohei_IT/status/1855999119019626980)

**今日の進捗  150
- Node.js/Express編/初級
  - expressで作るHTTPサーバ – 入門編 ⇨ 100%
  - Node.jsとExpressでWeb APIを作ってみよう ⇨ 100%
  - 初めてのREST API【Re:ゼロから始めるWeb API入門実践編#1】 ⇨ 40%


**学んだこと**
- /path/:idのようにurlに渡す個別の値をパスパラメータという
- UUIDのインポートの仕方が変わっていた。const { v4: uuidv4 } = require("uuid");


**思ったこと**
- Next.js経験したおかげでexpressはすんなり理解できてます✌️



<br>
<hr>
<br>


### ■ 139日目: 2024年11月10日　[Twitterリンク](https://x.com/kyohei_IT/status/1855768782872191071)

**今日の進捗  150
- Node.js/Express編/初級
  - REST WebAPI サービス 設計 ⇨ 100%
  - expressで作るHTTPサーバ – 入門編 ⇨ 5%


**学んだこと**
- openapi：componentsでコンポーネント化。$ref:"#/"で呼び出し


**思ったこと**
- 半分くらいは理解できたので周回せず別の教材で補完していきます



<br>
<hr>
<br>


### ■ 138日目: 2024年11月9日　[Twitterリンク](https://x.com/kyohei_IT/status/1855271374513963010)

**今日の進捗  90
- Node.js/Express編/初級
  - REST WebAPI サービス 設計 ⇨ 80%


**学んだこと**
- swaggerはRESTの仕様書を作れるツール。fastapiだと自動生成してくれるが、expressとかNext.jsなどでは自動生成できないかも？


**思ったこと**
- 少し体調悪く、土曜で90mしかできなかったの久々です...切り替えてゆく！



<br>
<hr>
<br>


### ■ 137日目: 2024年11月8日　[Twitterリンク](https://x.com/kyohei_IT/status/1854940448277803268)

**今日の進捗  105
- Node.js/Express編/初級
  - REST WebAPI サービス 設計 ⇨ 50%


**学んだこと**
- OpenID connectは OAuth+認証


**思ったこと**
- REST周りの話、知った気でいましたが、全然入口にも立ってなかったです
- でも未知の領域の学習って決まって1,2ヶ月後くらいに腹落ちするので、今は精一杯やって理解できない状態で次に進んでOKと思ってます。



<br>
<hr>
<br>



### ■ 136日目: 2024年11月7日　[Twitterリンク](https://x.com/kyohei_IT/status/1854543311346016262)

**今日の進捗  165
- Node.js/Express編/初級
  - Node.jsⅤ(学習コース) ⇨ 100%
  - Node.jsⅤI(学習コース) ⇨ 100%
  - REST WebAPI サービス 設計 ⇨ 10%


**学んだこと**
- requestからの値取り出し：req.params.xx, req.body.xx, req.session.xx
- app.メソッド((req, res, next) => {})でnextを実行すると次のミドルウェア関数の処理に移行
- bcrypt.hash()でpasswordをハッシュ化


**思ったこと**
- Next.jsやってたおかげですんなり理解できました



<br>
<hr>
<br>


### ■ 135日目: 2024年11月6日　[Twitterリンク](https://x.com/kyohei_IT/status/1854191724652040404)

**今日の進捗  150
- Node.js/Express編/初級
  - Node.jsⅠ(学習コース) ⇨ 100%
  - Node.jsⅡ(学習コース) ⇨ 100%
  - Node.jsⅢ(学習コース) ⇨ 100%
  - Node.jsⅣ(学習コース) ⇨ 100%
  - Node.jsⅤ(学習コース) ⇨ 10%


**学んだこと**
- connection.query(SQL, 配列, 成功/失敗時の処理)


**思ったこと**
- Node.js編突入！
- 思えばwebの学習開始からはや25120m...
- 1000h必要説ありますが完全未経験でなければそうでもなさそうです



<br>
<hr>
<br>


### ■ 134日目: 2024年11月5日　[Twitterリンク](https://x.com/kyohei_IT/status/1853831859467431975)

**今日の進捗  120
- SQL初級編
  - 【22日間で学ぶ】SQL文、分析関数、テーブル設計、SQLチューニングまでMySQLで覚えるSQL実践講座 ⇨ 30%


**学んだこと**
- constraintで制約名を指定


**思ったこと**
- existsはなんとなく理解。
- テーブル設計の演習をやりましたが、かなりタメになりました✌️
- 必要最低限はやったので一旦SQLは終わりにしてnode.js始めます！



<br>
<hr>
<br>


### ■ 133日目: 2024年11月4日　[Twitterリンク](https://x.com/kyohei_IT/status/1853453786632908828)

**今日の進捗  210
- SQL初級編
  - テーブル設計の考え方とやり方 \[入門編\] ⇨ 100%
  - 【22日間で学ぶ】SQL文、分析関数、テーブル設計、SQLチューニングまでMySQLで覚えるSQL実践講座 ⇨ 30%
  - SQL中級編（SQLab） ⇨ 100%
  - DVD Rental データベースを使ったサブクエリ、トランザクション ⇨ 100%


**学んだこと**
- SQLの様々な関数：substring, trim, to_char, concat, coalesce, length
- 共有/排他ロック：for share, for update



**思ったこと**
- 「テーブル設計」のみにフォーカスを当て、別の教材で基礎の基礎から学ぶ必要がありそう。



<br>
<hr>
<br>


### ■ 132日目: 2024年11月3日　[Twitterリンク](https://x.com/kyohei_IT/status/1853232250592403660)

**今日の進捗  120
- SQL初級編
  - DVD Rental データベースを使ったJOIN、集計とグルーピング ⇨ 100%
  - 一夜漬けSQL ～今日からあなたもデータ分析者～ ⇨ 100%
  - サービス開発者のためのSQLデータ集計入門 ⇨ 100%
  -  超入門！テーブル設計をデータモデリングから考えよう ⇨ 100%


**学んだこと**
- window関数の書式：関数 over(partition by ~ order by ~)
- 集約関数とcase文の併用：関数(case文)



**思ったこと**
- SQLに慣れるにはとにかく実行あるのみですね



<br>
<hr>
<br>


### ■ 131日目: 2024年11月2日　[Twitterリンク](https://x.com/kyohei_IT/status/1852741214543724894)

**今日の進捗  75
- SQL初級編
  - モダンなSQLクライアントソフト「DBeaver」の紹介 ⇨ 100%
  - 【完全無料】SQL：初心者向け学習ロードマップ：SQLの高度なトピックス ⇨ 100%
  - 論理削除と物理削除は何なのか ⇨ 100%
  - SQLの制約の種類とその指定方法 ⇨ 100%
  - SQL素人でも分かるテーブル結合(inner joinとouter join) ⇨ 100%


**学んだこと**
- PostgreSQLへの認証はpg_hba.confで管理



**思ったこと**
- 中級も一瞬で終われそうです✌️


<br>
<hr>
<br>


### ■ 130日目: 2024年11月1日　[Twitterリンク](https://x.com/kyohei_IT/status/1852387536871813432)

**今日の進捗  240
- SQL初級編
  - sqlzoo ⇨ 100%
  - SQL初級編（SQLab） ⇨ 100%
  - DVD Rental データベースのデータを取得、挿入、更新、削除 ⇨ 100%


**学んだこと**
- postgreSQL構築はソースコードからだと最新版の使用可
- yumとかだと最新版はインストールできない



**思ったこと**
- 初級編終わり！case whenや相関サブクエリとかすこし忘れてたのもありましたが概ね問題なし✌️


<br>
<hr>
<br>


### ■ 129日目: 2024年10月31日　[Twitterリンク](https://x.com/kyohei_IT/status/1852146810665734237)

**今日の進捗  60
- SQL初級編
  - sqlzoo ⇨ 20%
- Ansible


**学んだこと**
- ansible_userで接続先ユーザー指定
- ansibe-playbook に --ask-become-pass で sudo PWを指定可



**思ったこと**
- 業務でAnsible使うことになったので学習！


<br>
<hr>
<br>


### ■ 128日目: 2024年10月30日　[Twitterリンク](https://x.com/kyohei_IT/status/1851640534852567069)

**今日の進捗  165
- SQL初級編
  - ＳＱＬ攻略 - Ｗｅｂ上でＳＱＬを実行しながらマスターするサイト ⇨ 100%
  - SQLBolt ⇨ 100%
  - sqlzoo ⇨ 20%


**学んだこと**
- concat(a, b)で結合
- mid(a,b)でaの文時列をb番目から取得



**思ったこと**
- Web上で実行できるSQLの無料ページおすすめです👍
  - http://sql.main.jp/sql01.html
  - https://sqlbolt.com/lesson/introduction
  - https://sqlzoo.net/wiki/SQL_Tutorial/ja


<br>
<hr>
<br>


### ■ 127日目: 2024年10月29日　[Twitterリンク](https://x.com/kyohei_IT/status/1851285651209265572)

**今日の進捗  150
- SQL初級編
  - さまざまなリレーション ⇨ 100%
  - 学生管理システムのDBを構築してみよう ⇨ 100%
  - 複雑なSELECT文 ⇨ 100%
  - ＳＱＬ攻略 - Ｗｅｂ上でＳＱＬを実行しながらマスターするサイト ⇨ 70%


**学んだこと**
- すべて学習済みの内容だったのでなし



**思ったこと**
- OSS DB取得したおかげで初級は瞬殺できそうです✌️
- 予定としては
  - 11月：SQL中級, node.js, Express
  - 12月：AWS, Docker, ポートフォリオ作成
  - 1月：就活開始
  - 2月：内定
- の予定！絶対やりきる


<br>
<hr>
<br>


### ■ 126日目: 2024年10月28日　[Twitterリンク](https://x.com/kyohei_IT/status/1850914521738797069)

**今日の進捗  120
- SQL初級編
  - 【完全無料】SQL：初心者向け学習ロードマップ：データベースの基礎、SQLの基礎 ⇨ 100%
  - DBの基礎 ⇨ 100%
  - SELECT文の基礎 ⇨ 100%
  - テーブル操作の基礎 ⇨ 100%
  - テーブルの結合 ⇨ 100%


**学んだこと**
- すべて学習済みの内容だったのでなし



**思ったこと**
- ほとんど知ってる内容だったので一瞬で終了！年内残すところ2ヶ月しかないので、SQLは最速で終わらせます✌️




<br>
<hr>
<br>


### ■ 125日目: 2024年10月27日　[Twitterリンク](https://x.com/kyohei_IT/status/1850558452101431531)

**今日の進捗  60
- Next/Prisma編
  - Nextjs/Prismaを使ってフルスタックTodoアプリを作成しよう 70%


**学んだこと**
- バックエンド(記事取得,supabase-prisma連携,vercelデプロイ)
- UI(編集,詳細,一覧,認証)
- Material UI
- 他多数



**思ったこと**
- 時間かけ過ぎたので中断😭ただ、とんっっでもなくためになりました。点と点が繋がった感。




<br>
<hr>
<br>


### ■ 124日目: 2024年10月26日　[Twitterリンク](https://x.com/kyohei_IT/status/1850374333245612255)

**今日の進捗  240
- Next/Prisma編
  - Nextjs/Prismaを使ってフルスタックTodoアプリを作成しよう 70%


**学んだこと**
- あるけど書き忘れた


**思ったこと**
- prismaとsupabaseのpostgresを連携してGETとPOSTまで実装できました！確実に身についてる...！
- あと編集機能と認証を実装してstyle整えたら一旦この課題は終わりにしよっかな


<br>
<hr>
<br>


### ■ 123日目: 2024年10月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1849864087678935370)

**今日の進捗  570
- Next/Prisma編
  - Nextjs/Prismaを使ってフルスタックTodoアプリを作成しよう 50%


**学んだこと**
- たくさん


**思ったこと**
- 2ヶ月間インプットばかりで本当に作れるか心配でしたがちゃんと地力で書けるようになってて感激...😭
- やっと一歩踏み出した感...
- 甘い部分はたくさんあるのでまだしばらく掛かりそうです。


<br>
<hr>
<br>


### ■ 122日目: 2024年10月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1849608323043352943)

**今日の進捗  75
- Next/Prisma編
  - Nextjs/Prismaを使ってフルスタックTodoアプリを作成しよう -->10%


**学んだこと**
- <Stack>のdirection="row", spacing, useFlexGap で簡単にflexboxが実現可



**思ったこと**
- なんかそれっぽくなってきました！2段目以降のwidthがおかしいのを修正しないと。


<br>
<hr>
<br>


### ■ 121日目: 2024年10月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1849119678402384278)

**今日の進捗  240
- Next/Prisma編
  - How to Build a Fullstack App with Next.js, Prisma, and PostgreSQL ✔︎
  - Nextjs/Prismaを使ってフルスタックTodoアプリを作成しよう -->10%


**学んだこと**
- Material UI のstyleはsx={{}}で指定
- flex-directionは縦並びか横並びかを指定


**思ったこと**
- 完全に自力で作るのはまだ2回目ですが意外と出だしはよさげ！ちゃんと身についててよかった…


<br>
<hr>
<br>


### ■ 120日目: 2024年10月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1848741686400458917)

**今日の進捗  120
- Next/Prisma編
  - How to Build a Fullstack App with Next.js, Prisma, and PostgreSQL --> 40%


**学んだこと**
- vercel env pull .envでvercel側の環境変数を簡単に引っ張ってこれる


**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 119日目: 2024年10月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1848423820220371262)

**今日の進捗  165
- Next/Prisma編
  - 電子記事販売WebアプリケーションをNext.jsをフル活用して実践力を身に着けるWeb開発マスター講座 
  - How to Build a Fullstack App with Next.js, Prisma, and PostgreSQL --> 5%


**学んだこと**
- microCMSとVercelはwebhookで自動連携可
- .envに環境変数まとめるの便利


**思ったこと**
- バグは残りましたが認証・決済システム実装の良い学びになりました


<br>
<hr>
<br>


### ■ 118日目: 2024年10月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1848026498567147740)

**今日の進捗  390
- Next/Prisma編
  - 電子記事販売WebアプリケーションをNext.jsをフル活用して実践力を身に着けるWeb開発マスター講座 --> 75%



**学んだこと**
- process.env.NEXT_PUBLIC_SERVICE_DOMAIN! などの!は「null、あるいはundefinedではない」という断言


**思ったこと**
- NextAuth認証やStripeとの連携が難しいけど楽しい！コーディングの参考ネタとしてGithubに保存


<br>
<hr>
<br>


### ■ 117日目: 2024年10月19日　[Twitterリンク](https://x.com/kyohei_IT/status/1847792196063559866)

**今日の進捗  300
- Next/Prisma編
  - モダンな技術でフルスタックブログ開発をしてみよう【Next.js13/Prisma/Supabase/Typescriptを利用】✅
  - 電子記事販売WebアプリケーションをNext.jsをフル活用して実践力を身に着けるWeb開発マスター講座 --> 30%



**学んだこと**
- vercel：storage - db作成 - .env.localコピーでprismaと連携


**思ったこと**
- 写経したコードをGitHubとVercelにあげるといつでも見返せれて便利でした！


<br>
<hr>
<br>


### ■ 116日目: 2024年10月18日　[Twitterリンク](https://x.com/kyohei_IT/status/1847295605221249135)

**今日の進捗  60
- Next/Prisma編
  - モダンな技術でフルスタックブログ開発をしてみよう【Next.js13/Prisma/Supabase/Typescriptを利用】 --> 90%



**学んだこと**
- useRefはタグの属性を取得する時とかに使う


**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 115日目: 2024年10月17日　[Twitterリンク](https://x.com/kyohei_IT/status/1846932122512306259)

**今日の進捗  240
- Next/Prisma編
  - Next.jsでPrismaとSupabaseを使ってみる　Prisma設定編　✅
  - Next.jsでPrismaとSupabaseを使ってみる　API編　✅
  - モダンな技術でフルスタックブログ開発をしてみよう【Next.js13/Prisma/Supabase/Typescriptを利用】 --> 60%



**学んだこと**
- prisma.$connect と $disconnect でDB接続／切断
- VSCodeの拡張Postmanが便利
- migrationの役割はDBやスキーマの変更とバージョン管理


**思ったこと**
- 理解できるわけない！と思ってたNext.js, Prismaも数打てば慣れてくるもんですね...
- やっとNext.jsも終わりが見えてきて嬉しい。。


<br>
<hr>
<br>


### ■ 114日目: 2024年10月16日　[Twitterリンク](https://x.com/kyohei_IT/status/1846569175818604993)

**今日の進捗  255
- Next/Prisma編
  - 【Prisma入門】次世代ORMで簡単にデータベース管理ができるようになろう ✔︎
  - Prisma を使った効率的なバックエンド開発ワークフロー ✔︎
  - 【Supabase入門】Todoアプリを作りながらSupabaseをNext.jsとTypescriptで学んでみよう ✔︎
  - Next.jsでPrismaとSupabaseを使ってみる　Prisma設定編 --> 90%



**学んだこと**
- npx prisma studio でテーブルを確認
- schema.prisma に model テーブル名 {} でテーブルを定義し、npx prisma migrate dev --name init で migrateするとテーブルが作成される
- $transaction() の中に任意のCRUD操作を記述することでトランザクション処理になる


**思ったこと**
- 平日だけど4つも進んだ！


<br>
<hr>
<br>


### ■ 113日目: 2024年10月15日　[Twitterリンク](https://x.com/kyohei_IT/status/1846211402341798273)

**今日の進捗  105
- Next v13以降
  - 【Next.js13】最新バージョンのNext.js13をマイクロブログ構築しながら基礎と本質を学ぶ講座 ✔︎
- Next/Prisma編
  - 【Prisma入門】次世代ORMで簡単にデータベース管理ができるようになろう --> 60%



**学んだこと**
- supabaseの.from, .select, .eqなどでDBへのAPIを作成し、fetch関数でAPIのパスを指定
- prisma：model テーブル名 {} でテーブル作成

**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 112日目: 2024年10月14日　[Twitterリンク](https://x.com/kyohei_IT/status/1845865100777070918)

**今日の進捗  330
- Next v13以降
  - 【Next.js13】最新バージョンのNext.js13をマイクロブログ構築しながら基礎と本質を学ぶ講座 --> 90%
- Prettier復習


**学んだこと**
- SSRのログはターミナルに出力
- prettierは.prettierrcで実装。.prettierignoreだと除外
- loading.tsxでローディング実装(error, not-foundなども)

**思ったこと**
- prettierのおかげで学習効率UP！


<br>
<hr>
<br>


### ■ 111日目: 2024年10月13日　[Twitterリンク](https://x.com/kyohei_IT/status/1845474461853909189)

**今日の進捗  120
- Next v13以降
  - 【Next.js13】最新バージョンのNext.js13をマイクロブログ構築しながら基礎と本質を学ぶ講座 --> 60%


**学んだこと**
- SSGはビルド時にレンダリングすること。
- SSRはサーバーサイドでのレンダリング。初回読み込みが速い。

**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 110日目: 2024年10月12日　[Twitterリンク](https://x.com/kyohei_IT/status/1845145172319010887)

**今日の進捗  285
- Next v13以降
  - 全てがここに！Next.jsとSupabaseで構築する認証システム --> 100%
  - 【Next.js13】最新バージョンのNext.js13をマイクロブログ構築しながら基礎と本質を学ぶ講座 --> 5%


**学んだこと**
- 'use client', 'use server' でサーバ側かクライアント側の処理か宣言可
- not-found.tsxのように特定の役割を持たせれるファイル名の命名則がある（？）

**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 109日目: 2024年10月11日　[Twitterリンク](https://x.com/kyohei_IT/status/1844884423122223226)

**今日の進捗  210
- Next v13以降
  - 全てがここに！Next.jsとSupabaseで構築する認証システム --> %


**学んだこと**
- app配下のディレクトリにpage.tsxを作ればディレクトリ名がURLパスになる
- supabaseとnext.js連携：.env作成⇨npx supabase login⇨init⇨link --project-ref

**思ったこと**
- なし


<br>
<hr>
<br>


### ■ 108日目: 2024年10月10日　[Twitterリンク](https://x.com/kyohei_IT/status/1844523881350225931)

**今日の進捗  120
- Ansible
  - \[Zenn\] Ansibleの使い方 --> 10%
- Next v13以降
  - Next.js14で掲示板Webアプリケーションを作ってみよう【Supabase/react-hook-form/zod/shadcnを利用】 --> 100%


**学んだこと**
- インベントリはchildrenでグループ化
- http://prisma.post.XXXX でSQL実行

**思ったこと**
- 業務で使いそうなのでAnsible勉強中。prismaはすこし理解！SQLやっておいてよかったです


<br>
<hr>
<br>


### ■ 107日目: 2024年10月9日　[Twitterリンク](https://x.com/kyohei_IT/status/1844153203715342592)

**今日の進捗  60
- Next v13以降
  - Next.js14で掲示板Webアプリケーションを作ってみよう【Supabase/react-hook-form/zod/shadcnを利用】 --> 70%


**学んだこと**
- zodでフォームのバリデーションを作れる？
- npx shadcn@latest add ~ でコンポーネントをインストール

**思ったこと**
- 同時に初見の技術4つ(Supabase, zod, shadcn, Prisma)やるの厳しいですね..ここはサクッといきます！


<br>
<hr>
<br>


### ■ 106日目: 2024年10月8日　[Twitterリンク](https://x.com/kyohei_IT/status/1843797993289593128)

**今日の進捗  180
- Next v13以降
  - Next.js14で掲示板Webアプリケーションを作ってみよう【Supabase/react-hook-form/zod/shadcnを利用】 --> 70%


**思ったこと**
- supabaseと.envファイル準備
- prismaをインストール→init→migrateでsupabaseと連携（？）
- supabaseとprismaが初見で正直あまり理解できず。来週入門やるので最低限の理解に留めます


<br>
<hr>
<br>


### ■ 105日目: 2024年10月7日　[Twitterリンク](https://x.com/kyohei_IT/status/1843301066773008745)

**今日の進捗  120
- Next v13以降
  - Todoアプリを作りながらNext.js13の新機能を理解してみよう ~Next.js13入門~
  - Next.js14で掲示板Webアプリケーションを作ってみよう【Supabase/react-hook-form/zod/shadcnを利用】 --> 10%


**思ったこと**
- layout.tsxの変更はappディレクトリ配下の全ページコンポーネントに反映


<br>
<hr>
<br>


### ■ 104日目: 2024年10月6日　[Twitterリンク](https://x.com/kyohei_IT/status/1842951664917270853)

**今日の進捗  180
- Next v13以降
  - Next.jsと一緒に学ぶReact講座
  - Next.js 13入門 - App Router対応
  - Todoアプリを作りながらNext.js13の新機能を理解してみよう ~Next.js13入門~ --> 5%


**思ったこと**
- appの下に作成したファイル名でURLが決定される（verによって差異）
- aタグだとリロードしてしまうからLinkタグを使うのが通常
- Githubとvercelの連携で自動デプロイできるのがすごく便利！


<br>
<hr>
<br>


### ■ 103日目: 2024年10月5日　[Twitterリンク](https://x.com/kyohei_IT/status/1842717094510825677)

**今日の進捗  105
- Next v13以降
  - Next.jsと一緒に学ぶReact講座 --> 50%


**思ったこと**
- 今のところReact基礎の復習ばかりなので簡単です！


<br>
<hr>
<br>


### ■ 102日目: 2024年10月4日　[Twitterリンク](https://x.com/kyohei_IT/status/1842216272211443737)

**今日の進捗  75
- Next v13以降
  - Next.jsと一緒に学ぶReact講座 --> 25%


**思ったこと**
- 久々のGitは良い復習でした！


<br>
<hr>
<br>


### ■ 101日目: 2024年10月3日　[Twitterリンク](https://x.com/kyohei_IT/status/1841850468185866437)

**今日の進捗  195
- React 上級
  - 今後のフロントエンド開発で必須知識となるReact v18の機能を丁寧に理解する
- Next v13以降
  - Next.jsと一緒に学ぶReact講座 --> 10%


**思ったこと**
- CSR, SSRの違い
- ハイドレーションとはHTMLとJSの紐づけ
- Next.js, Vercel, GitHub環境構築
- やっとReact上級終わりました！長かったーー
- そして気づけば100日超えてた。次の目標は200日！


<br>
<hr>
<br>


### ■ 100日目: 2024年10月2日　[Twitterリンク](https://x.com/kyohei_IT/status/1841491045001179152)

**今日の進捗  195
- React 上級
  - 今後のフロントエンド開発で必須知識となるReact v18の機能を丁寧に理解する --> 70%


**思ったこと**
- 意識しなくてもAutomatic Batchingでレンダリングがまとまる
- isLoadingも使いたければuseTransition
- 子でTransitionするならuseDeferredValue
- UX向上のためには裏側の仕組み大事ですね🔥


<br>
<hr>
<br>


### ■ 99日目: 2024年10月1日　[Twitterリンク](https://x.com/kyohei_IT/status/1841191845659103531)

**今日の進捗  135
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版
  - 今後のフロントエンド開発で必須知識となるReact v18の機能を丁寧に理解する --> 10%


**思ったこと**
- グローバルステートがやっと少し理解できました✌️
const xxx = createContext() 
↓
useStateでステートを用意
↓
コンポーネントのreturnで<xxx.Provider value={ステート}>
↓
使う側でconst { ステート } = useContext


<br>
<hr>
<br>


### ■ 98日目: 2024年9月30日　[Twitterリンク](https://x.com/kyohei_IT/status/1840784628929745266)

**今日の進捗  90
- React 上級
  - 記事
    - React 18について自分がインプットに使った記事・動画をまとめてみた（随時更新）


**思ったこと**
- React18以前？のレンダリングはすべて同時に行われていたけど、18からはレンダリングに優先順位をつけれるようになって、それがstartTransitionとuseTransitionという理解！


<br>
<hr>
<br>


### ■ 97日目: 2024年9月29日　[Twitterリンク](https://x.com/kyohei_IT/status/1840409893901398468)

**今日の進捗  60
- React 上級
  - （Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 95%）
  - 記事
    - 【React.memo】Reactのパフォーマンス改善方法の整理　✔︎
    - Webフロントエンド パフォーマンス改善ハンドブック　✔︎
    - Reactのパフォーマンス改善を勉強会で開催しました　✔︎
  - React 18について自分がインプットに使った記事・動画をまとめてみた（随時更新）--> 20%


**思ったこと**
- 昨日に引き続き、memo, useCallback, useMemoについてQiitaやZennなどを読了！
- レンダリングの度に再定義される部分(参照が作成される)をメモ化する、という理解で大きく外れてなさそうです✌️
- そしてsuspenseについても学習！


<br>
<hr>
<br>


### ■ 96日目: 2024年9月28日　[Twitterリンク](https://x.com/kyohei_IT/status/1840212664691372092)

**今日の進捗  270
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 95%
  - 記事
    - React.memo / useCallback / useMemo の使い方、使い所を理解してパフォーマンス最適化をする　✔︎


**思ったこと**
- やっとUdemyが終わりましたが、理解度40%くらいなので、もう3~40分ほどコードを眺めたいと思います！


<br>
<hr>
<br>

### ■ 95日目: 2024年9月27日　[Twitterリンク]()

**今日の進捗  60
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 85%


**思ったこと**
- めだ！今日は時間がとれず、ただ模写するしかできなかったので反省。。
- 明日は朝〜夕でしっかりやる予定です


<br>
<hr>
<br>


### ■ 94日目: 2024年9月26日　[Twitterリンク]()

**今日の進捗  135
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 80%


**思ったこと**
- 1つ1つの意味は理解できるのですが、扱うモジュール数が増えてくるとそれぞれがどう繋がっているのか混乱してきました….
- 時間が解決してくれると思うので、今はひたすらコード書きまくります🔥


<br>
<hr>
<br>


### ■ 93日目: 2024年9月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1838931410989822200)

**今日の進捗  120
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 70%


**思ったこと**
- オプショナルチェーンの使いドコロが理解できました。なるほど、undefinedが渡される可能性もあるからってことね...
- axiosの使い方もついでに覚えれてラッキーでした✌️

<br>
<hr>
<br>

### ■ 92日目: 2024年9月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1838588266834202705)

**今日の進捗  165
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 50%


**思ったこと**
- useContextも少し理解が進みました！この講座だけで新しいこと学びすぎて混乱中ですが、たぶん時間が解決してくれそう。
- styled-components, Atomic Design, useHistory, レンダリング最適化などなど...

<br>
<hr>
<br>

### ■ 91日目: 2024年9月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1838228057221689520)

**今日の進捗  255
- React 上級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版 ---> 40%


**思ったこと**
- じゃけぇさんの講座は本当にわかりやすいです😭初学者がどこで詰まるか正確に理解してくれてる
- Memo, UseCallback, useMemo, styled-components, react-router, 他...
- Chakra UI のレッスンが楽しみすぎます！

<br>
<hr>
<br>

### ■ 90日目: 2024年9月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1837863224009806251)

**今日の進捗  180
- React 中級
  - TypeScript で React Hooks に入門するチュートリアル
  - スキルチェックReactレベル2の内容が理解・使えるか確認


**思ったこと**
- チュートリアルに時間かけすぎた。

<br>
<hr>
<br>


### ■ 89日目: 2024年9月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1837509127263916372)

**今日の進捗  270
- React 中級
  - TypeScript で React Hooks に入門するチュートリアル  ---> 80%
- Ansible
  - 【YouTube】Ansibleを学ぼう

**思ったこと**
- useRef, localStorageが少し分かりかけてきた。あともう一つは今の業務に必要な技術の学習。

<br>
<hr>
<br>


### ■ 88日目: 2024年9月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1837288406445109550)

**今日の進捗  60
- React 中級
  - React Hook Form ライブラリの使い方！フォームのバリデーションを実装しよう【 TypeScript 】
  - TypeScript で React Hooks に入門するチュートリアル  ---> 10%

**思ったこと**
- React Hook Formの記事やっと終わりましたが、機能が多すぎるのでたぶんリファレンス的に使うことになりそうです
- UIコンポーネントと組み合わせれるのは助かる！

<br>
<hr>
<br>


### ■ 87日目: 2024年9月19日　[Twitterリンク](https://x.com/kyohei_IT/status/1836763792505807228)

**今日の進捗  90
- React 中級
  - React Hook Form ライブラリの使い方！フォームのバリデーションを実装しよう【 TypeScript 】 ---> 60%

**思ったこと**
- useFormがすこし理解できた。register関数の第二引数は { required: {xxx: yyy}} の書式の方が見やすい
- オプションとかとんでもない量あるので、頻出のやつから覚えていく

<br>
<hr>
<br>


### ■ 86日目: 2024年9月18日　[Twitterリンク](https://x.com/kyohei_IT/status/1836413155536441509)

**今日の進捗  255
- React 中級
  - ReactでTodoアプリを作ろう

**思ったこと**
- useFormも新しいHookなのかな...？うーむ
- formの入力値がオブジェクトとしてreturnされonSubmitの引数に渡されているみたい
- まぁ基礎的なバリデーションチェックは理解したのでヨシ！

<br>
<hr>
<br>


### ■ 85日目: 2024年9月17日　[Twitterリンク](https://x.com/kyohei_IT/status/1836045192333570391)

**今日の進捗  150
- React 初級
  - React.jsでTODOリストをつくる（初級編）
- React 中級
  - ReactでTodoアプリを作ろう

**思ったこと**
- Todoアプリ初級ではマークアップのセンスのなさに絶望しました😭
- 今日でちょうど1ヶ月。時折不安になりますが、console.logしか書けなかった頃と比べるとだいぶマシになってる気がします

<br>
<hr>
<br>


### ■ 84日目: 2024年9月16日　[Twitterリンク](https://x.com/kyohei_IT/status/1835706972030849377)

**今日の進捗  285
- React 初級
  - React.jsでTODOリストをつくる（初級編） --> 80%

**思ったこと**
- 惜しいとこまで来てる気はしますが、詳細の表示だけ上手くいかず。モーダルでやらない方が良いのかな…
- 初のアウトプットは難しいですが、インプットの何倍も勉強になります！

<br>
<hr>
<br>


### ■ 83日目: 2024年9月15日　[Twitterリンク](https://x.com/kyohei_IT/status/1835340744850309234)

**今日の進捗  300
- React 初級
  - モダンJavaSciptの基礎から始める挫折しないためのReact入門
  - スキルチェックReactレベル1の内容が理解・使えるか確認

**思ったこと**
- useState, props, 関数コンポーネント、といった基本的なところは結構スラスラ書けるようになった。

<br>
<hr>
<br>


### ■ 82日目: 2024年9月14日　[Twitterリンク](https://x.com/kyohei_IT/status/1834963900196175917)

**今日の進捗  315
- React 初級
  - モダンJavaSciptの基礎から始める挫折しないためのReact入門

**思ったこと**
- あまり使うことはないけど、JavaScriptだけでDOM操作を実装する良い復習になった。
- 同じ実装をReactで行い、どれだけラクになったかを検証中

<br>
<hr>
<br>


### ■ 81日目: 2024年9月13日　[Twitterリンク](https://x.com/kyohei_IT/status/1834600907428032825)

**今日の進捗  135
- React 初級
  - モダンJavaSciptの基礎から始める挫折しないためのReact入門  --> 50%


**思ったこと**
- 講座のテーマとしてJSの復習からだったけど、論理演算子以外は簡単過ぎて早送りで済ませた。
- HTML&CSSが久しぶりすぎて良い復習になった。が、本題はReactなのでここは一瞬で終わらせる🔥

<br>
<hr>
<br>


### ■ 80日目: 2024年9月12日　[Twitterリンク](https://x.com/kyohei_IT/status/1834231616539164809)

**今日の進捗  120
- React 初級
  - 【React Hooks入門】完全初心者OK！8種類のHooksを学んでReactの理解を深めよう
  - モダンJavaSciptの基礎から始める挫折しないためのReact入門  --> 5%


**思ったこと**
- 今のメンターサービスのおかげで本当に勉強の仕方が変わった😭
- day54から勉強始めて87.75時間で、VSCode, Git/Github, Chome(Devツール), JavaScript, TypeScript, React初級までできるとは思わなかったです

<br>
<hr>
<br>


### ■ 79日目: 2024年9月11日　[Twitterリンク](https://x.com/kyohei_IT/status/1833883053896384712)

**今日の進捗  135
- React 初級
  - CodeLesson
    - Reactでクリックするたびに色が変わるボタンを作ろう
    - Reactを使ったパスワードジェネレーター
    - Reactでおみくじアプリを作ろう


**思ったこと**
- カリキュラムに沿って簡易的なコーディング。（PW作成, おみくじ, 色が変わるボタンなど）
- カスタムフックの応用的な使い方やイベントハンドラとの組み合わせ方が学びになった！

<br>
<hr>
<br>


### ■ 78日目: 2024年9月10日　[Twitterリンク](https://x.com/kyohei_IT/status/1833511337114406961)

**今日の進捗  165
- React 初級
  - CodeLesson
    - React入門
    - React基礎
    - Reactでカウンターアプリを作ろう
    - Reactで問い合わせフォームを作ろう


**思ったこと**
- 激ムズのTypeScriptではなくJavaScriptで進めているので今のところ順調😭
- useState, useEffect, props, イベントハンドラ, preventDefault, 三項演算子との併用などなど。
- { state && HTML要素} の記法がなぜかお気に入り

<br>
<hr>
<br>


### ■ 77日目: 2024年9月9日　[Twitterリンク](https://x.com/kyohei_IT/status/1833150223197372759)

**今日の進捗  105
- React 初級
  - CodeLesson
    - Reactによく出るJavaScriptをおさらいしよう
    - React入門


**思ったこと**
- {}で関数や変数を呼び出せる、子要素は<></>で囲む、<関数名 />という呼び方もある。
- const [変数, 変数にセットする関数] = useState(初期値)

<br>
<hr>
<br>


### ■ 76日目: 2024年9月8日　[Twitterリンク](https://x.com/kyohei_IT/status/1832800964455403689)

**今日の進捗  270
- React 初級
  - のび太君でもわかるReact入門
  - 【React入門】Youtube


**思ったこと**
- JSXの書式にはまだ慣れないが、動画が分かりやすすぎて7割くらいは理解。
- 仮引数に置く props の書式に ({ xxxx }) => と (props) => の（ {}ありとなし）2種類あった気がしたが、違いが分からず。。
- map関数も() と {} の2パターンあったように見えた

<br>
<hr>
<br>


### ■ 75日目: 2024年9月7日　[Twitterリンク](https://x.com/kyohei_IT/status/1832451518005703105)

**今日の進捗  315
- React 初級
  - 【ESlint/Prettier入門】自動コード整形と構文チェックで開発効率を爆上げしてみよう
  - のび太君でもわかるReact入門
- 環境構築


**思ったこと**
- 参考動画のESlint/Prettierはver8.48.0。現在はv9以上。
- 来年頭にはv10で現在の書式は廃止され、Flat Config形式になるので、Flat Configについて深掘り。

<br>
<hr>
<br>


### ■ 74日目: 2024年9月6日　[Twitterリンク](https://x.com/kyohei_IT/status/1832226631076999556)

**今日の進捗  75
- React 初級
  - 【ESlint/Prettier入門】自動コード整形と構文チェックで開発効率を爆上げしてみよう -> \[30%\]
- 環境構築


**思ったこと**
- 用事があってほぼできなかった。。今日は取り戻す！

<br>
<hr>
<br>


### ■ 73日目: 2024年9月5日　[Twitterリンク](https://x.com/kyohei_IT/status/1831707693125636111)

**今日の進捗  165
- TypeScript　中級
  - TypeScriptおすすめ記事レベル2を読了する
  - 型ドリル\[HARD\]
- React 初級
  - React Developer Toolsのすすめ
  - nodeのpackage管理ツールを導入する（React）
  - 【ESlint/Prettier入門】自動コード整形と構文チェックで開発効率を爆上げしてみよう -> \[20%\]


**思ったこと**
- Typescriptがやっとｵﾜﾀ...
- 最後の最後に自力で　MyPartial<T> = {\[K in keyof T\]?: T\[K\]}　こういう解答も導き出せたので、脳に負荷かけてきてよかった😭

<br>
<hr>
<br>


### ■ 72日目: 2024年9月4日　[Twitterリンク](https://x.com/kyohei_IT/status/1831361401505628658)

**今日の進捗  90
- TypeScript　中級
  - TypeScriptの型演習
  - TypeScriptおすすめ記事レベル2を読了する
    - TypeScript で型定義ファイル( d.ts )がないときの対処法


**思ったこと**
- function<型変数>()~　という書式にやっと慣れてきた。
- 型の応用的な書式のバリエーションがありすぎて何度も挫折しそうになった....
- もう少しでReact入れるから踏ん張ろう！

<br>
<hr>
<br>


### ■ 71日目: 2024年9月3日　[Twitterリンク](https://x.com/kyohei_IT/status/1831115172553093315)

**今日の進捗  75
- TypeScript　中級
  - TypeScriptの型演習


**思ったこと**
- 昨日は新調したM3 Macbook airの初期設定であまり進まず、初めて1項目も進まなかったです。
- そして型演習に苦戦中...Partial一発でできることをジェネリクスで表現した別解ってことなのか...

<br>
<hr>
<br>


### ■ 70日目: 2024年9月2日　[Twitterリンク](https://x.com/kyohei_IT/status/1830630970422432061)

**今日の進捗  210
- TypeScript　中級
  - ゴリ押ししないTypeScript 型ガードの使いどころ5選
  - 使えると便利！TypeScriptのUtilityType入門
  - 最速で学ぶTypeScript
  - TypeScriptの型演習 (0 -> 5%)


**思ったこと**
- ジェネリクスで表記するPromise型というのがあるとのこと。Promise<T>。Promiseが実行された場合の関数の戻り値。
- やっとkeyof と typeof の違いを理解。型に使うのか、定義済みの変数に使うのか、というだけでした。
- 複数の教材で学習すると、別の角度からの気付きもあるし、繰り返したくさん同じ情報に出会うから記憶が強化されてる！って感じがします。
- 最初絶望していたTypeScriptも、少しだけマシになってきました

<br>
<hr>
<br>


### ■ 69日目: 2024年9月1日　[Twitterリンク](https://x.com/kyohei_IT/status/1830281027509739677)

**今日の進捗  300
- TypeScript　初級
  - 型ドリル\[NORMAL\]
- TypeScript　中級
  - ゴリ押ししないTypeScript 型ガードの使いどころ5選
- Python
  - 退屈なことは Pythonにやらせよう：正規表現を使ったパターンマッチ 7.5~7.8
- Ansible
  - 【プレイブックとインベントリ】実践的なプレイプックの利用～Linux構成管理～ P126~137

**思ったこと**
- ユーティリティ型, in, 型ガードみたいに直感的で扱いやすいものもあれば、keyof typeof xxxx みたいな思いもよらない使い方のものもあって、頭の整理にもう少し掛かりそうです。
- 中級終える頃にはもう少しマシになってるはず！

<br>
<hr>
<br>


### ■ 68日目: 2024年8月31日　[Twitterリンク](https://x.com/kyohei_IT/status/1829914858978197747)

**今日の進捗  300
- TypeScript　初級
  - TypeScriptおすすめ記事レベル1を読了する
    - サバイバルTypeScript
  - 型ドリル\[EASY\]
  - 型ドリル\[NORMAL\] 途中
  - TypeScriptを実践で活用したい人向けの基本を徹底解説


**思ったこと**
- TypeScript初学者はみんな悲鳴あげてると思う...
- 「100%理解しよう」と思わないことが大事。時間掛かっていい
- keyof, typeof, Omit, Exclude, Required, Pick, readonly, 他...

<br>
<hr>
<br>


### ■ 67日目: 2024年8月30日　[Twitterリンク](https://x.com/kyohei_IT/status/1829530216559173841)

**今日の進捗  60
- TypeScript　初級
  - 記事
    - TypeScriptの型入門
    - サバイバルTypeScript
    - 5歳娘「パパ、型ガードって何？」


**思ったこと**
- 正直使い方とか使い所は一回度外視して、基本的な型は理解できた。
- ユニオン, プリミティブ, リテラル, void, any, interface, type, 型ガード？, 型アサーション？

<br>
<hr>
<br>


### ■ 66日目: 2024年8月29日　[Twitterリンク](https://x.com/kyohei_IT/status/1829149497446019493)

**今日の進捗  105
- TypeScript　初級
  - CodeLesson
    - 必要最小限のTypescript入門
    - 基本の型を使って、関数の型を理解しよう
    - ゴリ押しTypeScript〜とりあえずエラーを解消してみよう〜


**思ったこと**
- as, !, ? の意味は分かりましたが、慣れるまではどこに使えば良いか迷いそうです。難しくなってきたけど進んでいる証拠なので、今はただ無心で打ち込みます

<br>
<hr>
<br>


### ■ 65日目: 2024年8月28日　[Twitterリンク](https://x.com/kyohei_IT/status/1828793781476536399)

**今日の進捗  120
- TypeScript
  - おすすめ記事2.5本読了


**思ったこと**
- 途中から難しくて読むのがつらくなってきた。このままだと適当に目を走らせて終わりそうな気がしたので、一旦保留にしてもっと基礎のカリキュラムからやることにする。

<br>
<hr>
<br>


### ■ 64日目: 2024年8月27日　[Twitterリンク](https://x.com/kyohei_IT/status/1828447155721470272)

**今日の進捗  180
- Git
  - Gitに関する記事を読んで理解を深める
  - GitHub実践ハンズオン
- ハンズオンReact勉強会


**思ったこと**
- Gitの全カリキュラム終了！まだ基礎が分かっただけなので実務でもっと深まるはず。
- 明日からはTypeScript。かなり良いペース👍

<br>
<hr>
<br>


### ■ 63日目: 2024年8月26日　[Twitterリンク](https://x.com/kyohei_IT/status/1828209371001868576)

**今日の進捗  240
- Git
  - VSCodeでのGitの基本操作まとめ
  - 【Git】自分のアカウントだけでプルリクの練習をしてみよう(pull request)
  - Git,Github 演習課題
- その他
  - 【完全保存版】マークダウン記法


**思ったこと**
- だいぶ理解しやすかったです。gitの苦手意識が少し解消されました

<br>
<hr>
<br>


### ■ 62日目: 2024年8月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1827717107620217047)

**今日の進捗  240
- Git
  - 新しい SSH キーを生成して ssh-agent に追加する
  - VSCodeでGit・GitHubを使う方法を解説する【初心者向き】
  - GitHub環境構築
  - Git Ⅰ(学習コース)
- Javascript初中級、DOMの軽い見直し


**思ったこと**
- Git, SSH, VSCode周りの学習！
- VSCodeでブランチ作成／変更／削除／マージとか学んでるけどCLIでもできるようにしておかないとだな
- なにはともあれ当初2ヶ月で組まれてたカリキュラムを8日で完了。良いペース👍

<br>
<hr>
<br>


### ■ 61日目: 2024年8月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1827366622006538604)

**今日の進捗  300
- JavaScript DOM 初級
  - CodeLesson
    - さまざまな要素の取得方法を学ぼう
    - アコーディオンを作ろう
    - タブメニューを作ろう
    - モーダルウィンドウを作ろう
    - JavaScript CSSスタイルをDOMで操作しよう
    - 要素の属性を自由自在に操ろう

**思ったこと**
- 最速でDOM完了！currentTargetとか細かいところ理解すっとばしてるけどインプットには時間を掛けない、という方針だからOK。
- やっぱ今までの学習スタイルは間違ってた。素直に現役SEの学習方針をマネして良かった

<br>
<hr>
<br>


### ■ 60日目: 2024年8月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1827006898958381532)

**今日の進捗  270
- 開発ツール
  - terminal コマンド編
  - Command Line 基礎編
- Google Chrome
  - 最新のChromeデベロッパーツールの使い方をキャッチアップ
  - Google Chromeデベロッパーツールの基本的な使い方をわかりやすく解説
  - Google Chromeの検証ツール（デベロッパーツール）使い方解説！

- JavaScript DOM 初級
  - CodeLesson
    - JavaScript DOM イベント操作でアクションを実行しよう
    - CodeLesson - JavaScript DOM操作を体験しよう


**思ったこと**
- DOM操作だいぶ慣れてきた！..けどReactあたりのモダンJSだともっと簡潔に書けるらしいのでDOMは歴史をさらう程度。


<br>
<hr>
<br>


### ■ 59日目: 2024年8月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1826642632749293992)

**今日の進捗  405
- Javascript中級
  - 小学生でもわかるasync/await/Promise入門【JavaScript講座】
  - スキルチェックJavaScriptレベル2の内容が理解・使えるか確認
  - Javascriptドリル/NORMAL
  - リファクタドリル[EASY]
- JavaScript DOM操作
  - 【JavaScript基礎・初心者向け】便利なDOM操作をやってみよう！メソッドの紹介 / 簡単な実装例を解説【プログラミング入門】
  - JavaScriptのメソッドを使ってみよう！DOM操作の基本解説 クリックイベントの設定・クラス操作のやり方


**思ったこと**
- awaitをつけてOKな対象が若干怪しいかも。
- Promiseや非同期周りは概ね理解
- DOM操作もほぼOK。querySelectorが少し迷うかな


<br>
<hr>
<br>


### ■ 58日目: 2024年8月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1826272267141300569)

**今日の進捗  330
- Javascript中級
  - CodeLesson
    - Javascriptの非同期処理について学んでいこう
    - JavascriptのPromiseオブジェクト
    - JavaScriptの文字列メソッド
    - JavaScriptのオブジェクト・基礎
    - JavaScriptのオブジェクト・基礎 2
    - JavaScriptのオブジェクト・標準


**思ったこと**
- 初見だとawaitはどこに書くか迷う。基本は非同期関数の前に使用。たとえばfetchとか。
- Promise関数で404などが返ってきてもresolveであることに注意。

<br>
<hr>
<br>


### ■ 57日目: 2024年8月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1826039749599179057)

**今日の進捗  300
- Javascript初級
  - Javascriptドリル/EASY
- CodeLesson Javascript中級
  - 配列メソッド1
  - 配列メソッド2
  - コールバック関数の実践的な使い方を学んでいこう


**思ったこと**
- 昔挫折したコールバック関数、今回はすんなり理解できて良かった。forEach, find, map, filter など
- 他学んだメソッドは substring, splice, slice, setTimeOut, push, shift, unshift, pop, ...　など。

<br>
<hr>
<br>


### ■ 56日目: 2024年8月18日　[Twitterリンク](https://x.com/kyohei_IT/status/1825304179268870638)

**今日の進捗  240

- CodeLesson Javascript
- DAILY CODE
  - Wantedlyから求人情報をスクレイピングするモジュールのカスタマイズ


**思ったこと**
- reを学んだので早速自分のコードに組み込んでみた。動いたのでヨシ！
- 今日は担当メンターとの初回面談だけどJS初級の勉強は課題以外完了

<br>
<hr>
<br>


### ■ 55日目: 2024年8月17日　[Twitterリンク](https://x.com/kyohei_IT/status/1824961563973034202)

**今日の進捗  210

\[新規\]
- codelesson Javascript
  - 入門
  - 条件分岐
  - 繰り返し処理

**思ったこと**
- JSから開始！ロードマップ作る初回面談より前に先に初級を終わらせる！
- Pythonを触ってたおかげで基礎はサクサク進む
- 転職まで6ヶ月という話だったけど短縮してみせる

<br>
<hr>
<br>

### ■ 54日目: 2024年8月16日　[Twitterリンク](https://x.com/kyohei_IT/status/1824465653698531478)

**今日の進捗  60

\[新規\]
- codelesson Javascript入門


\[復習\]
- \[OSS DB\] Ping-t 40問


**思ったこと**
- OSS DB合格！🎉もっと点数低いと思ってたけど結構とれてた
- 残りの時間は申し込んだメンタリングサービスの準備してたので勉強時間は少なめ
- まだ初回面談前だけど先んじてJSから開始！絶対に転職するぞ〜

<br>
<hr>
<br>

### ■ 53日目: 2024年8月15日　[Twitterリンク](https://x.com/kyohei_IT/status/1824100137175802023)

**今日の進捗  90

\[新規\]
- DAILY CODE


\[復習\]
- \[OSS DB\] Ping-t 80問


**思ったこと**
- 明日は資格試験！これで一旦SQLは区切り。今日メンターサービスの方と話したけど良さそうなので申し込む。カリキュラム組むまでの間はnotion整理ととりあえずpythonを深めておくかな

<br>
<hr>
<br>


### ■ 52日目: 2024年8月14日　[Twitterリンク](https://x.com/kyohei_IT/status/1823738270284701765)

**今日の進捗  180

\[新規\]
- DAILY CODE
  - Wantedlyから求人情報をスクレイピングするモジュール

\[復習\]
- \[OSS DB\] Ping-t 120問
- Axross Resipe suumoから物件情報取得

**思ったこと**
- Wantedlyから求人情報を集めるコードを書いてみた！何も見ずに書いたけどノーミスでちゃんと動いて嬉しい
- DBも順調。金曜はOSS DB試験！

<br>
<hr>
<br>


### ■ 51日目: 2024年8月13日　[Twitterリンク](https://x.com/kyohei_IT/status/1823388278432924101)

**今日の進捗  90

\[復習\]
- \[OSS DB\] Ping-t 80問
- Axross Resipe suumoから物件情報取得

**思ったこと**
- 明後日MENTAでメンターに無料相談し、良さそうだったらプラン契約しようと思う
- Webエンジニア転職のためのカリキュラムを作成してそれに沿って学習予定！

<br>
<hr>
<br>


### ■ 50日目: 2024年8月12日　[Twitterリンク](https://x.com/kyohei_IT/status/1823151516607545467)

**今日の進捗  210

\[復習\]
- \[OSS DB\] Ping-t 123問
- Axross Resipe suumoから物件情報取得

**思ったこと**
- 50日間の内、大部分をOSS DBの勉強に費やした...
- 来週くらいからは本格的にフロントやバックエンドの学習も始まるはずなので、day 100までには何かしら成果物を出したい！


<br>
<hr>
<br>


### ■ 49日目: 2024年8月11日　[Twitterリンク](https://x.com/kyohei_IT/status/1822802447297126551)

**今日の進捗  135

\[新規\]
- Axross Resipe suumoから物件情報取得

\[復習\]
- OSS-DB Exam Silver 模擬試験 60問

**思ったこと**
- 正規化は前より理解深まったけどまだ間違う時ある...テーブル設計に関わるので、資格取ったあともしっかり詰めてゆく


<br>
<hr>
<br>


### ■ 48日目: 2024年8月10日　[Twitterリンク](https://x.com/kyohei_IT/status/1822426899316088981)

**今日の進捗  90

\[新規\]
- Axross Resipe suumoから物件情報取得


**思ったこと**
- 好きな住所を入れて座標を取得できるAPIにリクエスト送るためのモジュールを写経
- http://geocoding.jp/api
- with open(), open(), ... と複数行一気に開けることを知った

<br>
<hr>
<br>


### ■ 47日目: 2024年8月9日　[Twitterリンク](https://x.com/kyohei_IT/status/1822073146381635654)

**今日の進捗  270

\[新規\]
- \[OSS DB\] Ping-t
  - 基本的な運用管理作業
  - リレーショナルデータベースに関する一般知識
- OSS-DB Exam Silver 模擬試験 41~60問

\[復習\]
- Axross Resipe suumoから物件情報取得

**思ったこと**
- やっとpingt, 参考書の問題すべて終わった。もう1周ずつやって試験に挑む！

<br>
<hr>
<br>


### ■ 46日目: 2024年8月8日　[Twitterリンク](https://x.com/kyohei_IT/status/1821574493405671586)

**今日の進捗  255

\[新規\]
- \[OSS DB\] Ping-t
  - トランザクションの概念
  - バックアップ方法

\[復習\]
- Axross Resipe suumoから物件情報取得

**思ったこと**
- 昨日は熱が出て1日逃してしまった...昨日より症状軽いのでガッツリ勉強。
- アクティブリコールしながらBeautifulSoup, csvなどの基本的な使い方を理解

<br>
<hr>
<br>


### ■ 45日目: 2024年8月6日　[Twitterリンク](https://x.com/kyohei_IT/status/1820856126826770730)

**今日の進捗  240

\[復習\]
- Axross Resipe suumoから物件情報取得
- DailyCode

**思ったこと**
- 何か成果物を作ろうと思い、賃貸物件探しのAPIを制作開始！
- 特にコンセプトもなく走り出してしまったけど、なんとなく「自動化」や「生成AI」あたりを絡ませられたらなと

<br>
<hr>
<br>


### ■ 44日目: 2024年8月5日　[Twitterリンク](https://x.com/kyohei_IT/status/1820614528998191175)

**今日の進捗  75

\[復習\]
- Udemy FastAPI セクション 38~47

**思ったこと**
- 講座でやってるapp.py（Streamlit）とmain.py（FastAPI）を何も見ずに思い出しながら書いてみた（白紙勉強法）。

<br>
<hr>
<br>

### ■ 43日目: 2024年8月4日　[Twitterリンク](https://x.com/kyohei_IT/status/1820104528186015762)

**今日の進捗  270

\[新規\]
- \[OSS DB\] Ping-t
  - SQLコマンド（8章)
- Axross Resipe suumoから物件情報取得

**思ったこと**
- やっと一番難関のpingt177問が終わった...
- trigger, sequence, schema, function, procedure, etc...がすごく覚えづらかったけど問題を繰り返すとやっぱ身に付く😄

<br>
<hr>
<br>


### ■ 42日目: 2024年8月3日　[Twitterリンク](https://x.com/kyohei_IT/status/1819750257296879781)

**今日の進捗  210

\[新規\]
- Axross Resipe suumoから物件情報取得
- \[OSS DB\] Ping-t
  - SQLコマンド（8章)

**思ったこと**
- 作りたいものが浮かばない内はひたすら写経しようと思い、Axross Resipeで良い題材を見つけて勉強。
- BeautifulSoupの基礎的な使い方がわかった。find, find_all, parserが基本みたい

<br>
<hr>
<br>


### ■ 41日目: 2024年8月2日　[Twitterリンク](https://x.com/kyohei_IT/status/1819550841172644317)

**今日の進捗  60

\[新規\]
- 要件定義のしっかりわかる教科書
- Axross Recipe

**思ったこと**
- 自社で自動化システムの開発をやる流れになっているので、要件定義とchatgptについて少しずつ学習。

<br>
<hr>
<br>


### ■ 40日目: 2024年8月1日　[Twitterリンク](https://x.com/kyohei_IT/status/1819027458731200993)

**今日の進捗  120

\[新規\]
- \[OSS DB\] Ping-t
  - SQLコマンド（8章)


**思ったこと**
- 結合には重複するすべての列を結合する natural と、重複する特定の列のみを結合する using があるみたい。
- あと1,2個前の問題を何も見ずに思い出しながら進める(=アクティブリコール)と記憶の定着度増した気がする

<br>
<hr>
<br>


### ■ 39日目: 2024年7月31日　[Twitterリンク](https://x.com/kyohei_IT/status/1818660386570383501)

**今日の進捗  120

\[新規\]
- Udemy FastAPI セクション 7: 51~52

\[復習\]
- Udemy FastAPI セクション 7: 46~47

**思ったこと**


<br>
<hr>
<br>

### ■ 38日目: 2024年7月30日　[Twitterリンク](https://x.com/kyohei_IT/status/1818421024821854391)

**今日の進捗  150

\[新規\]
- Udemy FastAPI セクション 7: 49~50

\[復習\]
- Udemy FastAPI セクション 7: 41~45,48
- ゼロから始めるデータベース操作 5, 6章
  - view
  - サブクエリ, スカラ・サブクエリ, 相関サブクエリ
  - 組み込み関数
  - like, between, in, not in 

**思ったこと**
- ORMというDBMS操作ツールの概要部分を学習✌️

<br>
<hr>
<br>


### ■ 37日目: 2024年7月29日　[Twitterリンク](https://x.com/kyohei_IT/status/1817947223973560599)

**今日の進捗  120

\[新規\]
- Udemy FastAPI セクション 7


**思ったこと**
- input系の関数名はたいていst.xxxx_input()。st.number_ , http://st.date_ , st.text_ など。
- datetimeの使い方も結構覚えれた。
- http://datetime.date.xxxx, datetime.datetime(year=xx, month=xx, ....).isoformat()


<br>
<hr>
<br>


### ■ 36日目: 2024年7月28日　[Twitterリンク](https://x.com/kyohei_IT/status/1817574464206581763)

**今日の進捗  180

\[新規\]
- Udemy FastAPI セクション 7
- Pythonプロフェッショナル大全


**思ったこと**
- streamlitのsidebar, selectbox, number_input, text_input, ...などを使ってfastapiとの連携の仕方を学んだ。


<br>
<hr>
<br>


### ■ 35日目: 2024年7月27日　[Twitterリンク](https://x.com/kyohei_IT/status/1817227617650802895)

**今日の進捗  180

\[新規\]
- Udemy FastAPI セクション 6, 7


**思ったこと**
- importエラーやpylint, flake8の警告解消の調査、学習方法の見直しにほぼ1日を費やした。
- 今まではNotionに書籍を丸ごとコピペして体裁整えて...と相当時間をムダにしてた。
- Notion x Goodnotesのおかげで数十時間の節約になりそう😢


<br>
<hr>
<br>


### ■ 34日目: 2024年7月26日　[Twitterリンク](https://x.com/kyohei_IT/status/1817025528635023407)

**今日の進捗  75

\[新規\]
- Udemy FastAPI セクション 6


<br>
<hr>
<br>


### ■ 33日目: 2024年7月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1816495271620030840)

**今日の進捗  90

\[新規\]
- コーディング


**思ったこと**
- pandasとmatplotlibでヒストグラフを書いた。皆ここからどうやって新たなプログラムに発展させてるんだろう。


<br>
<hr>
<br>

### ■ 32日目: 2024年7月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1816132925580365930)

**今日の進捗  180

\[新規\]
- コーディング
- \[OSS DB\] Ping-t
  - SQLコマンド（8章)

**思ったこと**
- 制約は何個も設定できたのか。
- uniqueは末尾に複数列指定可。
- 外部キー制約も慣れた
- cursor文にも慣れたけど試験範囲外のような気が...
- あとこれから毎日pythonで成果物を作る。初心者なので小さなプログラムから


<br>
<hr>
<br>


### ■ 31日目: 2024年7月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1815766073360412873)

**今日の進捗  180

\[新規\]
- \[OSS DB\] Ping-t
  - SQLコマンド（8章)


**思ったこと**
- トリガーとか制約、関数、マテビュー、プリペアド文？、テーブルスペース、パーティショニングとかをかなり応用した問題が多い。難しい・・


<br>
<hr>
<br>


### ■ 30日目: 2024年7月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1815421088324784608)

**今日の進捗  300

\[新規\]
- \[OSS DB\] Ping-t
  - 標準付属ツールの使い方(4章)
  - 設定ファイル(5章)
  - 組み込み関数(9章)


**思ったこと**
- 各パラメータの反映タイミングは、とりあえず再起動のものだけ暗記してしまえば、ほとんど答えられそう
- alter systemコマンド、postgresql.auto.confは初めて知った
- sql系の問題はほぼ100%の正解率


<br>
<hr>
<br>


### ■ 29日目: 2024年7月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1815037809012654100)

**今日の進捗  180

\[新規\]
- OSS DB Silver 11章 21~40問
- [OSS DB] Ping-t
  - OSS-DBの一般的特徴(1章)
  - インストール方法(3章)

**思ったこと**
- OSS DBは相当細かいところばかり聞いてくるからすごく助かる。
- インストール周りは結構わかった。


<br>
<hr>
<br>


### ■ 28日目: 2024年7月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1814704152884486166)

**今日の進捗  300

\[新規\]
- OSS DB Silver 11章 11~20問

\[復習\]
- Paiza 新・SQL入門編04,05
- ゼロから始めるデータベース操作 3, 4, 5, 6, 7章
  - group by, having, order by
  - view
  - サブクエリ, スカラ・サブクエリ, 相関サブクエリ
  - 集合演算, case式
  - 内部結合、外部結合
- プロになるためのWeb技術入門 6.1~6.2章

**思ったこと**
- サブクエリはfrom句で使う。スカラサブクエリは基本どこでも使える。相関サブクエリもどこでも？select句, where句での使い方は理解した。グループ単位で使うので基本的にgroup by と併用。
- case式もどこでも使える？select句に使ったり、集約関数の中での使い方は理解した。
- view, 多段view, viewの更新可否についても理解。distinct, group by, having を使っておらず、fromに指定するテーブルが1つの場合に限りinsertができる。


<br>
<hr>
<br>

### ■ 27日目: 2024年7月19日　[Twitterリンク](https://x.com/kyohei_IT/status/1814312353410040299)

**今日の進捗  75

\[新規\]
- Udemy FastAPI セクション 4

**思ったこと**
- 昨日1日空いてしまった...
- Detaはうまく使えなかったけど、Herokuというサービスもあるのか。後々はAWSだけどとりあえず練習で使おう

<br>
<hr>
<br>



### ■ 26日目: 2024年7月17日　[Twitterリンク](https://x.com/kyohei_IT/status/1813594734738514001)

**今日の進捗  120

\[新規\]
- Udemy FastAPI セクション 4
- OSS DB Silver 11章


<br>
<hr>
<br>


### ■ 25日目: 2024年7月16日　[Twitterリンク](https://x.com/kyohei_IT/status/1813358119793381523)

**今日の進捗  120

\[新規\]
- Udemy FastAPI セクション 4



<br>
<hr>
<br>


### ■ 24日目: 2024年7月15日　[Twitterリンク](https://x.com/kyohei_IT/status/1812872149629300879)

**今日の進捗  330

\[新規\]
- Udemy FastAPI セクション 4
- Paiza 新・SQL入門編05, 06

\[復習\]
- ゼロから始めるデータベース操作 6, 7章
  - 集合演算
  - 内部結合、外部結合
- OSS DB Silver 3, 4章
  - テンプレートデータベース
  - initdb
  - pg_ctl, psql, createuser, createdb, dropuser, dropdb, pg_controldata, pg_isready, pg_resetwal, pg_config
  - postgresql.conf
  - pg_hba.conf

**思ったこと**
- パスパラメータ, 型ヒントによるフィルタリングなど、基本的な使い方の半分は理解できた。思ってた以上にシンプルだった。
- 集合演算と結合が結構慣れてきた。



<br>
<hr>
<br>


### ■ 23日目: 2024年7月14日　[Twitterリンク](https://x.com/kyohei_IT/status/1812508520497246543)

**今日の進捗  165

\[新規\]
- Paiza 新・SQL入門編04ドリル
- Udemy FastAPI セクション 4


**思ったこと**
- inner join, left/right outer join がわかった!外部結合は左を全部含むか右を全部含むかの違いね。



<br>
<hr>
<br>


### ■ 22日目: 2024年7月13日　[Twitterリンク](https://x.com/kyohei_IT/status/1811791159691514273)

**今日の進捗  195

\[新規\]
- Udemy FastAPI セクション 1, 2, 3

\[復習\]
- ゼロから始めるデータベース操作 1, 2, 3, 6章


<br>
<hr>
<br>


### ■ 21日目: 2024年7月12日　[Twitterリンク](https://x.com/kyohei_IT/status/1811791159691514273)

**今日の進捗  60

\[新規\]
- Paiza 新・SQL入門編03ドリル

\[復習\]
- Ansible実践ガイド 3章
  - インベントリの基礎
  - プレイブックの基礎
- ゼロから始めるデータベース操作 4章

**思ったこと**
- 問題文の日本語が独特で解けないのは悔しい
- 基礎〜サブクエリまでは粗方覚えれた。あとは反復。SQLはクエリ打てば打つほど習熟度が上がってシンプル


<br>
<hr>
<br>


### ■ 20日目: 2024年7月11日　[Twitterリンク](https://x.com/kyohei_IT/status/1811418589259591980)

**今日の進捗  195

\[復習\]
- ゼロから始めるデータベース操作 1, 2, 3, 4, 5章
  - create／alter／drop table, select, from, where, group by, having, order by, limit
  - distinct
  - 集約関数
  - view
  - サブクエリ, スカラ・サブクエリ, 相関サブクエリ


**思ったこと**
- かなりSQLわかってきた！前やってた時は全くだったのに、成長を実感している.
- あとOSSDB取得まで30%ほど


<br>
<hr>
<br>


### ■ 19日目: 2024年7月10日　[Twitterリンク](https://x.com/kyohei_IT/status/1811061401739481335)

**今日の進捗  240

\[新規\]
- Paiza 新・SQL入門編02ドリル

\[復習\]
- Ansible実践ガイド 3章 実践的なプレイブック利用
- OSS DB Silver 4, 5, 6章
  - pg_ctl, psql, createuser, createdb, dropuser, dropdb, pg_controldata, pg_isready, pg_resetwal, pg_config
  - postgresql.conf
  - pg_hba.conf
  - set文
  - バックアップ／リストア
- ゼロから始めるデータベース操作 1, 2, 3章
  - create／alter／drop table, select, from, where, group by, having, order by, limit
  - 集約関数


**思ったこと**
- pandasのgroupbyを学んだおかげで、sqlのgroup by句がかなり理解できた
- まだ写経ばかりでゼロからプレイブックは作れてないけど、それでも理解したり思い出しながらやることで身についているのがわかる。
- ただ、まだ外部ファイルの読み込みがよく分かってない


<br>
<hr>
<br>


### ■ 18日目: 2024年7月9日　[Twitterリンク](https://x.com/kyohei_IT/status/1810706760673685966)

**今日の進捗  165

\[復習\]
- Paiza：【最安値】最安値を達成するには 4
- Paiza：【連続列】最長減少連続部分列
- OSS DB Silver 1, 2章
  - PostgreSQLのライセンス
  - データモデル
  - ER図
  - データベース設計（概念データモデル, 論理データモデル）
  - 正規化
- Ansible実践ガイド 3章 実践的なプレイブック利用

**思ったこと**
- 昨日旅行から帰ってから1時間やろうと思ったけど、疲れすぎててすぐ寝てしまった。ただ、1日休んでしまうのはまだOKらしい。2日空けるのはNGとのこと。当面旅行とかないから、ここから絶対毎日やる！


<br>
<hr>
<br>


### ■ 17日目: 2024年7月7日　[Twitterリンク](https://x.com/kyohei_IT/status/1809964721342390473)

**今日の進捗  60

\[新規\]
- Ansible実践ガイド 3章 実践的なプレイブック利用

\[復習\]
- OSS DB Silver 3, 5章
  - テンプレートデータベース
  - initdb
  - postgresql.conf
  - pg_hba.conf
  - set文

**思ったこと**
- 旅行だけど頑張った...
- 先週の勉強時間より75m増えた！ただ、週20hは絶対超えたいのでもっとスキマ時間ムダにしていないか見直す。もちろんただの時間稼ぎではなく質の高い勉強を。

今週の勉強時間：16h


<br>
<hr>
<br>


### ■ 16日目: 2024年7月6日　[Twitterリンク](https://x.com/kyohei_IT/status/1809622687351972326)

**今日の進捗  240

\[新規\]
- プロになるためのWeb技術入門 6.1~6.3章
- Ansible実践ガイド 3章 実践的なプレイブック利用

\[復習\]
- OSS DB Silver 4, 5, 10章
  - pg_ctl, psql, createuser, createdb, dropuser, dropdb, pg_controldata, pg_isready, pg_resetwal, pg_config
  - postgresql.conf
  - pg_hba.conf
  - set文
  - トランザクション制御コマンド
  - トランザクション分離性
  - ロック



**思ったこと**
- やっぱり反復が大事だったのか。今までは一度インプットして終わりの学習方法だったから、理解度が低かったけど、1／3／7／30日後の4回復習始めてから定着率良い感じ
- 分離性もイメージはついてきた。直列化異常だけまだ理解できてない。
- 排他ロック中は別の処理から排他/共有ロックを取得できないはず。ということはデッドロックとは共有ロック同士が掛かりあってる状態？


<br>
<hr>
<br>


### ■ 15日目: 2024年7月5日　[Twitterリンク](https://x.com/kyohei_IT/status/1809241665028460584)

**今日の進捗  165

\[復習\]
- Progate Professional チームの勝率とグッズ売り上げの相関をグラフで表そう
  - pandas(groupby, get_group, merge, concat), matplotlib.pyplot(plt.scatter)
- Ansible実践ガイド 3章 実践的なプレイブック利用
- OSS DB Silver 1, 2, 3, 9章
  - PostgreSQLのライセンス
  - データモデル
  - ER図
  - データベース設計（概念データモデル, 論理データモデル）
  - 正規化
  - データベースクラスタ概要
  - データベース概要
  - テンプレートデータベース
  - initdb
  - 算術関数
  - 文字列関数
  - 時刻関数
  - データ型変換関数
  - similar to
  - 算術演算子
  - 文字列演算子
  - 日付／時刻演算子


**思ったこと**
- 属性Xが決まれば属性Yが決まるので、YはXに関数従属するのはわかるけど、それであればYが決まればXも決まるのでXはYに関数従属する、と考えてはいけないのかな？
- 2回目の復習でやっと、完全関数従属の意味がわかった。けどやっぱ推移関数従属とボイスコッド正規形がわからない・・。回数を追うごとに理解度増してるので次回に期待。


<br>
<hr>
<br>


### ■ 14日目: 2024年7月4日　[Twitterリンク](https://x.com/kyohei_IT/status/1809008767570489510)

**今日の進捗  60

\[復習\]
- Progate Professional 月ごとの売上を集計して棒グラフで表そう
  - to_datetime, dt.strftime, groupby, get_group, sum, count, size


**思ったこと**
- groupby, get_groupで引数を複数指定できた。表が今どういう感じになってるかを想像しながら（あるいは確認しながら）進めると分かりやすい。
- 予定があったので、1時間しかできなかった...次の日勉強のために午後休とったので取り返す


<br>
<hr>
<br>


### ■ 13日目: 2024年7月3日　[Twitterリンク](https://x.com/kyohei_IT/status/1808523822485905904)

**今日の進捗  120

\[新規\]
- Ansible実践ガイド 3章 実践的なプレイブック利用

\[復習\]
- Progate Professional チームの勝率とグッズ売り上げの相関をグラフで表そう
- Progate Professional ユーザー属性ごとの来店回数をグラフ化しよう
  - merge, concat, scatter, hist, subplot, figure, floor, ceil, round


**思ったこと**
- タイマー使って勉強を計測し始めてから、かなり効率上がった。
- Ansibleの知識ももちろん重要だけど、Ansibleを実行する対象についての前提知識がないと、活用しきれないと思った。たとえばロケールやキーマップとか、Linuxの基礎知識を知らなければ、Ansibleの何のモジュールが最適か、どうプレイブックを作るべきかがイメージできないと思う。
- AnsibleでREST叩く場合って、changedしか出ない？から、冪等性もなにもないのかな？となるとエラーハンドリングにより気を使った方が良いのかも。
- pandas, matplotlib, numpyのメソッド結構覚えてた。エビングハウスの忘却曲線に沿った復習スケジュールに変えてから、記憶の定着率かなりよくなったかも。今までいかにインプットだけで終わっていたかがよくわかる。


<br>
<hr>
<br>


### ■ 12日目: 2024年7月2日　[Twitterリンク](https://x.com/kyohei_IT/status/1808157851371831483)

**今日の進捗  180

\[復習\]
- OSS DB Silver 3, 10章
  - トランザクション制御コマンド
  - トランザクション分離性
  - ロック
  - PostgreSQLの導入
  - データベースクラスタ概要
  - データベース概要
  - テンプレートデータベース
  - initdb
- Progate Professional チームの勝率とグッズ売り上げの相関をグラフで表そう
  - matplotlib(散布図)
  - pandas(データフレームの結合)
- Ansible実践ガイド 3章 実践的なプレイブック利用


**思ったこと**
- データベースクライアント、という単語をよく見かけるけど、そうか。アプリケーションとかのことか。
- Ansibleはしっかりインプットしたから、実践編がかなりちょうど良いアウトプットになってる。


<br>
<hr>
<br>


### ■ 11日目: 2024年7月1日　[Twitterリンク](https://x.com/kyohei_IT/status/1807792101662609525)

**今日の進捗  135

\[復習\]
- OSS DB Silver 1, 2, 9章
  - PostgreSQLのライセンス
  - データモデル
  - ER図
  - データベース設計（概念データモデル, 論理データモデル）
  - 正規化
  - 算術関数
  - 文字列関数
  - 時刻関数
  - データ型変換関数
  - similar to
  - 算術演算子
  - 文字列演算子
  - 日付／時刻演算子


**思ったこと**
- 対象世界からEntityを取り出すのも難しい。でもなるほど。Entityはテーブル、Entityが持つ属性が列名になるのか。
- Entityを取り出すのはなんとかできそう。でもRelationshipと多重度は慣れが必要な気がする。どうやって習熟度を上げるか。
- 「第二正規形の定義は、第一正規形であって、かつ、関係中のすべての非キー属性が候補キーに完全関数従属であること」とあるが、ここで言う候補キーは主キーでなくても良いのか


<br>
<hr>
<br>


### ■ 10日目: 2024年6月30日　[Twitterリンク](https://x.com/kyohei_IT/status/1807439393118171239)

**今日の進捗  195

\[復習\]
- OSS DB Silver 1, 2章
  - PostgreSQLのライセンス
  - データモデル
  - ER図
  - データベース設計（概念データモデル, 論理データモデル）
  - 正規化

\[新規\]
- OSS DB Silver 10章
  - トランザクションの制御コマンド（BEGIN／START, TRANSACTION, COMMIT, ROLLBACK, END, ABORT, SAVEPOINT）
  - トランザクションの分離性
  - ロック
- Ansible実践ガイド 3章
  - ロール
  - タスクの実行順序
  - 外部ファイルの読み込み
  - プレイブック作成の手引き


**思ったこと**
- 別PRJでDBを深堀りする際、対象世界→概念データモデル→論理データモデルに変換できるように子タスク切ろう。
- 正規化が難しい。それなりに理解できたような気はする。実際に設計してみて始めて感覚掴めそう。
- BSDライセンス。ソースコードの開示も自由。参考書にはなかったけど、つまり非コピーレフト型かな？
- 他タスクや休憩時間を含めず勉強時間を細かく計測すると意外と少ないな。20h超えてないのはヤバい...

今週の学習時間 14.75

<br>
<hr>
<br>


### ■ 9日目: 2024年6月29日　[Twitterリンク](https://x.com/kyohei_IT/status/1807082951190212701)

**今日の進捗  195

\[復習\]
- OSS DB Silver 8章
  - トリガ
  - ストアドファンクション
  - レプリケーション
- Progate Professional ユーザー属性ごとの来店回数をグラフ化しよう
- Paiza 3項間漸化式 2
- プロになるためのWeb技術入門 5章
- Ansible プレイブックの基礎 P102~112
- OSS DB Silver 9章
  - 算術関数
  - 時刻関数
  - 変換関数
  - SIMILAR TO
  - 算術演算子
  - 文字列演算子
  - 日付／時刻演算子

**思ったこと**
- トリガの仕組みはZabbixやってたのでわかりやすかった。WebアプリケーションからSQL実行する分の負荷を減らすために、DB側で関数仕掛けておく、みたいな使い方しそう。
- changed_when／failed_whenは実行結果の戻り値を利用して、そのタスクの結果としてchanged, failedを付与する。戻り値を使うので、必然的にレジスタ変数と組み合わせる。

<br>
<hr>
<br>

### ■ 8日目: 2024年6月28日　[Twitterリンク](https://x.com/kyohei_IT/status/1806714431461793915)

**今日の進捗  60

\[復習\]
- OSS DB Silver 8章
  - テーブルスペース
  - limit, offset句
  - マテリアライズドビュー
  - ANY
  - 関数とストアドプロシージャ

**思ったこと**
- 昨日今日と仕事後、すぐ予定があって全くできなかった。。

<br>
<hr>
<br>


### ■ 7日目: 2024年6月26日　[Twitterリンク](https://x.com/kyohei_IT/status/1805976117360390461)

**今日の進捗  180

\[復習\]
- Progate Professional ユーザー属性ごとの来店回数をグラフ化しよう
- OSS DB Silver 8章
  - データ型
  - 制約
  - スキーマ
  - シーケンス
  - alter table文（add, drop, rename to, owner to, rename column)
  - インデックス

**思ったこと**
- 8章長すぎるから復習が1日で終わらない・・。ただ、SQL文は結構覚えれた。復習した後に、その項目でやったことを何も見ずに思い出すのが、結構良いアウトプットになってる。
- この遅れは明日取り戻す。夜中まで勉強していて睡眠不足が続き、集中力が落ちて本末転倒になっていたので、今日は思い切ってしっかり寝る。明日はテーブルスペースから。
- その時わからなくても、時間経ってある時急に腹落ちする時がある。だからこそ1回ですべて覚えようとしないのがコツ。

<br>
<hr>
<br>


### ■ 6日目: 2024年6月25日　[Twitterリンク](https://x.com/kyohei_IT/status/1805615159958028555)

**今日の進捗  210

- Progate Professional ユーザー属性ごとの来店回数をグラフ化しよう
- OSS DB Silver 9章
  - 算術関数
  - 文字列関数
  - 時刻関数
  - データ型変換関数
  - similar to
  - 算術演算子
  - 文字列演算子
  - 日付／時刻演算子
  - トランザクション（途中まで）

**思ったこと**
- 9章終わった！10章終わったらあとはひたすら復習と問題集のみ。全体の進捗率は5.5割くらいかも。

<br>
<hr>
<br>


### ■ 5日目: 2024年6月24日　[Twitterリンク](https://x.com/kyohei_IT/status/1805263307349303481)

**今日の進捗  240

\[復習\]
- プロになるためのWeb技術入門 5章P239~317　
- OSS DB Silver
  - シーケンス
  - alter table文（add, drop, rename to, owner to, rename column)
  - インデックス
  - テーブルスペース
  - limit, offset句
  - マテリアライズドビュー
  - ストアドプロシージャ
  - ストアドファンクション
  - トリガ
  - レプリケーション
- Progate Professional ユーザー属性ごとの来店回数をグラフ化しよう 途中まで

**思ったこと**
- インデックス, テーブルスペース, マテリアライズドビュー, ストアド*, トリガの作成と設定は分かった。その上でどのように使うかは、今後別の参考書で補塡する必要がありそう。
- ロジカルレプリケーションだけ最後上手くいかなかったので次回再トライ

<br>
<hr>
<br>

### ■ 4日目: 2024年6月23日　[Twitterリンク](https://x.com/kyohei_IT/status/1804883948562256263)

**今日の進捗  240

\[復習\]
- Progate Professional：売上推移をグラフ化しよう（2-4,2-5）
- Ansible実践ガイド の プレイブックの基礎 P82~112
- OSS DB Silver
  - データ型（数値型, 文字列型, バイナリ型, 日付/時刻型, 論理値, 連番型, OID, 配列型, JSON型, NULL型）
  - 制約（NOT NULL制約, チェック制約, ドメイン制約, 外部キー制約, 識別子制約, 主キー制約）
  - スキーマ（スキーマ作成/削除、スキーマにテーブル作成、スキーマ検索パス設定）

**思ったこと**
- Pandas, matplotlib.pyplot はだいぶ使い方慣れてきた。
- 復習の際、まず章の名前や大項目/小項目名だけ見て、そこで説明されていたことを何も見ずに思い出そうとすると、かなり良いアウトプットになる。
- データ型、制約はすべて理解できた。スキーマは若干怪しい。テーブルなどのオブジェクトは「データベース」にあると思ってたけど、厳密に言うと「データベースの中にあるスキーマの中にある」という理解で良いのかな？

<br>
<hr>
<br>

### ■ 3日目: 2024年6月22日　[Twitterリンク](https://x.com/kyohei_IT/status/1804680045635781048)

**今日の進捗  240
- OSS DB Silver
  - インデックス（マルチカラムインデックス、関数インデックス/式インデックス、部分インデックス）
  - トリガ
  - スキーマ
  - 関数とプロシージャ
  - テーブルスペース
  - マテリアライズドビュー
  - レプリケーション
- プロになるためのWeb技術入門 5章P239~317　復習

**思ったこと**
- OSS DB参考書の一番長かった8章が一旦終わった・・といいつつもこれから数日に分けて復習していくけど、山場超えた感あって嬉しい。
- ApacheとTomcatの連携部分の理解が深まった！httpd.confへのworker指定やmod_jkなど。pythonとかで構築する場合のアプリケーションサーバにも、TomcatやJavaVM必要なのかな？素人過ぎて分からない…調べてみよう。

<br>
<hr>
<br>

### ■ 2日目: 2024年6月21日　[Twitterリンク](https://x.com/kyohei_IT/status/1804085282788249624)

**今日の進捗  300
- プロになるためのWeb技術入門 5章P239~317
- OSS DB Silver
  - 制約（外部キー、チェック制約、ドメイン制約、識別子制約）
  - テーブル定義変更（テーブル名/所有者の変更、列の追加/変更/削除）
  - パーティショニング
  - シーケンス
  - インデックス（途中まで）

**思ったこと**
- Web三層構成と連携の仕方はためになった。基礎知識はあったし、内容も易しめだったので、理解できない部分はなかった
- DBはあまり理解しきれなかった。ただ、ここから複数回復習していくので問題なし
- 折角有休にしたのに5時間弱しか勉強できなかった。

<br>
<hr>
<br>

### ■ 1日目: 2024年6月20日　[Twitterリンク](https://x.com/kyohei_IT/status/1803960105978990795)

**今日の進捗  60
- UDA式30音練習帳復習（DAY1~5）
- Ansible実践ガイド の プレイブックの基礎復習
  - changed_when
  - failed_when
  - Fail-Fast
  - ignore_errors

**思ったこと**
- 今日はあまり勉強時間取れなかった・・
- 英語の勉強も含めても良いのかどうか
- changed_when, failed_whenは実行結果から判断、という文脈は理解できたけど、その後どういう動きをとるのかが分かりづらかった。実際作り始めてから理解深めれば良いと思う

<br>
<hr>
<br>

### ■ 0日目: 2024年6月19日　[Twitterリンク](https://x.com/kyohei_IT/status/1803414450508275942)

**今日の進捗  180
- GitHub準備（\#100DaysOfCode）
- Progate Professional の Pythonによるデータ分析入門復習
  - 「売り上げ推移をグラフ化しよう」
- Ansible実践ガイド の プレイブックの基礎復習
  - 変数の定義
  - 変数の参照
  - 変数の優先順位
  - 条件分岐
- OSS DB[7章] 基本的な運用管理 復習
  - ユーザー管理
  - 情報スキーマ
  - システムカタログ
  - VACUUM, ANALYZE

**思ったこと**
- 今日から \#100DaysOfCode を開始。折角なのでGitHubに毎日の学習ログを残そうと思う

<br>
<hr>
<br>

### 逃した日
- 6月27日
- 7月8日
- 7月18日
- 8月7日
- 8月19日
