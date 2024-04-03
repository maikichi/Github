## 新規リポジトリをgithubに載せる方法
※新規リポジトリを作る際に<u>Add a README file</u>にチェックを入れず作成するとURLや下記コマンドラインが出てくるので順に打ち込む
```rd
git init
```

```rd
find . -name .DS_Store -type f -delete
```
上記は.DS_Storeを消すため最初に行う

```rb
git remote add origin https://github.com/maikichi/JavaScript.git
```

```rb
git add .
```

```rb
git commit -m"add files"
```

```rb
git push -u origin main
（git push -u<リモートリポジトリ名> <ローカルブランチ名>）
```
## ローカルで変更したものをリモートにpushする方法

```rb
find . -name .DS_Store -type f -delete
git add .
git commit -m"add files"
git push origin main
```