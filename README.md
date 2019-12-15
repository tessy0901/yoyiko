# KDDIプレ卒研「よゐこ」

## メンバー
- tessy0901

## インストール手順
```
$ cd ~~~~(好きなディレクトリに移動)
$ git clone https://github.com/tessy0901/yoyiko.git
$ cd yoyiko
$ git branch
（おそらくdevelopと出るはず）
```

## ブランチ切り分け
```
$ git branch
（自分の今いるブランチの確認）（developがマスト）
いない場合→
$ git checkout develop
いる場合→
→新機能実装
$ git checkout -b feature/〇〇（実装する機能の名前）（例：git checkout -b feature/signin）（全部小文字がマスト）
$ git branch
指定したブランチ名に移動していたらOK
```

