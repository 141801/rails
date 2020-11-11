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

