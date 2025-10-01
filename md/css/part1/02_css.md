### Part1: CSSとは

# CSSの構文

```txt
セレクタ {
    プロパティ: 値;
}
```

+ セレクタ：スタイルを適用する要素を指定
+ プロパティ：変更したいスタイルの種類
+ 値：プロパティに設定する具体的な内容

## サンプルコード

```html
<!DOCTYPE html>
<html lang="ja">

<head>
    <meta charset="UTF-8">
    <title>Hello CSS!</title>
    <style>
        h1 {
            background-color: teal;
            color: white;
            padding: 10px;
        }
    </style>
</head>

<body>
    <h1>Hello CSS!</h1>
</body>

</html>
```

## 実行結果

![](https://raw.githubusercontent.com/murayama333/md2slide/refs/heads/main/md/css/part1/img/02.png)

## ポイント

💬 HTMLとCSSを "家" に例えるならHTMLは家の骨組み、CSSは壁紙や塗装のようなものです。

💡 Cascading とは「滝のように流れる」という意味です。
スタイルが段階的に適用される仕組みを表しています。
