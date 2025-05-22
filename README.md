# Workshop: Integrating Data from OGC API into your Applications 🍣 OGC APIのデータをアプリケーションに取り込むワークショップ

This workshop shows different ways of consuming data from [OGC API - Features](https://features.developer.ogc.org/) services. After completing this workshop, you should be able to integrate OGC API - Features into your workflows.

このワークショップでは、OGC API - Features サービスからデータを様々な方法で利用する手順を紹介します。このワークショップを修了すると、OGC API - Features を自分のワークフローに統合できるようになります。

## Requirements 前提条件

※日本語注：参加者の皆様には一通りデモストレーションを体験いただき、QGIS, Jupyter, Leafletの**いずれか**を使ったプロトタイピングに取り組んでいただきます。以下の要件に満たない場合は、メンターがガイドしますのでご安心ください。

* ✅ Basic knowledge of python/ jupyter notebooks is required for some parts of the workshop.
* ✅ ワークショップの一部では、Python / Jupyter Notebook の基本的な知識が必要です。
* ✅ Basic knowledge of frontend web development (e.g.: HTML + JavaScript) is required for some parts of the workshop.
* ✅ ワークショップの一部では、フロントエンドウェブ開発（例: HTML + JavaScript）の基本的な知識が必要です。
* ❎ Some knowledge about REST architecture is recommended (e.g.: http verbs, status codes), although not required.
* ❎ RESTアーキテクチャに関する知識（例: HTTPメソッド、ステータスコード）が推奨されますが、必須ではありません。
* ❌ No previous knowledge of GIS or OGC Standards is required for this workshop.
* ❌ このワークショップでは、GISまたはOGC標準に関する事前の知識は不要です。

Before starting the workshop, make sure that you have access to a computer with the following installed:

ワークショップを開始する前に、以下のソフトウェアがインストールされたコンピュータをご用意ください。

* ✅ QGIS: you can follow the [instructions on the official website](https://qgis.org/resources/installation-guide/) to install it.
* ✅ QGIS: 公式ウェブサイトの手順に従ってインストールしてください。
* ✅ Jupyter notebook: You can follow [these](https://jupyter.org/install) instructions to install it with pip.
* ✅ Jupyter Notebook: pipを使用してインストールするには、こちらの手順に従ってください。
* ✅ A text editor: I 💙 [VS code](https://code.visualstudio.com/), but feel free to choose whatever you like.
* ✅ テキストエディタ: 私はVS Codeが大好きです💙が、お好きなものをご自由にお選びください。

## Introduction イントロダクション

In this workshop, we are going to connect to this deployment of [pygeoapi](https://pygeoapi.io/) provided by [GLODAL](https://glodal-inc.com/en-US/) (thank you!🙏💚) 

このワークショップでは、[GLODAL](https://glodal-inc.com/en-US/) 様提供（ありがとうございます！🙏💚）のこちらの[pygeoapi](https://pygeoapi.io/)デプロイメントに接続します。

https://pygeoapi.glodal-inc.net/

https://pygeoapi.glodal-inc.net/openapi?f=html

<!-- It is okay to link the presentations here for sharing it with participants? -->
* Introduction to OGC Standards / OGC Standards 入門
* Introduction to OGC API / OGC API 入門
* Present datasets 

## Tutorials チュートリアル

Explore OGC API using different technologies.

様々なテクノロジを使ってOGC APIを試してみましょう。

* [QGIS](QGIS.md)
* [Python/OWSLib](python.md)
* [JavaScript/LeafLet](javascript.md)

## Resources 参考資料

Continue your journey, by learning more about OGC API with these learning resources:

以下の学習リソースでOGC APIについてさらに学び、探求を続けましょう。

* OGC API Workshop: https://ogcapi-workshop.ogc.org/
* OGC APIワークショップ: https://ogcapi-workshop.ogc.org/
* pygeoapi Workshop: https://dive.pygeoapi.io/
* pygeoapiワークショップ: https://dive.pygeoapi.io/

## License ライセンス

This workshop is licensed under MIT. Read a copy of the license [here](./LICENSE).

このワークショップはMITライセンスに基づいています。ライセンスのコピーはこちらでお読みください。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
