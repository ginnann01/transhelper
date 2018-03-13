# transhelper
2段組の論文PDFとかでコピペで入る改行を消して[Google翻訳](https://translate.google.com)とかにぶっこめるようにする

# 流れ
英語苦手だけど論文読まなきゃ・・・  
そうだ！Google翻訳使うンゴ！  
でも，2段組論文のPDFとかだとコピペした時に改行が入って修正が面倒やね．  
というわけで作りました．改行消すやつ．  

# 機能
* 改行をスペースに変えます  
  '\n' -> ' '
* ハイフンと改行が並んでる場合はまとめてスペースに変えます  
  '-\n' -> ' '

# 使い方
1. 左側にPDFからコピペします  
2. Convertボタンを押します  
3. 右側に改行が取り除かれたのが表示されます  
4. ついでにクリップボードに自動的に右側のテキストがコピーされてるので，  
   あとはGoogle翻訳にCtl+vするだけ！  

# 開発・実行環境
<dl>
<dt>TransHelper.py</dt>  
<dd>Enthought Canopy 2.1.6</dd>
<dd>Python 2.7.13</dd>
<dd>PySide 1.2.2</dd>
</dl>

<dl>
<dt>TransHelper_3.py</dt>  
<dd>Enthought Canopy 2.1.8</dd>
<dd>Python 2.5.2</dd>
<dd>PyQt5</dd>
</dl>
