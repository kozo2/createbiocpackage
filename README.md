# Bioconductorパッケージの作り方

## 主要なリソース

- 教材: https://biopackathon.github.io/createbiocpackage/

## 教材の説明

この教材では、Bioconductorパッケージの作成方法の概要を説明します。

学習者は、Bioconductorパッケージが特別な理由、パッケージの作成を開始する方法、
およびそのパッケージの情報を広める方法を学びます。
この教材では、入門資料の説明、「ライブ」コーディング、を行います。
これらはすべて、以下のコンテンツを基にしています。

## インストラクター

- [西田孝三 Kozo Nishida](https://twitter.com/kozo2) (kozo.nishida@gmail.com)

## 前提条件

- Rの構文の基本的な知識
- Githubアカウント

## 目標と目的

### 学習目標

- パッケージ作成の目的を理解する
- パッケージの基本的な構成要素について学ぶ
- 初めてのシンプルなパッケージを開発する
- バージョン管理に精通する

## インストール

この教材では、Bioconductorバージョン3.12を使用します。

以下で、この教材に必要なパッケージをインストールできます。

``` r
library(BiocManager)
install(c("usethis", "biocthis", "roxygen2", "devtools", "goodpractice", "BiocCheck"))
```
