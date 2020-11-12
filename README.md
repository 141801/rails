# 環境構築　#debian　rails+postgresql
参考：https://vitux.com/installing-and-configuring-ruby-on-rails-on-debian-10/
```
gpg2 --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
curl -sSL https://rvm.io/mpapis.asc | gpg2 --import -
curl -sSL https://rvm.io/pkuczynski.asc | gpg2 --import -
curl -sSL https://get.rvm.io | bash -s stable --ruby
source /usr/local/rvm/scripts/rvm  # Setup RVM source folder
  ```
  
## トラブル１：yarnがインストールできない
対策：https://classic.yarnpkg.com/en/docs/install/#debian-stable

## トラブル2：外からアクセスできない
```
rails s -b localhost  -p 80
→　rails s -b 0.0.0.0  -p 80
```
## Rails scaffoldの使い方 
https://www.javadrive.jp/rails/scaffold/index1.html

## Rail devise,scaffold 組み合わせの使い方
https://qiita.com/takatoshi0905/items/a39b36ed4720880d4b59

## Rails ルーティング 基礎 まとめ
https://qiita.com/akk11_k/items/a6a21beb2b736ebbc147

##　MySQLとPostgreSQLコマンド比較表
https://qiita.com/aosho235/items/c657e2fcd15fa0647471

## Rails deviseで使えるようになるヘルパーメソッド一覧
https://qiita.com/tobita0000/items/866de191635e6d74e392

## configure_permitted_parametersメソッドってなんぞや
https://taiga-onrails0329.hatenablog.com/entry/2019/02/04/222812
