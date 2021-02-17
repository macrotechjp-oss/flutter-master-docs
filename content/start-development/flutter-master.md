+++
title = "Flutter Master"
description = ""
tags = [
    "go",
    "golang",
    "hugo",
    "development",
]
date = "2021-02-16"
categories = [
    "Development",
    "golang",
]
+++

![2 People Sitting With View of Yellow Flowers during Daytime](/images/docs-captcha.png)

* **Getting Starting**
  * [1. Hugo Install](#1-hugo-install)
  * [2. Git Clone](#2-git-clone)
  * [3. Hugo Start-up](#3-hugo-start-up)
* **Creating**
  * [4. Hugo PublicDir Create](#4-hugo-publicdir-create)
* **Deploying**
  * [5. Git Commit & Push](#5-git-commit--push)
* **Other Information**
  * [Docs Configration](#docs-configration)

{{< panel title="primary" >}}Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <a href="https://github.com/thingsym/hugo-theme-techdoc">Ut enim ad minim veniam</a>, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.{{< /panel >}}

{{< panel status="notice" title="Frontend" >}}Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. <a href="https://github.com/thingsym/hugo-theme-techdoc">Ut enim ad minim veniam</a>, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in <img src="/images/docs-captcha.png">culpa qui officia deserunt mollit anim id est laborum.{{< /panel >}}

{{< button status="notice" url="#" >}}notice{{< /button >}}

## Getting Starting
###  1. Hugo Install
Install the HugoCLI.(https://gohugo.io/getting-started/installing/) 
```bash
# Use Mac Case
brew install hugo
# Use Windows Case(PowerShell)
choco install hugo -confirm
```
### 2. Git Clone
Clone the Docs source code.
```bash
git clone https://github.com/MacrotechJP-OSS/flutter-master-docs.git
```
### 3. Hugo Start-up
Start hugo server.
```bash
hugo server
```

## Creating
### 4. Hugo PublicDir Create
After creating the content, create HTML for publication.  
HTML is created under docs.
```bash
hugo
```

## Deploying
### 5. Git Commit & Push
Push the created content to github.
```bash
git add *
git commit -m "<Commit Message>"
git push origin master
```
After the push is complete, the contents of Github pages will be updated automatically.

## Other Information
### Docs Configration
```bash
├── archetypes      .. hugo new コマンドでコンテンツファイルを作ったときの Markdown のフォーマット
│   └── default.md  .. デフォルトで設定したい書式を記載
├── content         .. メインコンテンツとなるMarkdownファイルを置くディレクトリ
├── data            .. サイトの全ページから参照したいデータを記述したファイルを置くディレクトリ
├── docs            .. 本番公開用のHTMLが作成されるディレクトリ
├── layouts         .. themes においたテーマファイルの一部修正やレイアウトパーツを追加するディレクトリ
├── resources       .. 静的ファイル（スタイルシート、JavaScript や画像ファイルなど）を配置するディレクトリ
├── config.toml     .. Hugoの設定ファイル
├── LICENSE         .. MIT License
└── README.md       .. リポジトリの概要情報を記載
```