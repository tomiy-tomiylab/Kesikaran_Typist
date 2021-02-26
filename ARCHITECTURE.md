# Kesikaran_Typist

USキーボードでかな入力をしたいと言う変態のためのタイピングソフト



## 完成像

### 動作

次に押すべきキーをオレンジ色に -間違えて入力しているときはdeleteをオレンジに

SampleSentenceの正しく入力している場所までSampleSentence(かな)をオレンジに

(SampleSentence切り替え　ボタンで)

(サイドバーで例文の一覧)

(アプリケーションメニューからのサイドバーの表示切り替え)

(アプリケーションメニューからSampleSentence登録(テキストファイルからインポート))

(SampleSentenceには文字数制限)

(SampleSentenceのインポート時読みの濁音等は自動で変換) ex) 「いだいだ、ぽけもん」-> 「いた゛いた゛、ほ゜けもん」

(アプリケーションメニューからSampleSentenceエクスポート(Zipで, デフォルトのSentenceを除くかをオプションに))





### UI

・Window

上から順に

キーボード

SampleSentence

SampleSentence(かな)

入力された文字列

入力欄　|　SampleSentence切り替えボタン 

入力されたキー

入力されたキーの刻印

・アプリケーションメニュー

File

​	-Import

​	-Export 

View

​	-Show Sidebar/Hide Sidebar

・サイドバー

１つのSampleSentenceが１つのブロックになっている

ダブルクリックで編集可能





## 用語

・SampleSentence

​	ユーザーが入力する例文　ex) 数年に１回レベルの大変楽しい日本語訳を発見いたしました！

・SampleSentence(かな)

​		ユーザーが入力する例文の読み仮名 ex) すうねんにいっかいれへ゛るのたいへんたのしいにほんこ゛やくをはっけんいたしました！



## 設計

・SampleSentence

1SampleSentence 1ファイル(にする予定)






