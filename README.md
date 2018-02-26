# RubyObject
文字列も配列もオブジェクト

## 処理
文字列や配列もオブジェクトであることを確認する。

## コード
```
text = "123"
p text.to_i
p text.length
p text.class        # クラス名を調べる
p "123".class

players = "勇者,戦士,魔法使い,忍者"
array = players.split(",")
p array
p array.length

array2 = Array.new(3)
p array2
```

## 出力結果  
```
123
3
String
String
["勇者", "戦士", "魔法使い", "忍者"]
4
[nil, nil, nil]
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Ruby 2.4.0 |
