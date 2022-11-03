
# $\LaTeX$ French Template

## JA / 日本語

### 説明

フランス語でレポートを書くための $\LaTeX$ テンプレート。

### 表紙テンプレート

学校ロゴ入りの表紙テンプレート。
ロゴファイルを、使いたいものと入れ替える。

### Guillemet 挿入用コマンド

元々 $\LaTeX$ でコマンドを使って guillemet を挿入するには、`\guillemotleft`, `\guillemotright` コマンドを使う必要があったが、長くて使いにくいため、 `\gl`, `\gr` を作成。
ついでに、 guillemet 前後のスペースも挿入するようにした。

### APA形式の引用・参考文献リスト

#### hyperref の修正

APA形式の引用スタイルを用いると、`hyperref` を使ったときのリンクが、年号の部分にしか作成されない問題があった。
そのため、[Biblatex, APA style, hyperlink \parencite not displaying author on 2nd cite](https://tex.stackexchange.com/questions/457411/biblatex-apa-style-hyperlink-parencite-not-displaying-author-on-2nd-cite) に掲載されていた moeve さんのコードを使い、著者・年号の全体にリンクが作成されるようにした。
なお、APA形式の引用スタイルを用いる場合は、`\cite` ではなく、`\parencite`、`\textcite` を用いるべきである。

## フォント

フォントは、個人的な好みとして、Times (stix2) あるいは Palatino (newpxtext, newpxmath) を選択した。
無論、各自でフォントを指定することで、他のフォントを用いることもできる。

## EN / English

Work in progress.

## FR / Français

En cours de réalisation.

## 参考文献 / References / Références

- [Biblatex, APA style, hyperlink \parencite not displaying author on 2nd cite](https://tex.stackexchange.com/questions/457411/biblatex-apa-style-hyperlink-parencite-not-displaying-author-on-2nd-cite) (2022/11/03 参照)