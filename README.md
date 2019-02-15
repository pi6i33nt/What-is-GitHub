# What is GitHub

## 概要
GitHubとはどういうものか，
GitHubの使い方などの基礎的な知識についてまとめる．

## 基礎的なコマンド

- リポジトリからクローンする

    $ git clone [ripository name]
    
- 現在変更ファイルの確認

    $ git status
    
  変更ファイルの一覧がでてくる
  
- 変更したファイルをステージに登録する

    $ git add [file name]
    
  `[file name]`を`.`にするとディレクトリ内のすべてのファイルが指定される．

- コメント付きでコミットする

    $ git commit -m 'hogehoge'
    
  コメントをシングルクォーテーションで囲む
  
- リモートにpushする

    $ git push
    
- ローカルファイルを最新に更新する
    
    $ git pull
    
- 変更したファイルを破棄する (変更を取り消す)

    $ git checkout [file name]

## GitHub 初期設定

````
    $ git config --global user.name [user name]
    $ git config --global user.email [mail addr.]
    $ git config --global core.editor "vim"
    $ git config user.name                            # ユーザ名の確認
    $ git config user.email                           # メールアドレスの確認
    $ git config core.editor                          # エディタの確認
    $ git config --list                               # 設定をまとめて確認
    $ cat ~/.gitconfig                                # 設定ファイルの確認
````

