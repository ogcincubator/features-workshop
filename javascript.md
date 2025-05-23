# JavaScript/ LeafLet

This tutorial shows how to plot features in an interactive map in HTML/JS, using the [LeafLet](https://leafletjs.com/) library.

このチュートリアルでは、［LeafLet］（https://leafletjs.com/） ライブラリを使用して、HTML/JS でインタラクティブな地図上に特徴をプロットする方法を説明します。

*Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps.*

*Leaflet は、モバイル対応のインタラクティブ地図用として最も広く使用されているオープンソースの JavaScript ライブラリです。*

Open [demo-oaf.htm](./demo-oaf.htm) in a text editor and in a browser. Follow the rest of the tutorial there.

テキストエディターとブラウザで ［demo-oaf.htm］（./demo-oaf.htm） を開きます。以降のチュートリアルはそちらに従って進めてください。

Note: To change the layer to be displayed, start by modifying line 23 `url = ...` to match the `collections` API (example from the 2015 land price layer: `https://pygeoapi.glodal-inc.net/collections/L01-15`). For further changes, refer to the [official documentation](https://leafletjs.com/reference.html) or [official tutorial](https://leafletjs.com/examples.html) while making adjustments.

注：表示するレイヤを変更するには23行目`url = ...`を`collections`APIに適合するよう（2015年地価公示の例：`https://pygeoapi.glodal-inc.net/collections/L01-15`）変更することから始めてみてください。その他、[公式ドキュメント](https://leafletjs.com/reference.html)や[公式チュートリアル](https://leafletjs.com/examples.html)を参照しながら変更を加えてみてください。