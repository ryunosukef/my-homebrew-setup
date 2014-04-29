my-homebrew-setup
=================

homebrewのインストールから、Brewfileに指定したパッケージをインストールする。
なお、
Macにはrubyが入っていることが前提。（まあ、はいってるわな）

```
$ git clone git@github.com:ryunosukef/my-homebrew-setup.git
$ cd my-homebrew-setup
$ sh install.sh
```

## error on brew doctor

[brew doctorで警告がでたとき](http://d.hatena.ne.jp/january/20130723/1374538421)は、不要なファイルをrmし、brew prune, brew cleanupするとよい。
