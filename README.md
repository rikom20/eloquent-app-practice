# eloquent-app-practice

## 概要
- COACHTECH 教材 Tutorial 9-4「Eloquent ORM ハンズオン演習」で作成した成果物です。
- Eloquent モデルを使ったCRUD操作（Model::all(), create(), update(), delete()）
- $fillable を使ったマスアサインメント対策の必要性
リソースコントローラ（index/create/store/edit/update/destroy）の役割

## 使用技術
- PHP 8.x
- Laravel 10.x
- Eloquent ORM
- MySQL

## 学んだこと
- $request	画面から送られてきたデータユーザー
フォームに入力した「タイトル」や「本文」などの値を受け取る。
- $posts データベースから取得したデータ	Postモデルを使ってデータベースから引っ張ってきた記事データ。
- create,store,edit,updateメソッドの違い
① 画面を表示する担当（GET）：create(新規作成画面)、edit（既存データフォーム画面表示）
② データベースを操作する裏方（POST等）:store(新規データ保存)、update（すでにあるデータを上書き保存する）

## 動作確認
ブラウザで http://localhost/posts にアクセスして、以下を確認：

投稿一覧が表示される
「新規作成」から投稿を追加できる
「編集」から投稿を更新できる
「削除」で投稿が削除される
<img width="434" height="156" alt="image" src="https://github.com/user-attachments/assets/11cd7a64-f525-41d6-b966-7a6cd34ba905" />

