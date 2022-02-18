# url-encode

以下の機能が実装されています。

- データをURLエンコード/デコードする機能
- データをデータURL形式にエンコードする機能

## 使用例

```
$ url-encode escape 'hoge=fuga'
hoge%3Dfuga
$ url-encode unescape hoge%3Dfuga
hoge=fuga
$ url-encode embed sample.png
data:image/png;base64,[base64strings...]
```

## 導入方法
パスの通ったディレクトリにファイルを配置してください。
Python3が利用できる環境ならどこでも動作します。
