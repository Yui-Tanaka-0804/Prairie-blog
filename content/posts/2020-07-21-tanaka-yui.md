---
date: 2020-07-21T17:30:00Z
title: 今日のハンズオンの計画書
author: Tanaka Yui
hero_image: "/content/images/wow-flog.jpg"
---
# 今日やりたいこと
1. 触りの部分だけ解説
    1. 前回のパワポ使いまわす
        - 流れだけ思い出せるように読み込んでおく
        - 最低限必要な用語だけは説明する(ブランチ、コミット、リポジトリ、~~プルリク~~)
1. gitの環境構築
    1. githubアカウントを作る
    1. gitのダウンロード
        - CUI
        - fork
        - sourceTree
2. ブログを立てる
    1. 手元でプロジェクト作成
    2. ローカルで表示
    1. testページを追加する
    1. pushする（ふりしてあらかじめ作ってあるほうに移動）
    1. netlifyで公開してあるURLで確認
3. 実際に触ってもらう
    1. フォークしてclone
    1. ~pushするとこまで
    1. プルリク出してもらう

## コマンドカンペ
```bash:gatsby.sh
sudo apt-get install npm
sudo npm install -g gatsby-cli
gatsby develop
# 何かあったら npm run develop
```
```bash:git.sh
sudo apt-get install git
git config --global user.name "My Name"
git config --global user.email MyName@example.com
git clone {repository_name}
git add {ファイル名}
git commit -m"メッセージ"
git push origin master
git fetch
git pull
git branch -b {ブランチ名}
git checkout {ブランチ名}
```