# report222-imgprocessing
今回はガウシアンフィルタを用いてフィルタリングを行った、 
また、valueを１にするとgrayスケールに変換するようにした、
また、histを１にするとヒストグラムを平坦化するようにした。
GUIを使ってインタラクティブにパラメータを変えられるようにした。 
今回のプログラムでは"q"または"esc"キーを押すことでカメラを終わらせられるようにした。 
環境は"opencv ver 3.3.1""numpy ver 1.14.5"で行った 
参考：https://www.blog.umentu.work/python-opencv3%E3%81%A7gaussian%E3%82%AA%E3%83%9A%E3%83%AC%E3%83%BC%E3%82%BF%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E5%B9%B3%E6%BB%91%E5%8C%96/
このページのgauss.pyのサンプルコードのフィルタ処理の部分を引用した。 
またBB9に乗っていたminimal sampleを一部改変した。 実行の例：
https://www.youtube.com/watch?v=lnFEc_VE1ms
youtubeに飛びます。
