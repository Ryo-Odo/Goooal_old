# README
## 製品名
目標共有、達成応援SNS「Goooal」

## 製品概要
同じ目標を持っている人達と繋がる、またみんなの目標達成を応援するアプリケーション。
目標を投稿し、その目標についての努力や進捗をつぶやき、そのつぶやきに対して他のユーザーから励ましやアドバイスのコメントを貰う事ができる。

なぜこのアプリが必要か
目標の達成には大きな障害や継続的な努力がつきものであり、精神的に挫けてしまう事がある。
一人では達成困難な目標も、このアプリを通してお互いに励ましアドバイスし合うことで達成へ近づくことができる。

## 開発言語
- Ruby 3.0.1
- Ruby on Rails 6.0.3

## 就職Termで学んだ技術
- devise
- フォロー機能

## カリキュラム外の技術
- Vue.js

## 実行手順
```
$ git clone git@github.com:Ryo-Odo/Goooal.git
$ cd goooal
$ bundle install
$ rails webpacker:install
$ rails db:create
$ rails db:migrate
$ rails s (rails server -b 0.0.0.0)
```

## チェックシート/カタログ設計/テーブル定義書
https://docs.google.com/spreadsheets/d/1MUHJiozWa66eLxQJp7RyoGq7b6MEhRlGyZ7nO93uK6w/edit?usp=sharing

## ER図
![ER図](https://user-images.githubusercontent.com/89906223/144702915-7bc264c1-5a0d-4877-af3e-6fe753d1d5da.png)

## 画面遷移図
![画面遷移図](https://user-images.githubusercontent.com/89906223/144703228-ac6f440a-f5f6-4823-a1b1-714adf7f30ca.png)


## ワイヤーフレーム
![ワイヤーフレーム](https://user-images.githubusercontent.com/89906223/144702893-859bfb25-2fbb-4b40-9a24-48e83cb24d5e.png)
