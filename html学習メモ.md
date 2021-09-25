## 最初にやる事

-   !で雛形を出す
-   title を好きな名前にかえる - タブの部分に設定した名前が入る
    <br>  
    <br>
-   meta name のところに discription と打つと、web サイトの説明が書ける
-   content の中に説明文を書く

```html
<meta name="discription" content="コーヒい美味しいよ" />
```

<br>

-   link icon でタブの部分の画像を設定できる
-   href の宇文に画像のパスを書く

```html
<link rel="icon" href="images/favicon.png" />
```

<br>

-   css の読み込み

```html
<link rel="stylesheet" href="css/style.css" />
```

<br>

-   ブラウザ間の表示をうまくさせるためにリセット css を読み込む

```html
<link rel="stylesheet" href="css/bootstrap-reboot.css" />
```

#### ul タグ

li タグと一緒に使う  
順序がないリストを使うときに使うタグ  
順序があるパターンは ol タグを使う  
<br>

#### ol タグ

li タグと一緒に使う  
順序付きのリストを使うときに使うタグ  
type 属性に数字やローマ字を入れると自動的にインクリメント的な動きする。  
start 属性を使うと、任意の開始番号を指定することも可能

#### アウトラインとは

アウトラインとは、HTML 文書から見出し（h1 ～ h6 要素）だけを抜き出して、文書内のセクションとその階層を示したものです。
