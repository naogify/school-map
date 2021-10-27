# basic

## ユーザーがカスタマイズする際の手順

* [Use this template](https://github.com/naogify/basic/generate) ボタンでこのリポジトリをコピー。
* `style.yml` を編集。
* しばらくすると `gh-pages` ブランチに `style.json` がコミットされるので、Geolonia Maps で表示する場合は、その URL を以下のように指定してください。

```
<div data-style="https://<あなたのGitHubユーザー名>.github.io/<リポジトリ名>/style.json"></div>
```

例: https://codepen.io/naogify/pen/ZEJOErQ


## 色のカスタマイズ

[style.yml](./style.yml) を開いて下さい。 以下をお好きな色のカラーコードに変更しコミットして下さい。

```
$background: rgba(254, 254, 254, 1)

# カスタマイズここまで
```

Twemoji CC-BY 4.0

Copyright 2020 Twitter, Inc and other contributors
Code licensed under the MIT License: http://opensource.org/licenses/MIT
Graphics licensed under CC-BY 4.0: https://creativecommons.org/licenses/by/4.0/
