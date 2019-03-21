---
title: Javascript
date: 2019-03-22 01:07:23
tags: javascript
---

#### JavaScriptを入力してみる

JavaScriptはシンプルで扱いやすい言語。エディタとブラウザさえあれば
開発することができる。
今回は、`Visual Studio Code`を使います。

###### test.html
```
<!DOCTYPE html>
    <html lang="ja">
        <head>
            <meta charset = "utf-8">
            <title>タイトル</title>
                <script type ="text/javascript">
                function welcome()
                {
                    window.alert("ようこそ");
                }
                </script>
        </head>
            <body>
                <img src = "test.jpg" onclick="welcome()"/>
            </body>
    </html>
```

行の頭にスペース（tabキー）を入れて字下げを行う。
画像はフリーの素材を使用。

次にスタイルシートを作成。
###### test.css - webページのレイアウト
```
body{
    background-color: #000000
    color: #ffffff;
}
```
これでディレクトリの中身は３つのファイルが存在している状態になる
では、htmlファイルをダブルクリック。

<img src="javascript.png" alt="" title="Javascript" width="700">