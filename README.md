# 🍅サービス名🥑
### AIお料理ネーミング

## 🥕サービス概要
「**名もなき日常料理**」に、名前をつけるアプリです。<br>

※「名もなき日常料理」とは、冷蔵庫の余り物やアドリブで作った料理など、特定のレシピに従わない独自の料理を指します。

## 🥕メインのターゲットユーザー
- 余り物で料理を作るのが得意な方
- 「いつものアレ」に名前をつけたい方
- SNSで料理をシェアしている方
- 家族や友人との会話のネタにしたい方

## 🥕ユーザーが抱える問題
- 余り物で美味しい料理が作れても、名前がないため、料理の特徴や味を上手く伝えられずに困る
- 料理に名前がないことで、過去に作った料理や食べた料理を思い出しにくくなる
- 「名もなき日常料理」に適切な名前が付けられず、SNSでシェアしにくい
- 他人に自分の得意料理を説明する際に、名前がなくて困ることがある

## 🥕解決方法
- アプリが自動的に「名もなき日常料理」にユニークで面白い名前をつける機能を提供
- 付けられた名前を使って、SNSでシェアしやすくする
- 話題性のある名前をつけることで、家族や友人との会話のネタにもなる

## 🥕実装予定の機能 (✋そのユーザー特有の操作は"太字"にしています)
⬜ **未ログインユーザー**

- [x] ヘッダー
  - サービス名のロゴから、トップページ(料理名生成画面)へ遷移できる
  - 「みんなの料理名」ボタンから、料理名投稿一覧画面へ遷移できる
  - **「ログイン」ボタンから、ログインができる画面へ遷移する**

- [x] **ログイン画面**
  - **フォームにメールアドレスとパスワードを入力後「ログイン」ボタンから、ログインができる**
  - **「パスワードをお忘れの方」リンクから、パスワードリセット申請画面に遷移できる**
  - **「LINEでログイン」ボタンから、ログインができる**
  - **「Googleでログイン」ボタンから、ログインができる**
  - **「メールアドレスで登録」ボタンから、新規登録ができる(「はじめてご利用の方はこちら」と書いておく)**

- [x] **新規登録画面**
  - **フォームにユーザー情報を入力後「登録」ボタンから、ユーザー登録ができ、トップページ(料理名生成画面)へ遷移できる**

- [x] **パスワードリセット申請画面**
  - **フォームにメールアドレスを入力後「送信」ボタンから、リセット手続きメールが届く**
  - **リセット手続きメールから、パスワードリセット画面に遷移できる**

- [x] **パスワードリセット画面**
  - **フォームに新しいパスワードを入力後「更新」ボタンから、パスワードを更新し、ログイン状態でトップページへ遷移できる**

- [x] トップページ(料理名生成画面)
  - フォームに料理に関する情報を入力・送信すると生成結果画面へ遷移できる

- [x] 生成結果画面
  - 「もう一度名前をつける」ボタンから、トップページ(料理名生成画面)に戻れる
  - **「ログインする」ボタンからログイン/新規登録が行える(ログインすると生成結果を保存できるよ！で誘導)**
  - 「LINEシェア」・「twitterシェア」ボタンから、シェアが行える

- [x] 料理名投稿一覧画面
   - 投稿者のアイコンをクリックすると、その投稿者の投稿一覧が見れる
  -  投稿カードをクリックすると、料理名詳細画面へ遷移できる

- [x] フッター
   -  利用規約画面に遷移できる
   -  プライバシー画面に遷移できる
   -  「お問合せは@twitterIDまで」リンクから運営Twitterアカウントに遷移できる


🟩 **ログインユーザー**
- [x] ヘッダー
  - サービス名のロゴから、トップページ(料理名生成画面)へ遷移できる
  - 「みんなの料理名」ボタンから、料理名投稿一覧画面へ遷移できる
  - **ユーザーアイコンから、ドロップダウンリストが出現し、**
    - **「自分の料理名」から、生成した料理名一覧画面へ遷移できる**
    - **「いいねした料理名」から、いいねした投稿の一覧画面へ遷移できる**
    - **「プロフィール」から、ユーザープロフィールの編集ができる画面へ遷移できる**
    - **「ログアウト」から、ログアウトできる**
  
- [x] **自分の料理名一覧画面** 
  - **「・・・」ボタンから、ドロップダウンリストが出現し、**
    - **「編集する」ボタンから、編集画面へ遷移できる**
    - **「削除する」ボタンから、生成した料理名を削除できる**
    
- [x] **自分の料理名編集画面**
    - **トグルで、料理名の「公開」・「非公開」のステータスを変更できる**
    - **料理画像を添付することができる**
    - **「更新」ボタンで、編集結果を反映し、自分の料理名一覧画面へ遷移できる**

- [x] **いいねした料理名一覧画面**
  - **いいねした投稿の一覧を取得できる**

- [x] **プロフィール画面**
  - **アイコン画像の変更ができる**
  - **表示名を変更できる**
  - **メールアドレスを変更できる**
  - **「更新」ボタンで、編集結果を反映し、プロフィール画面へ遷移できる**

- [x] トップページ(料理名生成画面)
  - フォームに料理に関する情報を入力・送信すると生成結果画面へ遷移できる
  
- [x] 生成結果画面
  - 「もう一度生成する」ボタンから、トップページ(料理名生成画面)に遷移できる
  - **「みんなに公開する」ボタンから、みんなの料理名(掲示板)に投稿ができる**
  - 「LINEシェア」・「twitterシェア」ボタンから、シェアが行える

- [x] 料理名投稿一覧画面
  - 投稿者のアイコンをクリックすると、その投稿者の投稿一覧が見れる
  - **それぞれの投稿にある「★」を押すと、「いいね」ができる**

- [x] フッター
   -  利用規約画面に遷移できる
   -  プライバシー画面に遷移できる
   -  「お問合せは@twitterIDまで」リンクから運営Twitterアカウントに遷移できる

## 🥕なぜこのサービスを作ろうと思ったのか？

### 😖「得意料理は何？」と聞かれた時に、何て答えたらいいか困ることが多かったから
私　「趣味は料理です！」<br>
相手「いいですねー！得意料理は何ですか？」<br>
私　「(得意料理は、冷蔵庫の余り物からアドリブで作る「**名もなき日常料理**」なんだよな...なんて答えたらいいのか...)」

のように、いつも回答に困っていました。「名もなき日常料理」が得意とも言えず、回答を濁すことが多かったため、**一層のこと「名もなき日常料理」に名前をつけてしまえばいいのでは？** と考えました。
### 🥳「名もなき日常料理」に日の目を浴びせてあげたいから
SNSでは、綺麗に盛り付けられた「**名前のある料理**」たちがズラリと並ぶ中、「**名もなき日常料理**」はその影に隠れがちです。一生で食べる食事のうち、食べる回数が多いのはきっと「**名もなき日常料理**」であり、間違いなく我々の胃袋を支えている彼らが、SNS上で肩身の狭い思いをしていることが不憫でなりません。そこで彼らに、**ユニークな名前をつけてあげることで、「名もなき日常料理」をシェアするきっかけや、話題に上る機会与えてあげたい**と考えました。

## 🧑‍💻技術選定
- Rails7
- Hotwire
- postgreSQL
- Redis...料理名生成機能の使用回数制限のために、IPアドレスと使用回数を格納する
- JavaScript
- BootStrap
- Heroku
- OpenAI API...料理名の生成に使用

## 🗓スケジュール
1. 企画(アイデア企画・技術調査): 5/7
2. 設計(README作成・画面遷移図作成・ER図作成): 5/15
3. 機能実装: 5/16〜6/16
4. MVPリリース: 6/16
5. 本リリース: 7/7

## 🖥画面遷移図
- Figmaのリンクは[**こちら**](https://www.figma.com/file/6Q1llX9yabbue2uU0OWOzq/Untitled?type=design&node-id=0-1&t=QuYtjEzxCkf1r6s7-0)をご覧ください。