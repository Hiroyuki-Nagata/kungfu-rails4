# kungfu-rails4

Kung Fu Master

# develop

* I developed with Debian/sid
* You can see the document for installation of rbenv/ruby-build
* (rbenv を使って ruby をインストールする(CentOS編))[http://qiita.com/inouet/items/478f4228dbbcd442bfe8]

## INSTALL

### rbenv/ruby-build

```
# apt-get install rbenv ruby-build
```

### Ruby 2.3.0 / Bundler

```
$ git clone https://github.com/Hiroyuki-Nagata/kungfu-rails4.git
$ cd kungfu-rails4
$ rbenv install 2.3.0-dev
$ rbenv local 2.3.0-dev
$ rbenv exec gem install bundler
$ rbenv exec bundle init
```

### Gemfile

* You can see the document for sufficient Gemfile information
* (Rails4 今のところ最強なデバッグツール達)[http://qiita.com/yusabana/items/8ce54577d959bb085b37]
* (kungfu-rails4 / Gemfile)[https://github.com/Hiroyuki-Nagata/kungfu-rails4/blob/master/Gemfile]

```
$ rbenv exec bundle install
```
