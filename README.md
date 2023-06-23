■ サービス概要
ダイエットをしたい！でも、難しいことはわからないし、めんどくさいことはやりたくない人に
簡単な登録だけですぐに使える
コンビニダイエット食おすすめサービスです。

■ユーザーが抱える課題
- 気軽にダイエットをしたいが、何を食べたらいいかわからない
- ダイエットについて勉強・調べる・記録する等の面倒なことは最小限にしたい

■課題に対する仮説
- 栄養学について十分な知識がない
  1. 何を食べたらいいかわからない
  2. 勉強しようにも情報が多すぎて、何を勉強したらいいかわからない

- ダイエットの過程で面倒な作業が多い
  1. ダイエットについて勉強することそのものが面倒
  2. 食べたものの栄養素を調べることが面倒
  3. 食事の記録をつけることが面倒

■解決方法
- ダイエットに適したコンビニ食を提案することによって、ユーザー調べたり勉強する手間を省きダイエットのハードルを下げる
  - ユーザーの登録情報に合わせて、登録されているコンビに食品の中から、ダイエットに適した食品を提案する
  - 脂質制限、糖質制限、カロリー制限などのダイエット法にも対応した食品を提案する（ダイエット法はユーザーは任意登録）
  - お気に入り機能をつけて、気に入った食品へ簡単にアクセスできるようにする
  - レビュー機能をつけて、ダイエット仲間と情報交換できるようにする

■メインのターゲットユーザー
面倒なことは省いてとにかくダイエットを始めたい人、コンビニで食事をすることが多い人

■実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
- ゲストユーザー機能
  - 食品の閲覧、検索（マルチ検索・オートコンプリート）
- 登録中ユーザー機能
  - ログイン、ログアウト
  - ユーザー登録、編集、削除
  - 食品の閲覧、検索（マルチ検索・オートコンプリート）、お気に入り登録、レコメンド機能
  - レビューの登録(星5段階評価）、編集、削除
- 管理ユーザー機能
  - 登録ユーザーの検索、一覧、詳細、編集、削除
  - ダイエット方法に合わせた栄養素設定、編集
  - 食品の一覧、詳細、編集、削除
  - レビューの一覧、詳細、編集、削除

■なぜこのサービスを作りたいのか？
前職でパーソナルトレーナーをしていたときから「何を食べたらいいですか？」という質問をよく受けていたことと、「食事の記録をつける」ことに挫折する人をたくさん見てきました。
一つの結論として、「なんらかのダイエット法を実践するまでに、情報を調べたり、勉強したりすることが面倒で挫折してしまう」というところに辿り着きました。
そこで、とにかくダイエットに関する面倒なことを排除し、ダイエットの始めの一歩になるようなサービスを作りたいと思いました。

■スケジュール
1. 企画（アイデア企画・技術調査）：6/21〆切
2. 設計（README作成・画面遷移図作成・ER図作成）：6/24 〆切
3. 機能実装：6/24〜8/24
4. MVPリリース：8/24〆切
5. 本リリース：8/24

■技術選定
- Rails7
- postgresql
- JavaScript
- jQuery
- Bootstrap
- heroku
- Stimulus Autocomplete
- Amazon Personalize
- スクレイピング

以下、今後チャレンジしたい機能・技術。（今回はスケジュール的にも技術難しいと思ってはずしています。）
■追加検討機能
- 通知機能(新着商品情報)

■追加検討技術
- React (UX向上)
- AWS (インフラ構築)
- LINE BOT（アプリそのものをLINEで使えるようにする）

■画面遷移図
https://www.figma.com/file/tOKDkThJh2jaTazg5U1DR5/korekue?type=design&node-id=0-1&mode=design&t=yhJW4wVLRdCEGE8w-0