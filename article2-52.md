# 環境設定

## Inkscapeのインストール

まずはInkscapeの公式サイトにアクセスします。
<br>
http://www.inkscape.org/en/

次に上部のバーにあるダウンロードにマウスオーバーしてOSを指定します。
<br>
![](ink1-01.jpg)

<br>

### Mac OS の場合

#### XQuartzのダウンロード

MACの場合、Inkscapeを使用するにはXQuartzが必要となりますので、まずXQuartzをダウンロードします。
<br>
赤い矢印のところをクリックすると自動的にダウンロードが始まります。
![](ink1-02.jpg)

ダウンロードが完了するとXQuartz-X.X.X.dmgがアイコンとして出てくるのでダブルクリックします。
<br>
![](ink1-03.jpg)


中にある「XQuartz.pkg」をダブルクリックします。
<br>
![](ink1-04.jpg)

インストールが開始します。
すべて「続ける」をクリックします。
<br>
![](ink1-05.jpg)
<br>
![](ink1-06.jpg)
<br>
![](ink1-07.jpg)

「同意する」をクリック
<br>
![](ink1-08.jpg)

「インストール」をクリック
<br>
![](ink1-09.jpg)

OSXのログインパスワードを入力します。
<br>
![](ink1-10.jpg)

インストールが開始します。
<br>
10分程度の時間がかかります。
<br>
![](ink1-11.jpg)

これでXQuartxのインストールが完了です。
<br>
![](ink1-12.jpg)

<br>

#### Inkscapeのダウンロード(MAC)

次にInkscapeをダウンロードします。
<br>
まずこのアイコンをクリックします。
<br>
![](ink1-13.jpg)


この画面５秒ほど待ちますと自動的にダウンロードが開始します。
<br>
![](ink1-14.jpg)


ダウンロードが完了したらInkscape-0.48.5-2+X11.dmgをダブルクリックし、ファイルを展開します。
<br>
展開すると下の様なウィンドウが出てくるのでInkscapeのアイコンをApplicationにドラッグ&ドロップします。
<br>
![](ink1-15.jpg)


インストールはこれで完了です。

<br>

#### Inkscapeの起動(MAC)

次にLaunchPadからInkscapeを起動します。
<br>
このような画面が出てくる場合、「システム環境設定」から「セキュリティとプライバシー」を選択します。
<br>
一番下にある「このまま開く」を選択します。
<br>
![](ink1-16.jpg)


このウィンドウが現れるので画面右下の「Browse...」を選択します。<br>
![](ink1-17.jpg)

「アプリケーション」→「ユーティリティ」に XQuartz があります。
<br>
XQuartz を指定して「Choose」をクリック。
<br>
![](ink1-19.jpg)

このまま起動しないので一旦システムを再起動します。
<br>
再起動後、もう一度Inkscapeを起動してください。
<br>
OKをクリックします。
<br>
![](ink1-20.jpg)

Inkscapeが起動します。
<br>
![](ink1-21.jpg)



## Windowsの場合

好みの形式を指定してダウンロードサイトにアクセスします。
<br>
![](ink1-22.jpg)

矢印の部分をクリックしてダウンロードを開始します。
<br>
![](ink1-23.jpg)

#### インストール方法

特に指定がない場合は「次へ」を押してインストールします。




## Inkscapeを日本語化する方法

「File」から「Inkscape Preferences」を開きます。([shift] + [control] + [P])
<br>
![](ink1-24.jpg)

Interfaceを選択してください。
<br>
LanguageでJapanese (ja) を選択します。
<br>
![](ink1-25.jpg)

Inkscapeを再起動すると日本語化完了です。
<br>
![](ink1-26.jpg)

※日本語化した後に起動するとエラーとなり起動できない場合があります。
<br>
その場合は下記の場所にあるファイルをテキストエディタで開き、編集して下さい。

[場所]
　inkscapeのアプリケーションファイルを右クリックし「パッケージ内の内容を表示」>「Contents」>「Resources」>「bin」>「inkscape」

[変更内容]
<br>
 153行目に1行追加し、内容を「export LANG=ja_JP.UTF-8」 として保存。
<br>

変更して保存後、Inkscapeは問題なく起動することができます。