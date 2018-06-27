# はじめに
業務を行う上で必要になる（と思われる）ソフトウエアなどを列記する。ただし、以下はあくまで参考情報とし、各用途に関して既に普段使っていて馴染んでいるものがあればそれを優先して利用してよいし、類似のソフトウエアを自身で選定してよい。

## ブラウザ
提供しているwebサイトの動作確認のため、少なくとも、自身が業務で扱っているwebサイトで「推奨環境」で記載されているブラウザ・バージョンは必ずインストールし、使える状態にしておくこと。また、ブラウザでは開発者ツール（developer tool）を扱えるようにしておくとよい。
- 主要ブラウザ
  - [Google Chrome](https://www.google.co.jp/chrome/index.html)
  - [Firefox](https://mozilla.org/ja/firefox/new/)
  - [Internet Explorer](https://support.microsoft.com/ja-jp/help/17621/internet-explorer-downloads)
- その他ブラウザ
  - [Edge](https://microsoft.com/ja-jp/windows/microsoft-edge)
  - [vivaldi](https://vivaldi.com/?lang=ja_JP)
### 開発者ツールとは
任意のブラウザでF12を押すと開発者ツールが立ち上がる。いずれのブラウザも殆ど機能に差はなく、webサイトのレイアウトの調整やjsのデバッグ実行、ネットワークの流れなどを確認することができる。Firefoxに関しては、MDNのリファレンスがあるので参照するとよい：[開発者ツール | MDN](https://developer.mozilla.org/ja/docs/Tools)

## IDE/editor
コーディング/スクリプティングや簡易な文書作成の用途で利用するIDEやエディタ。いずれも無償のもののみ記載。
- [Eclipse IDE for Java EE Developers](https://eclipse.org/downloads/packages/)
  - javaでweb開発をする際のIDEとしてスタンダードなもの。「EE」でない方だと機能が貧弱。
- [STS](https://spring.io/tools/sts)
  - Javaのweb開発フレームワークでSpringを利用する場合に適しているIDE。
- [VSCode](htt)ps://code.visualstudio.com)
  - 最近便利なエディタ。ターミナルがついていてプラグインも豊富で様々な用途に利用できる。軽量で.mdファイルのプレビュー機能が便利なので非エンジニアにも推奨。
- [Typora](https://typora.io)
  - markdownに特化したエディタ。軽量なので簡易な文書作成の用途であればtyporaを選択するのが合理的。開発用途では使わない。
- [Vim(kaoriya)](https://kaoriya.net/software/vim/)
  - LinuxOSに標準搭載されている「vi」の拡張版。CUIですべて完結するため、最初に操作方法を学習する必要がある。業務上、実際にサーバ上でvim/viを利用する場面があるかもしれないので、まずはローカルに落として試してみるとよい。
