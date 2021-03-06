# Javascript授業 補足説明
# このテキストについて
このテキストはマークダウン記法で作成しています。
記述ルールを理解すれば、通常のエディタで簡単に構造的な文書が作成できます。

[マークダウン -wikipedia](https://ja.wikipedia.org/wiki/Markdown)

[マークダウン記法チートシート](http://qiita.com/tbpgr/items/989c6badefff69377da7)

# Visual Studio Codeについて
* Microsoft製の多機能エディタ
* IDE(統合開発環境)のVisual Studioの派生製品。
* 無料
* eclipse や Visual StudioといったIDEに比べて軽量軽快。
* 拡張機能(Extension)で機能を追加できる。 
* ほかのエディタに比べて標準搭載されている機能が多い。

## 参考記事
まだ新しい製品のため、ドキュメントは少ないが、他の先発エディタと同じような機能が使える。

[Visual Studio Codeの使い方、基本の「キ」](http://www.atmarkit.co.jp/ait/articles/1507/10/news028.html)

# HTML入力支援
## EMMET
少ない入力でHTMLタグを記述してくれる機能。

特定の単語を入力後[TAB]キーでHTMLタグを展開する。
Visual Studio Codeには標準搭載。
 
 ```
 nav>ul>li*3[タブキー]    
 ```

[EMMET チートシート](http://docs.emmet.io/cheat-sheet/)

# HTMLデザイン支援
## Bootstrap
よく使うWebサイト用パーツを予めCSSでデザインして部品化しているコンポーネント集。
ひとまず、Bootstrap.cssがあれば簡単に利用できる。

CSSクラスの種類についてはこちら

[Bootstrap3 日本語リファレンス](http://bootstrap3.cyberlab.info/)


## Bootstrapを利用するには
* 自身でBootstrap.cssをダウンロードして利用する。
* CDN(コンテンツデリバリネットワーク)によるBootstrapのファイルのリンクを張る

* [Bootstrap 公式サイト(最新版はVer3α)](http://getbootstrap.com/)
* [Bootstrap CDN](https://www.bootstrapcdn.com/)

### HTMLファイルのhead内に記述
```html
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
```

# Javascriptの学習について

## チュートリアル、リファレンスサイト
* [とほほのJavaScriptリファレンス](http://www.tohoho-web.com/js/)
* [MDN JavaScript リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)
* [w3schools -javascript](http://www.w3schools.com/js/default.asp)

# ｊQueryについて

##必要なもの
jquery.jsファイルが必須。

## jQUery.jsのダウンロード
[jQuery公式ダウンロードサイト](https://jquery.com/)からダウンロード
1系、2系、3系があるこことに注意。(対応ブラウザの違い)

## CDN(コンテンツデリバリネットワーク)について
公式サーバーとリンクすることでjQuery.jsをダウンロードできるサービス

[jQuery CDN](https://code.jquery.com/)

### HTMLファイルのhead内に記述
注意：JSファイルはCSSファイルの後に記述すること。

```html
<script src="https://code.jquery.com/jquery-2.2.4.js"></script>
```


##jQUery参考サイト
* [jQuery日本語リファレンス](http://semooh.jp/jquery/)
* [js-Studio](http://js.studio-kingdom.com/jquery/)
* [w3schools jQuery Tutorial](http://www.w3schools.com/jquery/default.asp)

# Gitによるバージョン管理とGithubの活用

## バージョン管理システムの種類
* クラウド系のファイルストレージサービス(Googleドライブ、OneDrive)
* SVN(サブバージョン)
* Git(ギット)

[WindowsでOneDriveを活用するためのテクニック集 ](http://www.atmarkit.co.jp/ait/articles/1411/27/news137_4.html)



## バージョン管理システムの違い
### SVN
* 歴史が長い
* 企業向け
* 企業内サーバーにメインファイル(リポジトリ)があり、複数社員がクローンを作って変更を加え、メインにコミットする

### Git
* 最近のシステム開発の主流
* Visual Studio Codeからでも使える
* 個人～企業向け
* サーバー上にメインファイル(リモートリポジトリ)があり、複数人がクローンを作って(ローカル)リポジトリを利用することができる。
* 個人でローカルリポジトリに変更を加え、ローカルリポジトリにコミット、コミットしたローカルリポジトリをリモートリポジトリにマージする。
* オープンソースとして皆に公開する代わりに無料でファイルを預かってくれるGithubというサービスがある。
* **オープンソースのファイルサーバーGithubから様々なアプリ制作者の最新版ファイルをクローンして利用できる。**

## 参考サイト
* [サルでもわかるGit入門](http://www.backlog.jp/git-guide/)
* [github](https://github.com/)
