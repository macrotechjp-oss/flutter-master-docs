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
TableOfContents = true
+++
## Using Docker + VSCode

## Using VSCode（Online）
## Using VSCode（Local）

## その他情報
### ディレクトリ構成
**libフォルダ配下**
```bash
├── constant/     .. 値に変更がない固定値を定義
├── extension/    .. String等の既存のライブラリへの機能追加を記述
├── model/        .. データの保持
├── plugin/       .. ネイティブ実装内容を記述
├── resource/     .. 色や文字のスタイルなどを定義
├── service/      .. API通信の処理を記述
├── view/         .. uiのwidgetを記述
├── view_model/   .. serviceとviewの中間で、データの変更を管理
└── main.dart     .. 実行時呼び出されるメインファイル
```

