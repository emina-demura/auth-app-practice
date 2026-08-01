# auth-app-practice

## 概要
COACHTECH 教材 Tutorial 10-1「認証機能 ハンズオン演習」で作成した成果物です。


## 使用技術
- PHP 8.x
- Laravel 10.x
- Laravel Fortify（認証）
- MySQL


## 学んだこと
Laravel Fortify を使ったユーザー登録 / ログイン / ログアウトの仕組み
auth ミドルウェアでルートを保護する方法
リダイレクト設定（ログイン後の dashboard、未ログイン時の login）
- 
- 

## 動作確認
 /registerでユーザー登録ができる
 /loginでログインができる
 ユーザー登録後、ダッシュボードにリダイレクトされる
 未ログインで/dashboardにアクセスするとログインページにリダイレクトされる

