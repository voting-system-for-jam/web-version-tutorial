# web-version

## 開発言語

### フロントエンド：
HTML/CSS (SCSS)
JavaScript

### バックエンド：
Python (Django)

### 環境構築:
Docker

## エレベーターピッチ

[ShowVote] は[投票作成の不便さ]を解決したい[jamの人]向けの[Webサービス]です。

これは [ログイン不要かつ少ない入力事項でフォームが作成できること] によって、[GoogleForm] とは違って[簡単に投票ページを開設し、集計すること] を実現できます。

## なぜ、投票システムを作るのか？

Googleフォームではいけない理由：
・Googleアカウントを持っていないと登録できない
・集計がめんどくさい
・jamで使う投票システムは型が決まっているのに、毎回作るのがめんどくさい
・フォームに何回でも答えられる

どうすればいいか？：
・ログインが不要のものを作る
・自動的に集計してくれる
・チーム数とチーム名さえ入れれば、勝手にフォームを作成してくれる
・どのチームの人が何人答えているのかを確認する。（ログインできないので、再度入力の拒否は無理）
	というか、不正に投票する人はいないと仮定する
