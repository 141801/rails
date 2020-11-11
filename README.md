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
