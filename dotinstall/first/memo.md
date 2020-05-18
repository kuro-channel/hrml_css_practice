#### マークアップは意味を持たせること

#### headとheaderタグの違い
- head: 文章全体に対する情報を入れるためのもの
- header: bodyタグの中で使うヘッダー的な要素に入れるためのもの
- footer: 文章のフッター的要素

#### CSS: ボックスモデル
- ボックス： 要素それぞれに生成される四角形（矩形：長方形）の領域
- 内容（content）: 要素に含まれる内容
- padding： 内容とボーダーとの余白
- border： 枠線
- margin： ボーダーと隣接する要素との間隔
- width, height: 内容（content)の幅：widthと高さ:heightを指定する。

#### displayプロパティ
- div: デフォルトで「display: block」
- display: inline-box 幅と高さが設定できる
- MDN: https://developer.mozilla.org/ja/docs/Web/CSS/display
- https://saruwakakun.com/html-css/basic/display サルワカ

#### 属性セレクタ
- []
- 

#### 擬似要素
- サルワカ　https://saruwakakun.com/html-css/basic/before-after

#### セレクタ組み合わせ
```html
```
```css
```

#### 気になることまとめ
- width: 親要素のサイズを引き継ぐ

- marginの相殺　https://coliss.com/articles/build-websites/operation/css/about-collapsing-margins.html
  - MDN: ブロックの top と bottom のマージンは結合される（折り畳まれる (collapsed)）ことがあり、**結合されるマージンのうち大きなほうのサイズを持った一つのマージンになります**。この動作は マージンの相殺 (margin collapsing) として知られています。
  - https://developer.mozilla.org/ja/docs/Web/CSS/CSS_Box_Model/Mastering_margin_collapsing