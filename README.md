# 2019年度　卒業制作
- [シラバス](syllabus.md)

# 参考URL
- [Photoshopのレイヤーを別ファイルに書き出す](https://helpx.adobe.com/jp/photoshop/kb/5775.html)
- [かえるD. 良いゲームを作るためのディレクターの戦い。面白さの探索と不安のトレードオフ](https://note.mu/kaerusanu/n/n77cf0ee0734e)
  - (ゲーム大賞向けでやっちゃ駄目なやつだけど参考までに)
- [深津 貴之 (fladdict) . 就活用の作品ポートフォリオの作り方](https://note.mu/fladdict/n/ne61e9b48f112)
- [映画『Spider-Man: Into the Spider-Verse』に参加したアーティストがネット上に投稿したアート等1000点以上をまとめ](https://onanimation.com/2019/01/13/the-art-and-making-of-spider-man-into-the-spider-verse/)
  - https://animsquare.com/2019/01/spiderman_art/
- [VRデザインラボ Discordサーバー](https://twitter.com/Banjo_Kanna/status/1111208114831818752)
  - VRのためのデザインに興味ある方はぜひ
- ポートフォリオの作例
  - https://twitter.com/naonao_yanao/status/1112341547729616896
- [paizaブログ. プロジェクトの炎上を防ぐためにSEが「要件定義」で気をつけたい4つのこと](https://paiza.hatenablog.com/entry/2019/03/08/%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E7%82%8E%E4%B8%8A%E3%82%92%E9%98%B2%E3%81%90%E3%81%9F%E3%82%81%E3%81%ABSE%E3%81%8C%E3%80%8C%E8%A6%81%E4%BB%B6%E5%AE%9A%E7%BE%A9%E3%80%8D)

# 年間の予定
- 5月末 [日本ゲーム大賞応募](http://awards.cesa.or.jp/amateur/index.html)
- 6月 就活メイン。DATフェスタ作品の企画会議を平行して進める。1週間ゲームジャムがあるかも
- 11月 DATフェスタ(抽選に通ったらデジゲー博も)出展
- 2月 Web公開とパッケージ完成

## 5月末までの予定
- 4/17 企画の方向性出しと声入れができそうかの検討
- 4/19 企画の素案決定
- 4/26 企画を正式決定してプロジェクト作成とモック画面の作成開始、作業のリストアップ
- **5/9** モックアップ画面仕上げ。細谷先生の画面チェック
- 5/31 応募

# 役割
- プランナー：サムネイル、世界観、プレイヤー設定、操作、ルールをまとめる
- デザイナー：モックアップ作成、キャラクターデザイン、UIデザイン
- プログラマー：プロジェクト作成、作業予定の作成、仕様の調査

# 2週目(4/26)
## ニュース
- [Unity道場 ４月〜アーティストの為のPBR再入門〜](https://meetup.unity3d.jp/jp/events/1070)
- [Unity Designer's Cafe #2 (ワンダープラネット株式会社@渋谷) ](https://unity-designers-cafe.connpass.com/event/128444/)

## 3回目予定
### 1コマ目
各自、イメージ出しや作業に向けた準備。

- デザイナーは、ラフ作成を進める
- プログラマーは、プロジェクトの作成、ビルド、GitHubの連携、データをやり取りする方法などを確認

#### ブラックホール班
- ピクセルサイズを決める
- ピクセルに合わせてプロジェクト設定
- ばらばらに出力したアニメーションをUnityで統合
- 背景のチップをタイルマップに設定して、マップ作成
- UIの作成
- 1画面分を作る

#### ステラ班
- プレイヤーキャラクター、UI、背景を仮でよいので揃える
- Unityに読み込んで1画面分を構成

#### シミュレーション班
- 必要なUI、3Dモデルの発注
- Unityに読み込んで1画面分を構成を目指す

### 2コマ目
デザイナーが描いたラフ画像を見ながら、チームごとに会議をして以下を参考に仕様を決めてTrelloにまとめる。

- ゲームタイトル(仮でよい)
- 現在、考えているキャラクターのリストと、画面内での大きさ
- マップをタイルで作成する場合、1マスの大きさ
- ミスの条件
- ステージクリアの条件
- 操作方法
- プレイヤーに必要な動作一覧
- 必要なシーンと遷移の仕方(あとで追加するのは簡単なので、最低限のもの)
- 各自のGW中の作業担当

以下、可能なら決めておくとよい。

- フォント
  - タイトル / 見出し用フォント
    - ゲームの世界観に合うことを重視。多少読みにくくても良い
  - 説明用フォント
    - ルール説明などのメッセージ用のフォント。ゲームの世界観に合っていながら、読みやすさを重視
  - パラメーター用フォント
    - アルファベットや数値用フォント。他のフォントと共用でもよい
  - 参考： [coliss. 2019年用、日本語のフリーフォント377種類のまとめ](https://coliss.com/articles/freebies/japanese-free-fonts-for-2019.html)
- テーマの色
  - [カラースキームジェネレーター](https://coolors.co/)
  - 参考： https://www.webprofessional.jp/using-color-schemes-in-mobile-ui-design/

### 参考
- Unityプロジェクトの作成と[GitHubでの共有](https://docs.google.com/document/d/1_-4IYojfAzUwW-fk2GSaoDq8zzOp5EID5JemP52Lt6w/)

# 1週目(4/17,19)
## 2回目予定
### やりたいこと
- ゲームシーンの流れを考えてすべてのシーンをスケッチ
- やりたいことのイメージを落書きしながら共有
- カラースキームを決める
  - [カラースキームジェネレーター](https://coolors.co/)  
- BGMと効果音、ボイスの素案
- 正式な解像度で、仮のゲーム画面(モックアップ)を作成
  - [Ryosuke. モックアップ作例](https://twitter.com/ryo620org/status/1104933258389667841)
  - [参考例](https://www.pinterest.jp/yrk00337/%E3%82%B3%E3%83%B3%E3%82%BB%E3%83%97%E3%83%88%E3%82%A2%E3%83%BC%E3%83%88/)
  - [映画『Spider-Man: Into the Spider-Verse』に参加したアーティストがネット上に投稿したアート等1000点以上をまとめ](https://animsquare.com/2019/01/spiderman_art/)
- Trelloに**作業リスト**というリストを作成して、思いつく限りの作業をカードで作成
- Trelloに**Todo**というリストを作成して、来週までにやってくることを作業リストから移動させて、担当者をアサインする
- 最後に簡単にチームごとに進捗を発表

### 手順
- 起動からゲーム開始、ミス、ゲームオーバー、ステージクリア、全ステージクリアなどの流れを一通り考える
  - ざっとスケッチしながら進めると効果的
  - 各画面での操作を考える
  - ゲームでやってみたいことをスケッチして表現しながら固めていく
  - 正式な解像度を共有して、UI、キャラクター、背景の最低3レイヤーに分けて、イメージを描き始める  

### 情報共有ツールTrello
- 情報共有用にTrelloのチームを作って共有
  - 「とれろ」で検索すればOK
  - [Trelloガイド](https://trello.com/guide/)
- 出したアイディアをTrelloに貼り付ける

## 1回目
### アイディアだし
- ジャンル(横スクロールジャンプアクション、パズル、3Dアクション、FPS、TPS、etc...)
- グラフィック(フォトリアル3D、セルシェーダー3D、ローポリ3D、ドット絵、2D基本図形、イラスト系、etc...)

### デザイナーに求めること
- 仮アイディアの時点からすぐにラフ絵を描いて、イメージの共有に寄与する
  - [ほぼ日手帳. グラフィックレコーディングをやってみる](https://www.1101.com/store/techo/ja/magazine/2017/graphicrecording/2017-04-04.html?device=pc)
- 仮グラフィックを手早く揃える
- ゲームを面白そうに見せる画面作り(配色 / レイアウト / フォントの選択 / キャラデザ / 背景)
- 決められた仕様を守ってデータを作成する(解像度、フォーマット、並べ方、ファイル名など)

### プログラマーに求めること
- ゲームの操作やルールをとりまとめて明確にする
- 必要なグラフィックのサイズ、ファイル名、並べ方を明確にして共有
- 素早いプロトタイプ作成
- システムは後回しでよいので、デザイナーが作ったものをすぐ組み込む

### 企画検討
- 企画2週間、開発2週間、仕上げ2週間が目安
- GW開けの5/9にモック画面を完成させてクオリティチェックを受ける
- 声優コースとのコラボは強み。スタジオのスケジュールがあるのでコンテストには間に合わない可能性があるが、今日明日には方針を出して相談だけでもしたい
- ゲームシステムはコンパクトにしつつ、ステージ数やキャラを増やして拡張できるのが望ましい
- DATフェスタ向け作品は別企画でもよい(大物をやりたい場合はコンテストが終わってから仕切り直しましょう)
- リアルな3Dものより、センスの良い抽象的なやつの方が期間的に勝負しやすい
  - [えれのあ. TRISHOOTA](https://twitter.com/in_7010/status/1090902035552063490)
  - [daijo. MetroTree](https://unityroom.com/games/metrotree)

### ゲームの企画
- [昨年度の受賞作品](http://awards.cesa.or.jp/2018/prize/amateur.html)
- [ゲームの定義や面白さの要素からミニゲームを考える](https://docs.google.com/presentation/d/1_psbxg6vPk21C3nAcytyVJm8QTYr-G7AV1qAtjcRclg/edit?usp=sharing)
- [Unity Blog. Unityグローバル学生チャレンジ　受賞作品発表](https://t.co/hJI3rlkiH3)

### モックアップ(コンセプトアート)
- サムネイルを描いて雰囲気を確認
  - ゲーム画面を小さく手書きしたもの
  - [参考例](https://www.pinterest.jp/yrk00337/ゲームラフスケッチ/)

### ゲームの企画概要書を手書きで作成
A4の紙を配布するので、以下について出たアイディアを書いていってください。なるべくグラフィックレコーディングで。

- タイトル
  - あとで変更可能なので深く考えずにとりあえず何か付けておく
- 対象プラットフォーム
  - PC / スマホ / Webなど
- 解像度
  - 最適な画面サイズ
- サムネイル
- ルール
- プレイヤーの操作
- ストーリー
  - 取ってつけるのではなく、プレイヤーの操作や攻撃方法、クリアの目的から発案するとよい
  - かっこいいカジュアルゲームならなくてもよい

### 1回目課題
- 自己紹介に備えて、自分の得意分野を示せる過去作品を、すぐに画面に出せるように準備してきてください
- 以下を読んでゲームを面白くするための根拠を考えてきてください。
  - [［GDC 2019］ゲームメカニクスだけに依存しない，面白いゲームの作り方。その技術を支える「6つの動詞」とは](https://www.4gamer.net/games/999/G999905/20190321021/)
  - [かえるD. なぜ作ったゲームが面白くならないのか？基礎にして奥義「フロー理論」](https://note.mu/kaerusanu/n/nc80f9523bb8e)
