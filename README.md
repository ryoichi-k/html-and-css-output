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
→層のように積みあがる


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
```css
<small>©aiueo.inc</small>
```

HTMLのコンテンツカテゴリ
  
## Flexbox
使い方：横並びにしたい要素の親要素にdisplay:flex;を付ける。

この場合の親要素は「フレックスコンテナ」という。
このフレックスコンテナにプロパティを指定することで横並びにできる。

## ページ全体のフォントを設定する
bodyにfont-size,font-family,colorの3つのプロパティを指定すればいい。

## セレクタ
nav内のulのliのみに適用。
nav ul li{ }

## ショートハンド
cssを一気に適用させる書き方をこういう。
  
### ボックスの影
```css
box-shadow: ;
```

### リスト項目
  ```css
list-style-type: ;
```
  disc,circle,square,decimal,none
  
### はみ出る部分をどう対処するかoverflow　横　縦
  ```css
overflow: hidden scroll;
```  
  
  visible→はみ出して表示
  
  hidden→非表示
  
  scroll→スクロールできるように
  
  auto→ブラウザに任せる
  
  ## divとspanタグにはcss適用以外の意味はない
  
  ## 行間の高さを調整する　line-height:～;
  
   ```css
line-height: 1.5;
```  
行間は1.5～1.8がおすすめ。単位なしを推奨


## ページ内リンク→<a href="#id">

