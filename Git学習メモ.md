# GitHub コマンド集

github を使うためのファイル「.git」が生成される

```
git init
```

#### 行き先場所の設定

```
git remote add origin ssh の URL
```

#### 出荷前の荷物をまとめる感じ

.をつけると全部

```
git add ファイル名
git add .
```

#### 出荷するときの説明文をつけれる

```
git commit -m ”説明文”
```

#### origin(行き先の url)に出荷します

```
git push origin master
```

#### リモートのリポジトリにあるデータがローカルにコピーされ、現在の階層に新しくcloneしたフォルダがが作成される。

```
git clone ssh の URL
```

#### 変更を更新

```
git pull origin master
```

#### 変更したかを確認する

```
git dif
```

#### branch を作成

```
git branch 名前
```

#### branch を変える

```
git checkout 名前
```

#### いまある branch を確認

```
git branch
```

#### branch 削除

```
git branch -D 名前
```

#### コミット履歴が見れる

```
git log
```

#### 打ち込んだコミット ID のコードまで戻れる

```
git reset --hard コミット ID
```

#### master で作業してしまった時に、一度コードをリセットして、ブランチを切り替えた時に移し替えてくれる(めっちゃ便利)

```
git stash
```

#### git branch で新しくブランチを切った後、git checkout で新しいブランチに切り替える。

```
git checkout
```

#### git stach pop を打ち込むと新しいブランチに前のブランチで間違って書いたコードがコピーされる

```
git stach pop
```

#### originを削除。  
エラーが出た時とかに使える。
```
git remote rm origin
```