# 2019年度　卒業制作
- [シラバス](syllabus.md)

# 参考URL
- [UnityプロジェクトをGitHubに登録する](https://github.com/dat19/gp1/blob/master/github-unity.md)
- [背景を切り取る](https://www.remove.bg/)
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
  - 最初の週で、各自が作成した素材を共有ドライブの指定のフォルダーに提出(デモプログラムを作成予定)
- 11月 DATフェスタ(抽選に通ったらデジゲー博も)出展
- 2月 Web公開とパッケージ完成

# 参考 Exプロジェクト
- [GreeningEx2019 GitHub](https://github.com/dat19/GreeningEx2019)
- [HungraviyEx2019 GitHub](https://github.com/dat19/HungraviyEx2019)
- [Unity用の命名規則設定ファイル](https://gist.github.com/am1tanaka/0870ceaf722062882bec487c652abccb)

# 残りの日程と予定
## 日程
- 12/18, 20
- **1/8, 10**
  - 作成するデータについて、詳しく説明した上で、制作開始
- 1/15, 17
- 1/22, 24
- 1/29, 31 すべての締め切り
- 2/5, 7 予備週

## 予定
- 完成版をCDに焼き、パッケージを制作する
- 完成作品を公開するためのGitHub Pagesを作成する。公開先は、このリポジトリー上。以下について、マークダウンかHTMLで作成して、データ一式を提出する
  - 作品名
  - スクリーンショット
  - ゲーム概要
  - 遊び方
  - ダウンロードのリンク
  - 使用アセットリスト
  - 参考 [paiza. ITエンジニアの就活準備編2: ポートフォリオ制作](https://paiza.jp/works/career/primer/career2)
- Greeningは、動画の組み込み
- GreeningとHungraviyのグラフィックデータをアセットにまとめて公開
  - 著作者表示の名前を確認

# 後期12週目(1/8, 10)

## 予定
- はんぐらびぃとGreeningのスタッフクレジットをTrelloなどでまとめる
  - 担当した作業と表示する名前。本名でもハンドル名でも仮名でも
- GreeningEx2019素材
  - 現在までにできているデモシーンの確認
  - 背景のうち、木のレイヤーを上下スクロールに対応させる
    - 高さを2048に拡張
    - 中央の1080ピクセルを画面と見立てて、見せたい大きさで描画する
    - 木のない上空は透過、下は地面の色で塗りつぶす
  - クリア時のステラの動きを検討する(星につかまる？)
- 作成するデータ
  - CDラベル
  - パッケージ
  - 配信用Webページ
    - 参考 [paiza. ITエンジニアの就活準備編2: ポートフォリオ制作](https://paiza.jp/works/career/primer/career2)
- 現状のバージョンをプレイして、不具合を見つけたらTrelloなどに書き込む
  - 先に進めないなど、遊ぶ上で支障が出ないようにすることを最優先にする



- はんぐらびぃとGreeningのExプロジェクトの成果物の確認
  - GreeningEx2019
    - `X:\2019年\ゲーム学科\Student\ゲームプログラム1年\GreeningEx2019` を開く
    - GreeningExeフォルダーをデスクトップなどにコピーしてから、中のGreeningEx2019.exeをダブルクリックして起動
    - GreeningEx2019の不具合は[こちら](https://github.com/dat19/GreeningEx2019)にNew issueを作って報告できる
  - はんぐらびぃEx2019
    - `X:\2019年\ゲーム学科\Student\ゲームプログラム1年\HungraviyEx2019` を開く
    - HungraviyExeフォルダーをデスクトップなどにコピーしてから、中のHungraviyEx2019.exeをダブルクリックして起動
    - [Android版のはんぐらびぃについて](https://github.com/dat19/HungraviyEx2019/blob/master/Documents/JikkiTest.md)


## 金曜日予定
- 引き続き、現状のバージョンをプレイして、不具合を見つけたらTrelloなどに書き込む
  - 先に進めないなど、遊ぶ上で支障が出ないようにすることを最優先にする


# 後期11週目(12/18, 20)
## 資料
- [Unityの命名規則とエディター設定](http://am1tanaka.hatenablog.com/entry/2019/12/06/101055)
- [GreeningEx2019 GitHub](https://github.com/dat19/GreeningEx2019)
- [HungraviyEx2019 GitHub](https://github.com/dat19/HungraviyEx2019)

## 内容
- 今後の予定の説明
- 1/8から、データのアーカイブを始められるように、不備が残っていたら直したり、問題のないバージョンを選ぶ
- Exプロジェクト側の完成目標は1/15。オープニング動画などが出来たら、それを入れてCDに同梱する予定

### Greening
- 現状報告。手がおかしい原因を調査

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - <s>ぐらびぃが落下する時の腹ペコ状態</s>


# 後期10週目(12/11, 13)

### Greening
- 進捗報告
  - 開発側の報告
  - 不足モデル、アニメーション
    - <s>ステラの立ちモーション</s>
    - <s>たんぽぽの花(茎と綿毛が丸くついている部分に分けて作る)</s>

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - ぐらびぃがブラックホールに引っ張られるのと、落下するアニメについても、腹ペコ状態の絵が欲しい

### 無人島ゲーム
- Bolt対応

### その他のプロジェクト
- 何をするかの相談


# 後期9週目(12/4, 6)
## 話題
- [ITmedia. 「これさぁ、悪いんだけど、捨ててくれる？」――『ジャンプ』伝説の編集長が、数億円を費やした『ドラゴンボールのゲーム事業』を容赦なく“ボツ”にした真相](https://www.itmedia.co.jp/business/articles/1912/06/news020.html)
- [Unity用の命名規則設定ファイル](https://gist.github.com/am1tanaka/0870ceaf722062882bec487c652abccb)
- [tkm. 企画を元にゲームのUIを作るときの流れ](https://note.com/torinegi/n/n5beaca465b1b)
- [ゲームグラフィックデザイン　アドベントカレンダー2019](https://adventar.org/calendars/4439)



### Greening
- 進捗報告
  - 開発側の報告
  - 不足モデル、アニメーション
    - ステラの立ちモーション
    - たんぽぽの花
    - ツタの苗

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - ぐらびぃがブラックホールに引っ張られるのと、落下するアニメについても、腹ペコ状態の絵が欲しい

### 無人島ゲーム
- Bolt対応

### その他のプロジェクト
- 何をするかの相談



https://github.com/dat18/sotsusei/


# 後期8週目(11/27, 29)
## 話題
- [ゲームクリエイターズギルド](https://game.creators-guild.com/event/gamecreatorsguildexpo2019/)

## 予定
- 進捗報告と作業

### Greening
- 進捗報告
  - 開発側の報告

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - ぐらびぃがブラックホールに引っ張られるのと、落下するアニメについても、腹ペコ状態の絵が欲しい

### 無人島ゲーム
- Bolt対応

### その他のプロジェクト
- 何をするかの相談


# 後期8週目(11/27, 29)
## 話題
- [仮想世界を一緒に創る3DCGモデラーの学生インターンの募集](https://note.mu/ambr/n/nc923309cb149)
- [ゲームクリエイターズギルド](https://game.creators-guild.com/event/gamecreatorsguildexpo2019/)
- [東京工科大学所属のゲーム制作チーム](https://twitter.com/littlebokkuri)
- [東京工業大学 デジタル創作同好会traP](https://trap.jp/)
- [ダウンロードカードを製作するサービス conca](https://conca.cc/)

## 内容
- 進捗報告と作業

### Greening
- 進捗報告
  - 開発側の報告
  - (済)地面ブロック
    - 地面と水の双方の床用の画像を、立方体に貼り付けたモデルとして作成する
  - (済)苗
    - [現状の植物の種類](https://docs.google.com/document/d/1oWRK3W0Fcn0d7V2_GTKpqFYhwVO18kx_rV-HDRxuXrw/)
  - (一先ず完了)プレイヤー
    - (済)苗を拾う
    - (済)苗を持ち上げている状態
      - 運ぶのは、このモーションと歩きをレイヤーマスクを使ってプログラム側で合成するので多分不要
    - (済)苗を置く
    - (済)水のミス
    - クリア時(動きを検討。急ぎではない)
    - ステージ開始時(制作は保留。ハスをたんぽぽを持つモーションで持たせてみる)
    - カブの上(歩きの逆再生でいけそうなので、ひとまずそれでやってみる)

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - ぐらびぃがブラックホールに引っ張られるのと、落下するアニメについても、腹ペコ状態の絵が欲しい

### 無人島ゲーム
- Bolt対応

### その他のプロジェクト
- 何をするかの相談


# 後期7週目(11/20, 22)
## 内容
### Greening
- 動画の演出と新しい仕様についての打ち合わせ
- 新規の画像やモーション
  - 地面ブロック
    - 地面と水の双方の床用の画像を、立方体に貼り付けたモデルとして作成する
  - 苗
    - 種類ごとに作成
    - 持ち運びに備えて、根っこをつける？　→　相談
    - [現状の植物の種類](https://docs.google.com/document/d/1oWRK3W0Fcn0d7V2_GTKpqFYhwVO18kx_rV-HDRxuXrw/)
  - プレイヤー
    - 苗を拾う
    - 苗を持ち上げている状態
      - 運ぶのは、このモーションと歩きをレイヤーマスクを使ってプログラム側で合成するので多分不要
    - 苗を置く
    - 水のミス
    - クリア時
    - ステージ開始時(制作は保留。ハスをたんぽぽを持つモーションで持たせてみる)
    - カブの上(歩きの逆再生でいけそうなので、ひとまずそれでやってみる)
  - 既存のモデルのマテリアル確認
    - stella_tulip →　未使用
- プログラムまとめ

### はんぐらびぃ
- アセット、プログラムそれぞれをまとめる作業
  - inhaleのアニメーションの作成。ファイルはこちらでリネームしたものを利用してほしい

### 無人島ゲーム
- Bolt対応

### その他のプロジェクト
- 何をするかの相談


# 後期6週目(11/13)
## 話題
- [ゲームクリエイターズギルド](https://game.creators-guild.com/event/gamecreatorsguildexpo2019/)
- [クオリティの追求例](https://twitter.com/nal_ew/status/1191210885894639621)
- [LookingGlassハッカソンの展示例](https://twitter.com/e__koma/status/1193857453223366656)
- [シロフード. ◆第2回LookingGlassハッカソンについて思う事](https://sirohood.exp.jp/20191111-2959/)
- [最小限の労力で最大限の効果を出す方法〜『ペルセポネ』ができるまで〜](https://madewithunity.jp/stories/persephone/)

## 内容
- DATフェスタの展示の実行ファイル、プロジェクトを提出
  - Unityのプロジェクトと実行ファイルをチームごとにまとめて、ネットドライブの `X:\2019年\ゲーム学科\Student\卒業制作\DATフェスタプロジェクト＆実行ファイル` に提出
    - ゲーム名のフォルダーを作成する

- 作成したゲーム名のフォルダーの中に以下をコピーする
      - Unityのプロジェクト
      - 実行ファイルをビルドしたフォルダー
      - 展示の時に張り出したゲーム説明のデータ
- 作品の講評
- 作品のまとめドキュメントを作成する
  - 夏休みの課題と同様に、DAT作品についてチームで1つドキュメントをまとめて、上記の提出先フォルダーに提出する
- 今後の方針
  - チームごとに、開発を継続するか、終了かを決定
  - プロジェクト終了の場合、パッケージ化と公開の作業を11月中を目途に完了させる
- リソースについて相談
  - 1年生の習作などで利用できるようにまとめたい
  - 利用方針を決めて、ライセンスを設定する
    - 公開の可否。可能な場合、クレジット表示をどうするか
    - 改変を可否。可能な場合、クレジット表示をどうするか
  - アセットストア、Sketchfab、Boothなどでの公開を検討

# 後期5週目(10/30, 11/1)
## DATフェスタまでのスケジュール
- 10/2, 4
- 10/9, 11
- 10/16, 18
- 10/23, 25
- **10/30, 11/1**
- **11/8, 9 本番**

## DATフェスタに向けて、どういう形で展示ができるかを検討する
- 未完成でも、説明する人間がいれば展示はできる
- 来た人に何が提供できるか？
- 作っておくとより良く展示できるものはないか？

## 予定
- ポスター、展示用パネルの制作(展示に間に合うように準備する)
- DATフェスタの作業等
- 現在できているものを統合して、ビルドのチェックを行う

## 各作業状況
### ステラ
- プレイヤーのアニメーションを増やす(データは完成)
  - たんぽぽとジャンプのコードを修正
- ステージをやめる時の選択肢のグラフィック
- ステージ選択時のフォント
- ステージの星の色決め
- 組み込んだ星の色チェック
- 導入や進行イベント、エンディングの検討、製作
  - 世界観？プレイヤーは何者？ゲームをクリアするモチベーション？
  - 主人公はしゃべらない。声
  - ナレーション
- <s>UnityTile3Dで地面を作る</s>
- <s>星モデルの差し替え</s>
- <s>ポーズ</s>
- <s>ステージ選択へ戻る</s>
- <s>プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する</s>
- <s>左右を素早く動かすと、逆方向に動き続けるバグの解消</s>
- <s>星モデルの作成</s>
  - 島をゲームのステージ数分作成
  - 島と星のマテリアルを分ける
  - 汚染された色と、回復した色の2つのモデルを作成

### はんぐらびぃ
- ステージをタイムアタックに改良
- タイムとランキングを統合
- 左に押し出されるバグ修正
- ぐらびぃのモーション相談
  - やられた時
  - 中に浮いている時(落ちているモーションだと動きに合っていなかった)
- ESCで終了
- 自作ネットランキング
  - unityroomのやつは展示に向いていないため
- 以下、保留
  - 上下に移動する障害物(敵はできている。ネットドライブの卒制の中の`enemy_2.unitypackage`)
  - 敵を増やす
  - クリアなどの文字を再描画
  - タイムの文字、演出の検討
- <s>ぐらびぃグラフィック</s>
  - <s>落下時のアニメ</s> `X:\2019年\ゲーム学科\Student\卒業制作\はんぐらびぃ\グラビィアニメーション\グラビィ　落下`
  - <s>ブラックホールで吸い込んだものがお腹におさまった演出のアニメ</s>
  - <s>満腹状態</s>
  - <s>腹ペコ状態</s>
- <s>GitHubアカウントの見直し。1つ外部作業用のアカウントを登録する</s>
- <s>ブラックホールの吸い込みの検討</s>
- <s>ブラックホールが消える時のアニメ</s>
- <s>タイトルのアルファベット表記を決めて、プロジェクトフォルダーをそれにしたものをGitHubで管理する</s>

### マルチプレイヤーコンストラクション
- 10/23の週にBoltを組み込む予定。それまでにきりがよいところまで進める
- オブジェクトの生成と配置
- UIやオブジェクトの作成と入れ替え
- <s>水のシェーダー研究</s>
- <s>フィールド作成</s>
- <s>アイテムのストック処理</s>




# 後期4週目(10/23, 25)

## DATフェスタまでのスケジュール
- 10/2, 4
- 10/9, 11
- 10/16, 18
- **10/23, 25**
- 10/30, 11/1
- **11/8, 9 本番**

## 予定
- ポスター、展示用パネルの制作(展示に間に合うように準備する)
- DATフェスタの作業等
- 現在できているものを統合して、ビルドのチェックを行う

## 各作業状況
### ステラ
- プレイヤーのアニメーションを増やす(データは完成)
  - たんぽぽとジャンプのコードを修正
- ステージをやめる時の選択肢のグラフィック
- ステージ選択時のフォント
- ステージの星の色決め
- 組み込んだ星の色チェック
- 導入や進行イベント、エンディングの検討、製作
  - 世界観？プレイヤーは何者？ゲームをクリアするモチベーション？
  - 主人公はしゃべらない。声
  - ナレーション
- <s>UnityTile3Dで地面を作る</s>
- <s>星モデルの差し替え</s>
- <s>ポーズ</s>
- <s>ステージ選択へ戻る</s>
- <s>プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する</s>
- <s>左右を素早く動かすと、逆方向に動き続けるバグの解消</s>
- <s>星モデルの作成</s>
  - 島をゲームのステージ数分作成
  - 島と星のマテリアルを分ける
  - 汚染された色と、回復した色の2つのモデルを作成

### はんぐらびぃ
- ステージをタイムアタックに改良
- タイムとランキングを統合
- 左に押し出されるバグ修正
- ぐらびぃのモーション相談
  - やられた時
  - 中に浮いている時(落ちているモーションだと動きに合っていなかった)
- ESCで終了
- 自作ネットランキング
  - unityroomのやつは展示に向いていないため
- 以下、保留
  - 上下に移動する障害物(敵はできている。ネットドライブの卒制の中の`enemy_2.unitypackage`)
  - 敵を増やす
  - クリアなどの文字を再描画
  - タイムの文字、演出の検討
- <s>ぐらびぃグラフィック</s>
  - <s>落下時のアニメ</s> `X:\2019年\ゲーム学科\Student\卒業制作\はんぐらびぃ\グラビィアニメーション\グラビィ　落下`
  - <s>ブラックホールで吸い込んだものがお腹におさまった演出のアニメ</s>
  - <s>満腹状態</s>
  - <s>腹ペコ状態</s>
- <s>GitHubアカウントの見直し。1つ外部作業用のアカウントを登録する</s>
- <s>ブラックホールの吸い込みの検討</s>
- <s>ブラックホールが消える時のアニメ</s>
- <s>タイトルのアルファベット表記を決めて、プロジェクトフォルダーをそれにしたものをGitHubで管理する</s>

### マルチプレイヤーコンストラクション
- 10/23の週にBoltを組み込む予定。それまでにきりがよいところまで進める
- オブジェクトの生成と配置
- UIやオブジェクトの作成と入れ替え
- <s>水のシェーダー研究</s>
- <s>フィールド作成</s>
- <s>アイテムのストック処理</s>



# 後期3週目(10/16, 18)
## 話題
- [2019 ハロウィンイベント結果発表](http://www.asset-sale.net/entry/Halloween2019End)
- [Unity Asset Store「ハロウィンコンテスト」開催中（10月31日まで）](http://assetstore.info/asset-store-halloween-contest/)
-　12/7  [【1day】Unity Engine Challenge by mixi GROUP](https://mixi.connpass.com/event/150482/)

## チームごとに作業予定の発表と必要な打ち合わせ


## 各作業状況
### ステラ
- ステージをやめる時の選択肢のグラフィック
- ステージ選択時のフォント
- ステージの星の色決め
- 組み込んだ星の色チェック
- 導入や進行イベント、エンディングの検討、製作
  - 世界観？プレイヤーは何者？ゲームをクリアするモチベーション？
  - 主人公はしゃべらない。声
  - ナレーション
- プレイヤーのアニメーションを増やす(データは完成)
- <s>UnityTile3Dで地面を作る</s>
- <s>星モデルの差し替え</s>
- <s>ポーズ</s>
- <s>ステージ選択へ戻る</s>
- <s>プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する</s>
- <s>左右を素早く動かすと、逆方向に動き続けるバグの解消</s>
- <s>星モデルの作成</s>
  - 島をゲームのステージ数分作成
  - 島と星のマテリアルを分ける
  - 汚染された色と、回復した色の2つのモデルを作成

### はんぐらびぃ
- クリアなどの文字を再描画
- ステージをタイムアタックに改良
- 左に押し出されるバグ修正
- ぐらびぃのモーション相談
  - やられた時
  - 中に浮いている時(落ちているモーションだと動きに合っていなかった)
- タイムの文字、演出の検討
- ESCで終了
- 以下、保留
  - 上下に移動する障害物(敵はできている。ネットドライブの卒制の中の`enemy_2.unitypackage`)
  - 敵を増やす
- 自作ネットランキング
  - unityroomのやつは展示に向いていない
- <s>ぐらびぃグラフィック</s>
  - <s>落下時のアニメ</s> `X:\2019年\ゲーム学科\Student\卒業制作\はんぐらびぃ\グラビィアニメーション\グラビィ　落下`
  - <s>ブラックホールで吸い込んだものがお腹におさまった演出のアニメ</s>
  - <s>満腹状態</s>
  - <s>腹ペコ状態</s>
- <s>GitHubアカウントの見直し。1つ外部作業用のアカウントを登録する</s>
- <s>ブラックホールの吸い込みの検討</s>
- <s>ブラックホールが消える時のアニメ</s>
- <s>タイトルのアルファベット表記を決めて、プロジェクトフォルダーをそれにしたものをGitHubで管理する</s>

### マルチプレイヤーコンストラクション
- 10/23の週にBoltを組み込む予定。それまでにきりがよいところまで進める
- オブジェクトの生成と配置
- 水のシェーダー研究
- <s>フィールド作成</s>
- <s>アイテムのストック処理</s>

## 金曜日： TwitCastingでライブストリーミングの準備
- スタートメニュー > twで検索して、TwitCasting Desktop Liveを起動
  - 未インストールの場合、[ここ](http://twitcasting.tv/tdl_download.php)を開いて、ダウンロードして実行 > 規約を承諾してインストールする
- Explorerを開いて、以下をバスにコピペして開いて、各項目を設定してください
  - X:\2019年\ゲーム学科\Teacher\tanaka\twitcasting.txt
- [手順](https://docs.google.com/document/d/1KA8AbOhcG2-eG0nhPJR02losYx-YCMQSuum2xWQfLwM)


# 後期2週目(10/9, 11)
## 話題
- [Unity AssetStoreまとめ. 【ハロウィン】バウチャー総額『250ドル+α』の山分けプレゼントイベント](http://www.asset-sale.net/entry/Halloween2019)
- [gamesindustry.biz. ［Unite 2019］実は3DCGアニメ作品だった「Hello World」。この作品をゲームエンジンUnityで再現することはできるのか？](https://jp.gamesindustry.biz/article/1909/19093002/)

## DATフェスタまでのスケジュール
- 10/2, 4
- **10/9, 11**
- 10/16, 18
- 10/23, 25
- 10/30, 11/1
- **11/8, 9 本番**

## 各作業状況
### ステラ
- <s>プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する</s>
- UnityTile3Dで地面を作る(半分ぐらい完了。ぴったりの場所じゃない場合、オブジェクトの位置を移動)
- 導入や進行イベント、エンディングの検討、製作
  - 世界観？プレイヤーは何者？ゲームをクリアするモチベーション？
  - 主人公はしゃべらない。声
  - ナレーション
- <s>左右を素早く動かすと、逆方向に動き続けるバグの解消</s>
- プレイヤーのアニメーションを増やす
- 星モデルの作成
  - 島をゲームのステージ数分作成
  - 島と星のマテリアルを分ける
  - 汚染された色と、回復した色の2つのモデルを作成
- 星モデルの差し替え
- ポーズ
- ステージ選択へ戻る

### はんぐらびぃ
- <s>GitHubアカウントの見直し。1つ外部作業用のアカウントを登録する</s>
- <s>ブラックホールの吸い込みの検討</s>
- <s>ブラックホールが消える時のアニメ</s>
- <s>タイトルのアルファベット表記を決めて、プロジェクトフォルダーをそれにしたものをGitHubで管理する</s>
- クリアなどの文字を再描画
- ステージをタイムアタックに改良
- 左に押し出されるバグ修正
- ESCで終了
- ぐらびぃグラフィック
  - <s>落下時のアニメ</s> `X:\2019年\ゲーム学科\Student\卒業制作\はんぐらびぃ\グラビィアニメーション\グラビィ　落下`
  - ブラックホールで吸い込んだものがお腹におさまった演出のアニメ
  - 満腹状態
  - 腹ペコ状態
- 以下、保留
  - 上下に移動する障害物(敵はできている。ネットドライブの卒制の中の`enemy_2.unitypackage`)
  - 敵を増やす

### マルチプレイヤーコンストラクション
- <s>フィールド作成</s>
- <s>アイテムのストック処理</s>
- オブジェクトの生成と配置
- 水のシェーダー研究

## TwitCastingでライブストリーミングの準備
- スタートメニュー > twで検索して、TwitCasting Desktop Liveを起動
  - 未インストールの場合、[ここ](http://twitcasting.tv/tdl_download.php)を開いて、ダウンロードして実行 > 規約を承諾してインストールする
- Explorerを開いて、以下をバスにコピペして開いて、各項目を設定してください
  - X:\2019年\ゲーム学科\Teacher\tanaka\twitcasting.txt
- [手順](https://docs.google.com/document/d/1KA8AbOhcG2-eG0nhPJR02losYx-YCMQSuum2xWQfLwM)


# 後期1週目(10/2, 4)
## 話題
- [Unity道場 幕張スペシャル3 -Education編-](https://meetup.unity3d.jp/jp/events/1132)にLTで登壇してきました
  - [専門学校のゲームプログラマーコースにおけるUnity1週間ゲームジャムの活用事例](https://www.slideshare.net/UnityTechnologiesJapan/unity-3unity1)
- [日本ゲーム大賞アマチュア部門](http://awards.cesa.or.jp/prize/amateur.html)
- [日本ゲーム大賞U18部門](https://u18.awards.cesa.or.jp/news/20190915/)

## 読み物
- [まちるだ / MESON. UIデザイナーでもできる！はじめてのUnity UIの教科書 ](https://note.mu/mathi0829lda/n/n0cd458dc00f6)
- [gamebiz.jp. 【CEDEC 2019】「エフェクトは人生だ」…『シノアリス』『戦姫絶唱シンフォギアXD』を担うポケラボ・池田氏がエフェクト制作の魅力を熱弁！](https://gamebiz.jp/?p=248246)
- [Sugimoto Chizuru. ゲームの仕様書を書こう](https://www.slideshare.net/ChizuruSugimoto/)
- [@odanny. 気持ちのいいジャンプを目指して](https://qiita.com/odanny/items/297f32a334c41410cc5d)

## 作業スケジュール検討
- シナリオと声の検討
  - [Fungus](https://assetstore.unity.com/packages/templates/systems/fungus-34184)
- 作品ごとに操作説明、A2のポスター制作

## 各作業状況
### ステラ
- <s>プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する</s>
- UnityTile3Dで地面を作る(半分ぐらい完了。ぴったりの場所じゃない場合、オブジェクトの位置を移動)
- エンディングの検討、製作
- プレイヤーのアニメーションを増やす
- 星モデルの作成
  - 島をゲームのステージ数分作成
  - 島と星のマテリアルを分ける
  - 汚染された色と、回復した色の2つのモデルを作成
- 星モデルの差し替え

### はんぐらびぃ
- <s>GitHubアカウントの見直し。1つ外部作業用のアカウントを登録する</s>
- <s>ブラックホールの吸い込みの検討</s>
- <s>ブラックホールが消える時のアニメ</s>
- タイトルのアルファベット表記を決めて、プロジェクトフォルダーをそれにしたものをGitHubで管理する
- クリアなどの文字を再描画
- ステージを操作に合わせて改良
- 左に押し出されるバグ修正
- ESCで終了
- ぐらびぃが落下する時のアニメ
- 以下、保留
  - 上下に移動する障害物(敵はできている。ネットドライブの卒制の中の`enemy_2.unitypackage`)
  - 敵を増やす

### マルチプレイヤーコンストラクション
- <s>フィールド作成</s>
- アイテムのストック処理
- 水のシェーダー研究


---

# 16週目(9/11, 13)
## 話題
- [@odanny. 気持ちのいいジャンプを目指して](https://qiita.com/odanny/items/297f32a334c41410cc5d)

## 後期に向けて
- シナリオと声の検討
  - [Fungus](https://assetstore.unity.com/packages/templates/systems/fungus-34184)
- 作品ごとに操作説明、A2のポスター制作

# 15週目(9/4, 6)
## 9/6
- ステラ
  - <s>ステージ選択の星の回転方法(あらかじめデータを作っておく方法 / ステージの位置から自動算出する方法)</s>
  - <s>アニメ速度、カメラのスクロールの改善、壁に引っかかるについての調査</s>
  - <s>モデルのテクスチャーの調査</s>
  - プレイヤーに壁の判定用のコライダーを追加して、それに摩擦0のPhysic Materialをアタッチする or プレイヤーの移動方法を変更する
  - UnityTile3Dで地面を作る(半分ぐらい完了。ぴったりの場所じゃない場合、オブジェクトの位置を移動)
  - エンディングの検討、製作
  - プレイヤーのアニメーションを増やす
  - 星モデルの作成
    - 島をゲームのステージ数分作成
    - 島と星のマテリアルを分ける
    - 汚染された色と、回復した色の2つのモデルを作成
- はんぐらびぃ
  - ブラックホールの吸い込みの検討
  - クリアなどの文字を再描画
  - 上下に移動する障害物
- マルチプレイヤーコンストラクション
  - フィールド作成
  - 水のシェーダー研究

## 話題
- デザイナー需要についてのツイート
  - https://twitter.com/yonasawa/status/1155842198472024066
  - https://twitter.com/yonasawa/status/1155843234905518081
- [ニコニコ自作ゲームフェス新人賞2020・応募要項](https://ch.nicovideo.jp/indies-game2020)
  - 注意。以下のようにあるので、応募するのは、好きに改変してもらって構わない作品にしてください
    - *本コンテストに応募することにより、当社及び当社が指定する第三者に対して、応募作品を自由に利用できる世界的、非独占的、無償、サブライセンス可能かつ譲渡可能な許諾ライセンス（ゲームの二次創作をするために必要な改変、編集等を含みます）を付与するものとします*
- 差支えなければ、1週間ゲームジャムの作品に「デジタルアーツ東京」のタグの設定を

## DATフェスタに向けたクオリティアップ準備
- クオリティを製品レベルに上げるための作業、研究を行う
  - 「時間が足りなかった」という言い訳はこの後は使えない。展示や会社に見せた時に、一切言い訳をしないで済むものに仕上げる
  - 常に動作するものをmasterブランチにしておく
- 作品ごとに、クオリティの低い部分、改良点を再点検して、作業項目出し
  - 遊びながら、良かった点、気になった点[Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)


## 今後のスケジュール
- 9/4, 6, 11, 13
- 2週間休み
- 10/2から5週間作業
- 11/8,9 DATフェスタ


# 応募作品の実行ファイル
- `Z:\2019年\ゲーム学科\Student\卒業制作\応募作品実行ファイル`フォルダー内に圧縮したファイルを置いてあります

# 夏休みまでの予定
- 就活をメインに、個人作品、ポートフォリオ作りなどを進める
- 試遊会を7/17(あるいは24)に実施予定。DATフェスタ版の仕様を検討し、必要なことを各自で夏休み中に準備してくることにする
  - 動画
  - 操作説明
  - 試遊会
  - DATフェスタに向けた作業項目を検討
    - 声を入れたい

# 14週目(7/24)
## 内容
- Stella
  - 金曜日にインポートしたユニティちゃんトゥーンシェーダーをマージする
  - 地面のテクスチャ差し替え
  - ポストプロセスの紹介
- ネットゲー
  - 研究を進める
- はんぐらびぃ
  - 各自、作業を進める


# 13週目(7/17, 7/19)
## 3Dモデルのポリゴン数、頂点数、ドローコール数など
- [CyberAgent, Inc. 3D美少女キャラクターをどこから見てもかわいく魅せる方法とは](https://creator.game.cyberagent.co.jp/?p=3344)
- [【Autodesk×Unity】 セガが語るUnityで作るiPhoneゲーム、そしてコンテンツ工学](https://www.inside-games.jp/article/2012/02/24/54783.html)

### 参考
- 何もない状態
  - Tris 1.7K, Verts 5K, Batches 2
- UnityChan
  - Tris 62.7K, Verts 52K, Batches 84
  - ゲーム用(一応)
- SD KohakuChanz
  - Tris 29.8K, Verts: 26.2K, Batches 51
  - ゲーム用
- LowPolyUnityChan
  - Tris 3.5K, Verts 1.9K, Batches 4
  - ライト無しテクスチャーシェーダー。ライトに反応しない
- UnityChanTPK
  - Tris 170.8k, Verts 128K, Batches 103
  - アニメーション作成用モデル
- Stella
  - Tris 12K, Verts 12K, Batches 43


## Stella - ユニティちゃんシェーダーv2を入れてみる
- [ユニティちゃんシェーダーGitHubリポジトリ](https://github.com/unity3d-jp/UnityChanToonShaderVer2_Project)
- [スライド](https://learning.unity3d.jp/1691/)
- 設定
  - Stellaのテクスチャーとマテリアルを解凍する
  - lambert2, lambert3, lambert5のマテリアルのシェーダーを、*UnityChanToonShader/Toon_DoubleShadeWithFeather*に変更
    - lambert5は、元の色をコピーしておく
  - Directional Lightの色を白にする
- 影の色の調整
  - BaseMapと1st ShadeMapに、テクスチャーをアタッチ
  - 1st ShadeMapの色を暗く調整
- 影のにじみの調整
  - *Basic Lookdevs*欄で、影のにじみを調整
- リムライト(輪郭近くを光らせてふんわりさせる効果)
  - 好みに合わせて、*RimLightSettings*を*Active*にして、調整
- アウトライン(輪郭)
  - *Outline Settings*で、色、Outline Widthを調整。線が出ない時は、*Offset Outline with Camera Z-aixs*の値を`-0.5`～`-0.75`ぐらいで調整


## 内容
- 卒業制作　再開に向けて
  - [ファミ通.com. 『ギアーズ オブ ウォー 3』で見る、Epic Gamesの開発方針](https://www.famitsu.com/news/201109/08049825.html)
  - これまでは応募を優先。**これからはクオリティを優先**
    - 「時間が足りなかった」という言い訳はこの後は使えない。会社などに見せて、一切言い訳をしないで済むものに仕上げる
- 試遊会
  - チームメンバーが前に出て、動画でゲームの紹介
  - 各自、担当項目を説明
  - 上記が終わったらしばらく試遊
  - 遊びながら、良かった点、気になった点を[Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)のコメントに書き込んでいく
- DATフェスタ版でブラッシュアップしたい項目を打ち合わせて、Trelloに列挙
  - [Ryosuke. はじめてのチーム開発、たアケイクさんと「REC」を制作しました](https://ryo620.org/2019/07/unity1week-game-jam-6/)
  - 時間があれば全体に報告
- 作業項目に従って、作業再開

# 12週目(7/10, 7/12)
## 話題
- [Unity道場 ７月～ゲーム制作に使う数学を学習しよう～](https://meetup.unity3d.jp/jp/events/1122)
- [渋谷ゆに茶会 scene07](https://t.co/TCWNlN5jDz)

## 内容
- 水曜日の最後の方に、1週間の活動報告と、来週までの活動予定報告
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- 各自作業

# 11週目(7/3, 7/5)
## 話題
- [デジゲー博2019](http://digigame-expo.org/)
  - 11/17(日) DATフェスタの次の週なので、DATフェスタの作品をそのまま展示できます
- [背景を切り取る](https://www.remove.bg/)

## 予定
- 水曜日の最後の方に、1週間の活動報告と、来週までの活動予定報告
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- 各自作業

# 10週目(6/26, 28)

## 話題
- [デジゲー博2019](http://digigame-expo.org/)
  - 11/17(日) DATフェスタの次の週なので、DATフェスタの作品をそのまま展示できます
- [背景を切り取る](https://www.remove.bg/)

## 内容
- 水曜日の最後の方に、1週間の活動報告と、来週までの活動予定報告
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- 各自作業


# 9週目(6/19, 21)
## 話題
- [paiza開発日誌. 【20卒】6月時点の内定率は7割！就活に出遅れた人もまだ間に合う面接対策](https://paiza.hatenablog.com/entry/2019/06/14/%E3%80%9020%E5%8D%92%E3%80%916%E6%9C%88%E6%99%82%E7%82%B9%E3%81%AE%E5%86%85%E5%AE%9A%E7%8E%87%E3%81%AF7%E5%89%B2%EF%BC%81%E5%B0%B1%E6%B4%BB%E3%81%AB%E5%87%BA%E9%81%85%E3%82%8C%E3%81%9F%E4%BA%BA%E3%82%82)
- [ハシラス見学会](https://hashilus.connpass.com/event/134585/)
- [NVIDIA. AIによる画像生成 GauGANのデモ](https://www.nvidia.com/en-us/research/ai-playground/)
  - https://www.youtube.com/watch?v=p5U4NgVGAwg

## 画像の命名規則の例
- [はんぐらゔぃの例](https://docs.google.com/document/d/10DWSrp2QcdawOtBvM67lr8Sjv1disyUshkcp0mc_B5U/)

## ポートフォリオ例
### デザイナー
- [お高菜. デザイナー志望者は必見！ 採用されるポートフォリオを作る「た行」の法則](https://www.e-aidem.com/ch/jimocoro/entry/otakana01)
- [望月 重太朗. た行で考える、採用ポートフォリオの作り方（主にクリエイティブ職向け）](https://note.mu/jyushok/n/n39429686354a)

### エンジニア
- [Chomado’s Portfolio (ちょまど)](https://chomado.com/)
- [Hakone's portfolio](http://hakone-gamedev.strikingly.com/)

## 内容
- 水曜日の最後の方に、1週間の活動報告と、来週までの活動予定報告
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- 各自作業

# 8週目(6/12, 14)
## 内容
- 水曜日の最後の方に、1週間の活動報告と、来週までの活動予定報告
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- (メンバーが揃ったら)発表と試遊会
  - 動画
  - 操作説明
  - 試遊会
    - [感想をこちらに](https://docs.google.com/document/d/1sh3h10addQhuQ0HgrUIypdQbOhU7obgQP-ehP0mfrds/edit?usp=sharing)
  - DATフェスタに向けた作業項目を検討
    - 声を入れたい
- 各自作業

# 7週目(6/5, 7)

## 話題
- [チュートリアル / Mayaで始めるゲーム用ローポリキャラモデル](https://twitter.com/autodesk_me_jp/status/1134404713682620416)
- [ワンボタンキーボード](https://twitter.com/tokyo_ff/status/1135864070144270338)
- VR方面の転職アドバイスのツイート。参考までに・・・[こちら](https://twitter.com/waffle_maker/status/1135854312641290240)
- [日本ゲーム大賞U18部門 予選大会 6/9](https://u18.awards.cesa.or.jp/)

## これからの進め方
- これから夏休みまで、就職活動を主軸にする
  - https://www3.nhk.or.jp/news/html/20190601/k10011937351000.html
  - 作品作りは継続してよいが、没頭して就活をおろそかにしないこと
- 水曜日の最後に、成果と次の1週間の予定を発表(来週から)
  - [Trello](https://trello.com/b/Y4V79jLx/0%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C)に箇条書き
- その他
  - **はんぐらゔぃ**と**戦艦VR**を教員参加のEXプロジェクトとして動かす予定
    - ポートフォリオに、リソースの活用事例として掲載できるようにする
    - VRは体験入学の際のデモに活用を検討
    - 作成済みのリソースを活用するので、作業は発生するとしてもフォーマットの変更程度の予定です
    - DATフェスタなどへの展示は学生作品なので、学生作品は引き続き学生チームで開発を進めてください

## 内容
- バージョンについて
  - [Report Hot Cafe. アルファ版・ベータ版・RC版って？](https://report.hot-cafe.net/alpha-beta-rc-7036)
  - 応募したのは、実質的にはアルファ版
- 最終バージョンを、`Z:\2019年\ゲーム学科\Student\卒業制作\日本ゲーム大賞作品のリソース提出`フォルダーに提出
- 就職活動に向けて、作成した作品をポートフォリオ向けにまとめる
  - プロジェクトを整理する(現状の活動に支障がない範囲で)
    - ファイル名など、規約を決めてリネームや配置換え
      - 参考: [Classmethod. 【日本語でファイルを作成しているデザイナーのあなたへ】デザイナーへのファイル命名のススメ](https://dev.classmethod.jp/etc/designer-faimename/)
    - 不要なファイルをプロジェクトから削除


---


# 5月末までの予定
- 4/17 企画の方向性出しと声入れができそうかの検討
- 4/19 企画の素案決定
- 4/26 企画を正式決定してプロジェクト作成とモック画面の作成開始、作業のリストアップ
- **5/9** モックアップ画面仕上げ。細谷先生の画面チェック
- 5/31 応募

# 役割
- プランナー：サムネイル、世界観、プレイヤー設定、操作、ルールをまとめる
- デザイナー：モックアップ作成、キャラクターデザイン、UIデザイン
- プログラマー：プロジェクト作成、作業予定の作成、仕様の調査



# 6週目(5/29, 31)
## 5/31 応募
1. 応募書類の作成
  - [応募要項](http://awards.cesa.or.jp/amateur/guideline/index.html)
  - [応募方法](http://awards.cesa.or.jp/amateur/entry/index.html)
2. 実行ファイルの作成
  - メンバー名やチーム名、学校名を入れないこと
  - ビルドして作成されるフォルダーをまるごとzip圧縮する
    - [データの作成、応募の手順](http://awards.cesa.or.jp/amateur/entry/gigafile.pdf)
3. 動画の作成
  - メンバー名やチーム名、学校名を入れないこと
  - [ゲーム動画の撮影方法](https://github.com/dat18/gp2#6%E5%9B%9E%E7%9B%AE530)
  - 参考(これらは受賞後に作成されたものなので、学校名やチーム名、メンバー名が入っていることがありますが、応募時には入れないので注意してください)
    - https://www.youtube.com/watch?v=-9LJaz6H7xE
    - https://www.youtube.com/watch?v=9Ps5Cri7LKc
    - https://www.youtube.com/watch?v=jKeXMkEY-OA
4. 応募
  - [応募フォーム](https://amateur-jga2019.com/form/)
    - 説明をしっかりと読んで正しく入力してください
    - 利用したアセットや素材(特に音関連)は、**過去作品素材の流用に関する自己申告**の欄にすべて記載するようにしてください

以上を完了させてください。

## 自分の担当部分が終わっている人は...
- 作成した素材やプロジェクト、ビルドした実行ファイルを提出する
  - 提出先は、`Z:\2019年\ゲーム学科\Student\卒業制作\日本ゲーム大賞作品のリソース提出`フォルダーの中に、キャラデザコースは自分の名前のフォルダーを作成、プログラムコースは実行ファイルを含むUnityのプロジェクト一式をまるごとコピーして提出してください
  - グラフィック素材は、プログラムに組み込むために書き出したものと、元のデータのどちらもコピーしてください
- 終わっていない部分で、自分が担当できる部分があれば引き受けて作業を進める
- テストプレイをする
- 就職活動に向けて、作成した作品をポートフォリオ向けにまとめる
- などなど

---

## 話題
- [日本ゲーム大賞U18部門 予選大会 6/9](https://u18.awards.cesa.or.jp/)

## 準備ができているチーム
- 5/29
  - 応募資料の作成
  - プレイ動画を取りながらテストプレイをして、ブラッシュアップ項目をTrelloにリストアップ
  - 動画を作成して、仮応募を完了させる
- 5/30
  - ブラッシュアップ項目や前日までに完成せずに仕様から外したものの開発(20時まで作業可)
- 5/31
  - 5/30までに新しく作ったものを組み込み
  - 最終版を再提出
    - 手を入れると、予想外のところに不具合が入る。必ずすべてが正しく動作することを確認すること

## 未完成のチーム
- 5/29 制作と応募資料作成に分ける
  - ゲームの完成に不足なものがある人達は、開発を進める
  - 担当が完了している人達で応募資料を確認して、動画以外は完成させる
- 5/30
  - 完成に必要なものの開発を完了させる。終わっていない場合は20時まで残って作業すること
- 5/31
  - 5/30までに新しく作ったものを組み込み
  - 動画作成を作成して提出

# 5週目(5/22, 24)
## 作品のバージョン
- 5月末
  - Ver1. 日本ゲーム大賞アマチュア部門応募バージョン
- 11月冒頭
  - Ver2. DATフェスタ、デジゲー博展示バージョン
- 3月
  - Ver3. パッケージバージョン

### 日本ゲーム大賞アマチュア部門応募バージョン　応募までの流れ
- 今日
  - 現在完成しているもんを確認して、ゲームの最小の仕様を決める
  - Unityのプロジェクトに現在できているものを組み込んで統合
  - ビルド
- 5/28まで
  - 日本ゲーム大賞アマチュア部門応募バージョンの完成
- 5/29(水)
  - 応募を完了させる
- 5/31(金)まで
  - 仕上げをして、最終版を提出

### 5/24作業予定
- [ ] チームで完成しているものを確認して、その要素で作れる最小のゲームの仕様を決める
- [ ] すべてのリソースをUnityプロジェクトに統合
  - 未完成のもので、省いてもゲームを完成させられる要素は、一旦、製作中止
  - 未完成のもので、省けないものについて、仮でよいのでデータを作成してプロジェクトに組み込む
- [ ] ビルド

以上完了したら、共有ドライブの `Z:\2019年\ゲーム学科\Student\卒業制作`の各チームのフォルダー内に、**Unityのパッケージ**と、**ビルドした実行ファイル一式**をコピー

# 4週目(5/15, 17)
- 残り2週間での作業の配分をTrelloを見ながら報告
- 木曜日の報告まとめ
- 不明な点の質疑応答

# 3週目(5/8, 9,10)

## 5回目予定(5/10)
- **チーム作業は難しい！！**
  - だからこそ、技術力だけではなく、コミュニケーション力も求める企業が多い
    - [ORANGE POS. ITの開発エンジニアにslackが人気な理由](https://orange-operation.jp/posrejihikaku/sharing/14026.html)
  - *乗っかること、褒め合うことで、チームワークがよくなる。*
    - [面白法人カヤック. 3. 始まりも終わりもブレスト](https://www.kayac.com/vision/brainstorm)より
- 応募要項の確認
  - [応募要項](http://awards.cesa.or.jp/amateur/guideline/index.html)
  - [応募方法](http://awards.cesa.or.jp/amateur/entry/index.html)
- 今回の目的のおさらい
  - コンテストへの応募の実績作り
  - ポートフォリオの素材作り
  - 就活の面接の際に、チームへの関り方、工夫についての話題作り
- 企画の仕様決定
  - 今後の2週間で完成させるための計画作り
  - 木曜日に出た話し合いの議題について結論を出す
  - ゲームの開始から終了までの流れを追って、必要な素材、処理を列挙
  - 作業リストを「必須」と「可能なら」で割り振る(ラベルを利用するとよい)
  - 決まらなかったことをリストアップしておく


## 5/9(合同講義 A601)
- 現在のゲームの内容について、画面を提示しながら細谷先生にプレゼン
- 細谷先生から画面の評価を受け、今後の方針をまとめる

## 4回目予定(5/8)
- Unity上(無理そうならPhotoshop上)で、ゲーム画面を構築する
  - プレイヤー
  - 背景
  - 敵
  - UI

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
- 開発を始められるように以下を決める
  - プレイヤーのアクションを一通り洗い出し
  - 簡単なマップと、最低限の仕掛け(チュートリアルステージ的なもの。仮の短いものでよい)

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
