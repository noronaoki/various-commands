# Linuxコマンド編
ディレクトリの作成や移動、ファイルの作成、編集など、普段マウスを使って操作しているものは大体Linuxコマンドでできます。

## pwd
現在いるディレクトリの確認。  
現在自分がいるディレクトリを確認する時に使うコマンド。

```sh
# print working directoryの略
pwd
```

## mkdir
ディレクトリの作成。  
スペース区切りで複数の並列ディレクトリ、`-p`を付けるとサブディレクトリが作成できる。

```sh
# make directoryの略
mkdir command

# 複数作成する場合
mkdir command/html command/css

# サブディレクトリも同時に作成する場合
mkdir -p command/js/top
```

## cd
ディレクトリの移動。

```sh
# commandディレクトリに移動する場合
cd command
```

## ls
ディレクトリのファイルリストを表示する。

```sh
# listの略（たぶん
ls

# サブディレクトリも表示する場合
ls -R

# 縦方向に並べつつ詳細情報も見たい場合
ls -l
```

## touch
ファイルの作成。  

```sh
# htmlディレクトリの中にindex.htmlを作成する
touch html/index.html
```

## cp
ファイルやディレクトリのコピー。

```sh
# html/index.htmlをコピーしてlist.htmlとして複製する
cp html/index.html html/list.html
```

## rm
ファイルの削除。

```sh
# htmlディレクトリのindex.htmlを削除する
rm html/list.html

# ディレクトリと中身のファイルを丸ごと削除する
rm -rf js
```
