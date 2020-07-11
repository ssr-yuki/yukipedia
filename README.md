# yukipedia
Wikiもどきです．

[ここ](https://ssr-yuki.github.io/yukipedia/)から見れます．

## ローカルでページを静的生成する方法
### 準備

```bash
sudo apt install ruby-dev
git clone https://github.com/pages-themes/slate.git
cd slate
./script/bootstrap
```
最後のコマンドは時々`sudo`を要求します．

ブートストラップが終わったら
```bash
cd ${root of this repo.}
sudo bundle install
```
をして準備完了．

### プレビュー
yukipediaのルートで次のコマンドを実行します．
```bash
bundle exec jekyll serve
```
正しく動けば，ブラウザで[localhost:4000](http://localhost:4000/)で閲覧できます．

## 謝辞
yukipediaはGithub Pagesを利用しています．

また，デザインはJekyll theme for GitHub Pagesの[Slate](https://github.com/pages-themes/slate)をベースにしています．
