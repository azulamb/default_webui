# default_webui

Webの標準UIのサンプルです。自分で様々な端末で確認する用です。

https://azulamb.github.io/default_webui/

## ざっくりとした特徴

* テキストが絡む場合は基本 `font-size` の指定で大きくすることができる
* checkboxのようなUIは `display: grid` を使うことでその中いっぱいに広げることができる
  * `transform: scale()` よりも使いやすいはず
* `<input type="range">` は当たり判定の大きさと横幅に関しては `width` や `height` でサイズ指定可能
  * `display: grid` を使っても中のUIが大きくできるわけではない。あくまでバーと上下の当たり判定のみ。
* `<input type="color">` は `width` や `height` でサイズ指定可能
