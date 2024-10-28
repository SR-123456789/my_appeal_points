# ポートフォリオ
## 立命館大学 理工学部 ロボティクス学科3回生 中谷壮志

### 製作物（個人）
* **BadEasyTranslater**
  * [GooglePlay](https://play.google.com/store/apps/details?id=preparation.badEasyTranslater)
  * [AppleStore](https://apps.apple.com/jp/app/%E8%88%88%E5%91%B3%E3%81%AE%E3%81%82%E3%82%8B%E6%96%87%E7%AB%A0%E3%81%A7%E8%8B%B1%E8%AA%9E%E5%AD%A6%E7%BF%92badeasytranslater/id6502329660)
    * プレームワーク・ライブラリ・APIなど
      * ReactNative
      * Azure Translater
      * english-to-katakana-conversion
      * Admob
    * 機能説明
      * 英語文を入力すると、その単語一つ一つの意味を表示することができる。
      * 普段日本語で読む文章を英語教材として活用できるようにすることで、英語学習の時間を大幅削減することを目的としている。
    * 開発理由・背景
      * 英文を読んでいるときにいちいち検索するのも単語帳に登録する事がストレスだったため、ワンタップで意味を表示し単語帳登録ができるアプリが欲しかった。
      * 英語学習のためだけに、文章を読むことが非効率的だと考えたため、普段読む文章を英語の教材といて活用できないかと考えた。
    * 将来の展望
      * ChatGPT APIを活用し、入力された英語文章から問題を生成し、正答率を評価する機能
      * Wikipedia APIから英文を取得できるようにする（９割実装完了　5/20時点）
    * SNS
      * [Instagram](https://www.instagram.com/badeaytranslater/?hl=ja) 

* **ドアベルセンサー[DoorBellSensor] **
  * [AppleStore]([[https://play.google.com/store/apps/details?id=todo.list.v1](https://apps.apple.com/jp/app/%E3%81%A9%E3%82%8C%E3%81%A0%E3%81%91%E9%80%B2%E3%82%93%E3%81%A0%E3%81%8B%E4%B8%80%E7%9B%AE%E3%81%A7%E3%82%8F%E3%81%8B%E3%82%8Btodo%E3%83%AA%E3%82%B9%E3%83%88-%E3%82%BF%E3%82%B9%E3%82%AF%E9%80%B2%E6%8D%97%E7%AE%A1%E7%90%86/id6560114498)](https://apps.apple.com/us/app/%E3%83%89%E3%82%A2%E3%83%99%E3%83%AB%E3%82%BB%E3%83%B3%E3%82%B5%E3%83%BC-doorbellsensor/id6736841798))
    * プレームワーク・ライブラリ・APIなど
      * Swift UI
    * 機能説明
      * クライアント側での人体検知の精度をためしたかったため、開発
      * スマホのカメラを使用し、人を検知した時にチャイムオンを再生する。
      * 今後は、警報機能や不審者撮影機能、人数カウント機能を追加予定
    　   
* **[ToDoリスト]どれだけ進んだのか一目でわかる**
  * [GooglePlay](https://play.google.com/store/apps/details?id=todo.list.v1)
  * [AppleStore]([https://play.google.com/store/apps/details?id=todo.list.v1](https://apps.apple.com/jp/app/%E3%81%A9%E3%82%8C%E3%81%A0%E3%81%91%E9%80%B2%E3%82%93%E3%81%A0%E3%81%8B%E4%B8%80%E7%9B%AE%E3%81%A7%E3%82%8F%E3%81%8B%E3%82%8Btodo%E3%83%AA%E3%82%B9%E3%83%88-%E3%82%BF%E3%82%B9%E3%82%AF%E9%80%B2%E6%8D%97%E7%AE%A1%E7%90%86/id6560114498))
    * プレームワーク・ライブラリ・APIなど
      * Monaca(Android)
      * ReactNative(IOS)
      * jQuery
      * Cordova
    * 機能説明
      * TODOリストは数え切れない数が存在するが、ここのタスクの進捗状態を記録するものが存在せず、それぞれのタスクの進捗状態を管理するアプリが欲しかったため開発しました。
    
* **english-to-katakana-conversion**
  * [GitHub](https://github.com/soshi1234/english-to-katakana-conversion?tab=readme-ov-file)
    * 機能説明
      * 英単語を引数にして、読み方をカタカナで返してくれるJavascriptライブラリー
     
* **reactnative-front-ocr**
  * ReactNarive環境でクライアントサイドでOCRを行うことを目標に開発中のライブラリー
  * GoogleVision API が高額なため開発することにしました。
  * Swiftで書いたネイティブモジュールをブリッジさせ、ReactNative環境で実行させることを目標にしています。
     
      

### 製作物（団体) 
* 団体名：歩くアルパカ制作委員会 [公式サイト（私が作成しました）](https://aruku-arupaka-organization.vercel.app/)
* 私の役職
  * 代表
   * 歩くアルパカ+RのPM
     * issueの割り振り
     * storeへの審査対応
     * 開発
     * 企画
  * プロジェクト
    * 歩くアルパカ+R
      * 私の役割　タスク割り振り・コーディング
      * 開発目的
        * 大学生に役立つアプリを開発する。
      * プレームワーク・ライブラリ・APIなど
        * ReactNative
        * DRF
        * Gin
        * FireBase
        * Render
      * インストール方法
        * [IOS](https://apps.apple.com/jp/app/%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%B4%BB%E6%94%AF%E6%8F%B4%E3%82%A2%E3%83%97%E3%83%AA-for-%E7%AB%8B%E5%91%BD%E9%A4%A8-%E6%AD%A9%E3%81%8F%E3%82%A2%E3%83%AB%E3%83%91%E3%82%AB-r/id6499567971)
        * Androidは審査中
        * [旧版(Android)](https://play.google.com/store/apps/details?id=cordova.arupaka)
    * リツフレ
      * 私の役割　チャット周りのコーディング
      * 開発目的
        *　学内SNS
      * プレームワーク・ライブラリ・APIなど
        * ReactNative
        * DRF
        * FireBase
        * Render
        * 
    * AI部門
