# HTTPでやりとりする仕組み

<!-- Markdown記法のヒント

コード記法（1行の中に埋めたい場合）

`code`

コードブロック記法（複数行）

```
print('a')
print('b')
```

-->

## 実習でやったこと (Y)

神戸電子のサイトでデベロッパーツールを使いHTTPの処理を見た

## 自分で調べたこと

https://www.kagoya.jp/howto/rentalserver/apache/
kd.txtに書いてあったwebサーバーソフトウェアApacheについて調べました

## HTTPメッセージ (kd.txt) のうち、最も重要だと思う部分を貼り付けてください

```
GET / HTTP/1.0

HTTP/1.0 200 OK
```

## それはなぜですか？

この部分が無いとリクエストしてもレスポンスで返して貰えずwebサーバーの処理のキャッチボールを行えないから

## わかったこと・気づいたこと

HTTPのリクエストとレスポンスで延々とキャッチボールを行っている
