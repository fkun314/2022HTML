:::note warn
配布プリント修正

配布した資料の一部を訂正します。
１、スタートボタンについてコードの記載が抜けていましたので追加させていただきます。

修正前：```<button type="button" class="btn btn-primary w-100 btn-lg">Start</button>```

修正後：```<button type="button" class="btn btn-primary w-100 btn-lg" id="start">Start</button>```

２、ストップボタンについてコードの記載が抜けていましたので追加させていただきます。

修正前：```<button type="button" class="btn btn-primary w-100 btn-lg">Stop</button>```

修正後：```<button type="button" class="btn btn-primary w-100 btn-lg" id="stop">Stop</button>```

index_complete.htmlという完成したファイルを用意していますのであわせてご覧ください。
:::

# プログラム説明

本プログラムは2022年プログラミング体験用に作成したものです。
* index.html：体験に使用したファイル
* index_complete.html：体験後のファイル
  
こちらプログラムは右上の緑色の```Code```と書かれたボタンを押して```Download ZIP```と押すとZip形式でダウンロードできます。展開してお使いください。

## 概要
今回のストップウォッチにはHTML/CSS/JavaScriptを用いたプログラムを作成しました。
* HTML: Webページの文字を書く部分。記事。</li>
* CSS: Webページに飾り付けを行うプログラム。フォントの変更や背景色の変更などができる。</li>
* JavaScript: WEbページに高度なプログラミングを可能とする言語。静的なサイト（シンプルなサイト）から動的なサイト（複雑、高性能なサイト）へ進化させるのに使用する。

## ファイルの説明
メインとなっているindex.htmlにはこれらHTML/CSS/JavaScriptがまとめて入ってあります。

HTMLは<>の中にh1、p、divなどを入れて使います。プログラム中でもたくさん使用されていることがわかるかと思います。

その中で```<style></style>```と書かれている部分にCSSが書かれています。CSSはHTMLとは書き方が異なるので気になったら調べてみてください。基本的には、どこに、どのように、がベースとなって書かれています。

そして```<script></script>```と書かれている部分がJavaScriptの部分です。JavaScriptが一番プログラミングとしての形をしているかと思います。JavaScriptでは変数や繰り返す処理のfor文、分岐処理のif文なども使用でき、今回のストップウォッチの動作部分はこのJavaScriptで作られています。仕組みとしてはスタートボタンを押した時間を記録しておき、現在時刻との差がストップウォッチの値になります。

また、今回の体験ではスタートから~~１０秒後~~５秒経過してからストップできれば背景が変化するようなプログラムを組んであります。これは変数colorに代入されたRGB値をそのまま背景色として使用しているので、背景色が簡単に変わるようになっています。

