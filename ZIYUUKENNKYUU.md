# HTML,CSS,JavaScriptでWebアプリケーションを開発する
Github Pagesで公開した→ https://ben4536925.github.io/web-clock
> [!note]
> これは元々Googleドキュメントで作成したものを一部改変してコピーしたものです

# 研究の動機
僕の将来の夢は「プログラマー」です。
今までは、ほとんどブロック言語を使ってプログラミングをしていたが、一歩進んでテキスト言語を使ってちゃんとした1つの作品を作りたいと思った。
今までも、テキスト言語を使って、少し遊んでいたことがあったけれど、未完成なものが多かったので、しっかりとした完成品を作ろうと思った。
# 研究の課題
- 何を開発するか
- 詳細な仕組みをどうするか
- なんの言語で開発するか
# 研究の方法
Q.何を開発するか
A.作るソフト web clock
時計のアプリ　Webで動く(exeとかのダウンロードだと試すのが大変なため)
|項目|値|
|-|-|
|機種|ESPRIMO D582/G|
|CPU|i7-3770(win11非対応)|
|RAM|16GB|
|OS|Windows11 Pro(チェックリスト回避)|

条件とか
|使う技術|HTML,CSS,JavaScript|
|-|-|
|開発環境|Visual Sudio Code + Webブラウザ|

行う制限
- AIなどなるべく利用しない
# 研究の実践
## 詳細な仕組みを考える
- Material Design 3を使う
- タブ
  - 項目
    - ホーム
    - ストップウォッチ
    - 設定
  - Material DesignのTabを使う
- ホームタブ
  - 時計はH:mm:ss形式
  - 日付はyyyy/M/d形式
  - 日付は時計の1/4サイズ
- ストップウォッチタブ
  - mm:ss:ms形式
  - スタート&ストップボタンとリセットボタン
- 設定タブ
  - Material Designのlist、Sliderなどを使う
  - 文字サイズ(自動&手動)
  - 秒表示
  - 色(色彩のみで明るさ、濃さはなし)
## 実装をする
  画像挿入予定...
作成風景
  画像挿入予定...
Developer Toolsで性能を制限してどれだけ動くかの確認
## Github Pagesに公開
  画像挿入予定...
# 研究の結果
HTML、CSS、JavaScriptを使って一つ、Webアプリを作って、Github Pagesに公開することができた。
# 研究の感想
HTMLだけは、少し前にも使ったことがあったけど、CSS、Javascriptは、あまり使ったことがなかったから、今回その二つも学べて良かった。あと、作ったけど、あまり触ったりしなかったGithubとかも、今回の自由研究で活用できて、使い方とかを、学べた。
# 研究の反省
AIをなるべく使わないと言ったけど、少しだけ使ってしまった。
スマホとかでのテストをあまりしていなかったから、完成後、スマホなどで見ると、レイアウトが崩れたりしてしまった。
  画像挿入予定...
↑PCで全画面表示
  画像挿入予定...
↑Developer ToolsでiPhone14ProMaxとして表示させた
# 参考文献
MDN Web Docs - https://developer.mozilla.org/ja/

Material Symbols and Icons - https://fonts.google.com/icons?icon.style=Rounded

SIMPLE CLOCK  - https://clock.shirokuma-lab.com(ソースコードを閲覧)


【JS】経過時間を取得する - https://qiita.com/mtoutside/items/653abb35447f4977a9f0

要素同士を重ねて表示する方法 - https://qiita.com/kuuuuumiiiii/items/a519658dba9582d99505

Local Storageを使ってみる - 
https://qiita.com/masuda-sankosc/items/cff6131efd6e1b5138e6
