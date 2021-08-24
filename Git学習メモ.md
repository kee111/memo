-   git init

    -   このコマンドを使うとギットハブを使う為のファイルが生成される。
        .git が作られる

-   git remote add origin ssh の URL

    -   これをコピペすると行き先場所の設定

-   git add git add.

    -   出荷前の荷物をまとめる感じ
        .をつけると全部

-   git commit -m 　”あああ”

    -   出荷するときの名前をつけれる

-   origin

    -   行き先の url のこと

-   git push origin master

    -   オリジン(url)のに出荷します

-   出荷のやり方

    -   .git があるディレクトリまで行ってコマンドを打たないと出荷できない。

-   git clone ssh の URL

    -   ディレクトリを作っておいて、このコマンドを打つと友達のリポジトリにあるフォルダがローカルにコピーされる。

-   git pull origin master

    -   変更を更新

-   git dif

    -   変更したか確認する

-   git branch 名前

    -   branch を作成

-   git checkout 名前

    -   branch を変える

-   git branch

    -   今あるブランチを確認

-   git branch -D 名前

    -   ブランチ削除

-   git log

    -   コミット履歴を見れる

-   git reset --hard コミット ID

    -   打ち込んだコミット ID のコードまで戻れる

-   git stash

    -   master で作業してしまった時に、一度コードをリセットして、ブランチを切り替えた時に移し替えてくれる(めっちゃ便利)
    -   git branch で新しくブランチを切った後、git checkout 　で新しいブランチに切り替える。
        git stach pop を打ち込むと新しいブランチに前のブランチで間違って書いたコードがコピーされる
