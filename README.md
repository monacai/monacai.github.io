# 参加の仕方

## 事前準備
- githubのアカウントを作成しログインしておきます。
- ブラウザーで `https://github.com/monacai/monacai.github.io` を開きます。

## 環境構築
- monakaiのgithubのサイトを表示したら、Forkボタンをクリックします。
- monacai/monacai.github.io から 自分のユーザー名/monacai.github.ioになったことを確認します。
- `Clone or download` (緑色のボタン)ボタンをクリックします。
- `Clone with HTTPS` 又は `Clone with SSH`が表示されます（あとで使うのでkeyをコピーしておきます）。
- 自分のPCからターミナルを起動します。
### Mac

- 作業環境を作成
```
$ mkdir monakaihp && cd monakaihp
```

#### ローカルにクローン

- HTTPSの場合

```
$ git clone https://github.com/ユーザー名/monacai.github.io.git
```

- SSHの場合

```
$ git clone git@github.com:ユーザー名/monacai.github.io.git
```

そのあと、ls すると `monacai.github.io` ができてます。
こちらは、フォルダーでこの下にindex.htmlがあります。
