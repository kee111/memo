# 不用ファイル削除

React ファイルを作った時に無駄なファイル整理するのだるいので、コピペで綺麗になるように手順を書く。

<br>

## React ファイル作成

```
npx create-react-app プロジェクト名
```

## index.html の中身

```html
<!DOCTYPE html>
<html lang="ja">
    <head>
        <meta charset="utf-8" />
        <title>React App</title>
    </head>
    <body>
        <div id="root"></div>
    </body>
</html>
```

<br>


## index.js の中身

```js
import React from "react";
import ReactDOM from "react-dom";
import "./index.scss";
import App from "./App";

ReactDOM.render(<App />, document.getElementById("root"));
```

<br>

## App.js の中身

```js
import React from "react";

function App() {
    return (
        <div>
            <p>Hello React.</p>
        </div>
    );
}

export default App;
```

<br>

## 不用ファイル削除 & index.scss作成

ルートディレクトリで実行

```
rm -rf public/*.ico public/*.png public/*.json public/*.txt
rm -rf src/*.svg src/serviceWorker.js src/App.test.js src/*.css
touch src/index.scss
mkdir src/components
```

<br>

## scss のインストール
こいつがコンパイラしてくれるので、拡張機能のlive scssは使わなくて良い。  
拡張機能がonになっていると余計なファイルが作られるので、offにしておくこと。
```
npm install sass
```
