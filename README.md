GitHub勉強会 for eeicer
====
Git/Githubについてお勉強しましょう。


目標
----
* よく使うGitのコマンドをなんとなく理解する
* GitHubの機能をなんとなく理解する
* プルリクエストを送るフローを体験する


準備
====

インストール
----
### Windows or Mac
GUIクライアントの Source Tree を使うのがおすすめ。

[http://www.sourcetreeapp.com/](http://www.sourcetreeapp.com/)

#### Source Tree の利点
* 自動的にフェッチしてくれる
* 部分的・一行単位のステージ/アンステージがやりやすい

### Ubuntu
調べた限り使い勝手の良いGUIクライアントはなかったので、コマンドラインから使う。

```sh
$ sudo apt-get install git
```

#### CUIの便利ツール
##### tig
Gitのクライアント。

```sh
$ sudo apt-get install tig
```

##### hub
`git`コマンドを拡張した`hub`コマンド。実行には`Ruby`が必要。

[github/hub](https://github.com/github/hub)


設定
----
### 公開鍵の登録
[https://github.com/settings/ssh](https://github.com/settings/ssh)

右上の`Add SSH key`をクリック。

公開鍵`~/.ssh/id_rsa.pub`の中身を`Key`にコピペする。

### GitHub Educationの申し込み
7ドル/月のディスカウントを2年間受けられるので、Microプラン（プライベートリポジトリ5）が無料で利用できる。

大学ドメインのメールアドレスの登録が必要。

[https://education.github.com/](https://education.github.com/)
