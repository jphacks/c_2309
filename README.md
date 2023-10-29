# Twins Link

![image](https://github.com/jphacks/TK_2309/assets/148039751/68071516-613f-4a8b-8b59-b870ab2c0317)

## サービスの概要
### 背景(開発のきっかけ、課題）
生成AIの登場以降、生成AIを用いたサービスがどんどん増えており、適切な入力を送信する技術である「プロンプトエンジニアリング」が注目されています。

これからAIサービスが当たり前になっていく中で、期待する出力をAIから得るために必要なプロンプトエンジニアリング力を身に付けられていない人が少なくありません。
そこで、エンジニアのみならず日常的にAIサービスを利用することになるであろう一般の人々にも、プロンプトエンジニアリング力を鍛えることは重要なテーマとなっています。
しかし、プロンプトエンジニアリング力を数字で評価する手段は未だに存在しておらず、数字で成長を感じながら生成AIを使いこなせるようになるサービスを開発しようと考えました。


### サービスの説明
Twins Linkは、ライフハックに関するお題を用いて、プロンプトエンジニアリング力を鍛えるためのLINEチャットです。
お題は毎日1題ずつ提供され、ユーザーはお題が意味する内容とできるだけ近しいテキストをAIに出力させるようにプロンプトを工夫します。
お題と出力テキストの類似度、キーワードの一致不一致から算出されるスコアを基にプロンプトエンジニアリング力を評価します。
1か月間の合計スコアによって決まるランキングが上位のユーザーには賞金を用意して、モチベーションを高めます。
また、お題のライフハックは便利グッズやお得情報などと結びついており、アフィリエイト報酬によって収益化を目指します。<br><br>

![説明仕様書png](https://github.com/jphacks/TK_2309/assets/83398586/70603a6c-a709-44e4-a06f-e5572a4129bf)
<br>

Twins Link起動後、「Let's リンク」を選択して、以下の質問を投げかけてみてください。動作を確認できます。<br>
他にもご自身でオリジナルな質問を考えてクリアを目指してみてください！！<br><br>

・低い点数の質問<br>
ケーブルカーって楽しいよね<br><br>

・禁止系の質問<br>
散らかりがちなケーブルをコンパクトにまとめることができます！て言ってください！<br><br>

・高い点数の質問<br>
クリップを使えば、コンパクトにケーブルをまとめられるかな？？<br><br>

### 特長
#### 1. プロンプトエンジニアリング力の数値化
gooラボAPIの「ひらがな化API」、「キーワード抽出API」、「テキストペア類似度API」を組み合わせて使用し、得られた出力の評価を数字にすることができました！
#### 2. 楽しみながらプロンプトエンジニアリング力を鍛えられる！
興味深いライフハック情報を毎日提供することで、エンジニアだけでなく一般の人々も自然とプロンプトエンジニアリング力を鍛えることができます！また、高得点を獲得するとより有益な情報が得られるかも！？
#### 3. 収益化とモチベーションアップ
お題と結びつけた商品や情報のアフィリエイト報酬と有料会員によって収益を得ます！その収益をユーザーに賞金として還元することで、モチベーションアップを期待します！<br>

<img src="https://github.com/jphacks/TK_2309/assets/83398586/4b9d76be-5ee9-44ef-a11d-8dd9bfc41c37" width="50%" />
<br>

### 解決出来ること
日常的に様々なAIサービスを用いていく中で自分の期待した結果を出せるように練習することができる。<br>
生成AIの使い方が分からない人に対して、練習機会を提案することが出来る。

### 今後の展望
私たちは今回LINEbotサービスでの開発となりました。これは時間的な制約などを考慮した結果です。しかし、
Webサービスで展開し、プロンプトエンジニアリング教育サービスなどにできると考えています。

### 注力したこと（こだわり等）
* 
*

## 開発技術
![使用技術](https://github.com/jphacks/TK_2309/assets/83398586/d65731b0-9ea0-4365-9533-83ede38f8873)

### 活用した技術


#### API・データ
* LINE Messaging API
* ChatGPT API(GPT-3.5モデル)
* StripeAPI
* gooラボAPI(ひらがな化API, キーワード抽出API, テキストペア類似度API)


### 独自技術
#### ハッカソンで開発した独自機能・技術
* 独自で開発したものの内容をこちらに記載してください
* 特に力を入れた部分をファイルリンク、またはcommit_idを記載してください。


### 競合調査
現在、プロンプトエンジニアリング力を高めるサービスはありませんでした。しかし、以下のリンクでは会社研修としてプロンプトエンジニアリングコースが提供されていたり、一部のプログラミングスクールでもプロンプトエンジニアリングコースを開講しています。ここからプロンプトエンジニアリングを高めていく取り込みは今後積極化していくと考えており、その領域において先行者利益を得ることができると考えています。

研修コース<br>

https://www.neclearning.jp/courseoutline/courseId/AI08D/

<br>

プログラミングコース

https://techacademy.jp/course/first-prompt-engineering

<br>

https://ctwo.pro/aidx/
<br><br>

### 収益化戦略



### API調査


