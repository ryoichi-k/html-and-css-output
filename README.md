# html-and-css-output
html and css warehouse
HTMLのインデントはタブ

cssファイルの先頭
```css
@charset "utf-8";
```

ボックスモデル
→htmlでマークアップされたものが持つ四角い領域を構成する6つのCSSプロパティのこと

width,height,border,padding,margin,content

ブロックボックスとインラインボックス
htmlでマークアップされたものは上記のどちらかの性質を持っている。

ブロックボックス
→可能な限り横幅いっぱいの領域をとろうとする性質がある。
→margin,paddingなどを四方に指定できる。
→


インラインボックス
→a,em,imgタグ

インラインボックスは主にブロックボックスの中に含まれる。
マークアップしたコンテンツの幅と同じ幅の領域になる。
→幅と高さは要素の中身によって変化する。
→marginとpaddingは左右のみ指定可能

ボックスレイアウトの種類を指定するプロパティ
```css
display: block;
```

文書構造
ローカルナビゲーション→同一カテゴリのページ同士をリンクするナビゲーション

ナビゲーション→<nav>
補足エリア→aside
記事・自己完結している要素→article
  
<section>タグ
アウトラインを明確にする。本で言う第1章
→クローラーの理解を助ける働きがある。見出しとセットで使うケースが多い

日時を表すタグ<time>

copyrightのやつ<small>
<small>©aiueo.inc</small>




