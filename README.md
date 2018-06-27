# 環境整備ガイド
## はじめに
業務を行う上で必要になる（と思われる）ソフトウエアなどを列記する。ただし、以下はあくまで参考情報であり、記載者の推奨にすぎない。各用途に関して既に普段使っていて馴染んでいるものがあればそれを優先して利用してよいし、類似のソフトウエアを自身で選定してよい。
### ここに記載していないこと
記載しているソフトウエア群をインストールしただけでは開発に着手できないこともある。そうしたとき、推定・検索して環境構築していく場面もあると思われる。例えば、列記しているソフトウエアの具体的なインストール方法や操作方法などについての詳細な記載をここではしておらず、それは検索しながらできるだけ独力で解決する力を養うことを目的としている。ただし、最長でも15分ほど悩んでわからなかった場合には周囲に経緯を相談して聞くなどする。

## ブラウザ
提供しているwebサイトの動作確認のため、少なくとも、自身が業務で扱っているwebサイトで「推奨環境」として記載されているブラウザ・バージョンは必ずインストールし、使える状態にしておくこと。また、ブラウザでは開発者ツール（developer tool）やブラウザの設定を扱えるようにしておくとよい。
- 主要ブラウザ
  - [Google Chrome](https://www.google.co.jp/chrome/index.html)
  - [Firefox](https://mozilla.org/ja/firefox/new/)
  - [Internet Explorer](https://support.microsoft.com/ja-jp/help/17621/internet-explorer-downloads)
- その他ブラウザ
  - [Edge](https://microsoft.com/ja-jp/windows/microsoft-edge)
  - [vivaldi](https://vivaldi.com/?lang=ja_JP)
### 開発者ツールとは
任意のブラウザでF12を押すと開発者ツールが立ち上がる。いずれのブラウザも殆ど機能に差はなく、webサイトのレイアウトの調整やjsのデバッグ実行、ネットワークの流れなどを確認することができる。Firefoxに関しては、MDNのリファレンスがあるので参照するとよい：[開発者ツール | MDN](https://developer.mozilla.org/ja/docs/Tools)
### ブラウザの設定とは
Chromeを利用している場合は `chrome://settings` 、Firefoxを利用している場合は `about:preferences` とアドレスバーに入力することで表示できる各種設定項目。

## IDE/editor
コーディング/スクリプティングや簡易な文書作成の用途で利用するIDEやエディタ。いずれも無償のもののみ記載。
- [Eclipse IDE for Java EE Developers](https://eclipse.org/downloads/packages/)
  - Javaでweb開発をする際のIDEとしてスタンダードなもの。「EE」でない方だと機能が貧弱。
- [STS](https://spring.io/tools/sts)
  - Javaのweb開発フレームワークでSpringを利用する場合に適しているIDE。
- [VSCode](https://code.visualstudio.com)
  - 最近便利なエディタ。ターミナルがついていてプラグインも豊富で様々な用途に利用できる。軽量で.mdファイルのプレビュー機能が便利なので非エンジニアにも推奨。似たもので[Sublime text](https://sublimetext.com)や[Atom](https://atom.io)があり、どれを使うかは好みによる。
- [Typora](https://typora.io)
  - markdownに特化したエディタ。軽量なので簡易な文書作成の用途であればtyporaを選択するのが合理的。開発用途では使わない。
- [Vim(kaoriya)](https://kaoriya.net/software/vim/)
  - vimは、LinuxOSに標準搭載されている「vi」の拡張版。CUIですべて完結するため、最初に操作方法を学習する必要がある。業務上、実際にサーバ上でvim/viを利用する場面があるかもしれないので、まずはローカルに落として試してみるとよい。
