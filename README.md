# Doki Doki Literature Club 日本語化パッチ(19/05/04)

## インストール方法
詳細は [Steam ガイド](https://steamcommunity.com/sharedfiles/filedetails/?id=1296040205) を参照してください

1. Steam または公式サイトから Doki Doki Literature Club! 本体 をダウンロードします
2. DDLCのインストールディレクトリを開きます
3. インストールディレクトリ内のgameフォルダを日本語化パッチ内のgameフォルダで上書きします
4. 起動してメッセージやタイトルが日本語になっていれば成功です
   英語のままの場合は Setting の Language を Japanese に変更することで日本語になります


## オマケ機能
- 詩の表示中はオート機能を解除する機能があります。
  v1.1.1からは標準搭載ですが、挙動が異なるので残してあります。

- あるシーンに日本語圏向けの修正を入れています。
  ネタバレになるので詳細は伏せます。

- 別売りのFan Packを購入している場合、エンディングに歌詞が付きます。
  日本語・英語両方対応していますので、興味があったら買ってみて下さい。


## 既知の不具合
- オプションや詩などが正常に表示されない
  以下の手順で直るようです。
  1. DDLCを通常起動
  2. Shift+Gキーでグラフィックアクセラレーションを起動
  3. Angle/DirectXを選択

- 言語を切り替えてもバックログが真っ白or英語のまま
  Ren’Pyの仕様です。

- 言語を切り替えても反映されない箇所がある
  このパッチの仕様です。次の台詞はちゃんと現在の言語で表示されます。
  作詞の場合はセーブ＆ロードで切り替えが反映されます。
  " "が付かないのとナツキ＆ユリの名前欄は仕様です。ごめんなさい。

- 中途半端な場所でタイトルに戻される
  日本語化パッチを更新した後、古いセーブデータから再開すると起こることがあります。
  申し訳ありませんが、ニューゲームからやり直して下さい。

- 翻訳が反映されない箇所がある
  原因不明です。Steam ガイドに原文と翻訳を載せてあります。
  またそれ以外の台詞で未翻訳箇所がありましたらガイドコメントや Discord、GitHub などでご連絡下さい。

- Linux環境での不具合
  ガイドに載せてあります。終盤のネタバレ注意。


## 使用フォント
VLゴシック[UI](http://vlgothic.dicey.org/license.html)
みかちゃん[UI](http://www001.upp.so-net.ne.jp/mikachan/)
ホリデイMDJP03[サヨリ](http://mksd.jp/Holiday_Kanji.html)
851手書き雑フォント[ユリ](http://www39.atpages.jp/yagoinienie/851fontpage.html)
草書フォント[ユリ](https://booth.pm/ja/items/318557)
さなフォン[ナツキ](http://sana.s12.xrea.com/2_sanafon.html)
るりいろフォント[モニカ](http://sapphirecrown.xxxxxxxx.jp/)
xano明朝フォント[特別な詩](http://www.asahi-net.or.jp/~sd5a-ucd/freefonts/XANO-mincho/)
えり字フォント[特別な詩](http://v7.mine.nu/pysco/gallery/font/06.html)


## 関連リンク
- [配布ページ(Steam ガイド)](https://steamcommunity.com/sharedfiles/filedetails/?id=1296040205)
- [Doki Doki Literature Club! 日本語化 作業所](https://docs.google.com/spreadsheets/d/1uqyB7x-8x_QSFKV8Um-rCwcLVUduf-FMhAZjocUGmJY/edit?usp=sharing)
- [DDLC翻訳部 (Discord)](https://discordapp.com/invite/9U9QCN2)
- [日本語化パッチのソースコード (GitHub)](https://github.com/proudust/ddlc-jp-patch)


## 更新履歴
### 190504
- Act4で翻訳が反映されない台詞があったのを修正
- READMEを更新 (06/13)

### 190216
- DDLC v1.1.1で追加・修正された台詞に対応
- 翻訳の修正

### 180314
- 字の縁が太くなりました
- オプションからオート時に詩も自動送りするかどうかを選択できるようにしました
- 翻訳の修正

### 180217
- 誤字訂正

### 180212
- ミスで数カ所の変更/バグ修正が反映されていなかったのを修正
- 誤字訂正

### 180210
- テスト終了、完成版リリース
- Act3のタイミングずれを修正
- 翻訳更新

### 180205
- ゲーム内からヘルプを開くとき、言語設定が反映されるように
- デバックコンソールを再度有効に
- Act2ラストでバックログが翻訳されないのを今度こそ修正
- 翻訳更新

### 180203
- Act1ラストのニセエラー文が翻訳されない不具合を修正
- Act2ラストでバックログが翻訳されないのを修正
- monika.chrとyuri.chrの翻訳を更新
- 翻訳更新

### 180128
- 今度こそニコ生に対応
- 作詞画面の言語切替に再起動が必要だったのを修正
- 多数の不具合を修正
- 翻訳更新

### 180127
- none.rpaを追加（字幕の追加など日本語に限らない変更）
- script.rpaの上書きが不要に
- poemword.txtが不要に
- 言語切替を実装（英語でもEDに字幕付きます）
- Act3作詞の翻訳を追加
- monika.chrとyuri.chrの翻訳を追加
- アンケート結果を受けてJust Monikaの翻訳を更新
- 詩の表示でオートが解除されるように
- 翻訳更新

### 180122
- Act1ラストのニセエラー文の翻訳を追加
- Act1ラストの終了ダイアログの翻訳を追加
- Act2ラストで一部イベントがスキップされる不具合を修正
- Ren'Pyコンソールのフォントが反映されていないのを修正
- 一部立ち絵が切り替わらない箇所があったのを一部修正
- 翻訳更新

### 180120
- フォントをパック（"gui/font"フォルダが不要に）
- 対応配信ソフトにNicoliveenc.exeを追加
- 日本語版poem_end.pngを追加
- Act1ラストのUI、ログの翻訳を追加
- Act2ラストの出力ファイルの翻訳を追加
- ユリのAct2最後の詩を少し修正
- macやlinuxでの起動時エラーを多分修正
- 翻訳更新

### 180119
- エンディングに歌詞を追加(DDLC Fan Packがある場合のみ)
- バックログの翻訳漏れを修正
- ナツキのフォントをさなフォンに変更
- 翻訳更新

### 180116
- 翻訳が反映されない不具合を多数修正
- 翻訳更新

### 180114
- エンディング歌詞前の砂嵐に字幕を追加
- ユリの詩とエンディング歌詞のフォント名を修正
- 翻訳更新
