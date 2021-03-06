Emacs vs Vim
==================================================

巷では ``Emacs`` vs ``Vim`` 戦争というのが昔からあるそうで、よくネタになっています。
ですが、僕自身は特に「Emacs信者」というわけではないです。
Emacsしか使えない、ただのポンコツです。
Vimの基本操作もできるようにしといた方がいいと思っています。

ただし、この章のはじめにも書きましたが、快適なプログラミングを行うにあたって
「 **自分に合ったエディタ** 」を選択するというのは重要なことだと思います。
思った以上に長いお付き合いになるので、愛着を持てるエディタを選びましょう。

僕の場合は修士でプログラミングを始めた時に、
最初に触ったのがEmacsだったというのが主な理由です。
Mac（のCocoaアプリ）もEmacsキーバインドで移動ができるのも大きな理由でした。

最初はこれまで使っていたテキストエディタと
同じように矢印キーなどで操作していました。
ウェブなどでキーバインドを確認しながら、
だんだんと操作方法を覚えていった気がします。

最近では `guru-mode <https://github.com/bbatsov/guru-mode>`__
なるパッケージもあるので、これを入れて練習したらいいと思います。
マニュアルにある通りにインストールして、
``(setq guru-warn-only t)`` するだけで有効になります。
矢印キーなどを押すとミニバッファに適切なキーバインドが表示されるので、
使いながら覚えるのにピッタリです。
後述するPreludeにはデフォルトで入っています（というか同じ作者みたい）。
