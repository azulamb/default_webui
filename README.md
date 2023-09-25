# default_webui

Webの標準UIのサンプルです。自分で様々な端末で確認する用です。

https://azulamb.github.io/default_webui/

## ざっくりとした特徴

* テキストが絡む場合は基本 `font-size` の指定で大きくすることができる
* checkboxのようなUIは `display: grid` を使うことでその中いっぱいに広げることができる
  * `transform: scale()` よりも使いやすいはず
* `<input type="color">` は今のところどうすればサイズ変更可能か不明
