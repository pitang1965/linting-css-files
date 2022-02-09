# linting-css-files
* （バニラJavaScript +)HTML, CSS のプロジェクトで、CSSファイルの誤記により期待どおりにならないことを検出するために、 [Stylelint](https://stylelint.io/)を使う方法の調査。

## [1] 使い方
* 以下をクリックしてすぐ試せます。 
  * [Edit on StackBlitz ⚡️](https://stackblitz.com/edit/vitejs-vite-d7ldhb)
* Terminal で次のコマンドを実行します。
```
❯ npm run lint
$ npx stylelint "**/*.css"

style.css
 7:15  ✖  Unexpected unknown unit "opx"  unit-no-unknown

src/foo.css
 3:11  ✖  Unexpected unknown unit "opx"             unit-no-unknown                 


~/projects/vitejs-vite-d7ldhb
❯ 
```
0とoを間違えが2つのファイルにあることが検出されました。

## [2] StackBlitzでのプロジェクト解説
* [1]のプロジェクトをどう作ったかなどを説明します。
* 編集中...

## [3] ローカルでのWebサイト開発環境の構築方法
[2]の内容を他の人からは見えないローカルの環境に構築する方法を説明します。
* 編集中...

## [4] サイトのデプロイ方法
* Terminalで次のコマンドを実行します。

```
npm run build
```
* distフォルダ以下をレンタルサーバー（例：エックスサーバー）や通常無料で使用できる静的サイトのホスティングサービス（例：Netlify、GitHub Pages）にアップロードすれば、サイトがデプロイできます。

以上
