---
title: Aspose.Pdf.Vector
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vectorはグラフィックス操作のルート名前空間です
type: docs
weight: 270
url: /ja/net/aspose.pdf.vector/
---
**Aspose.Pdf.Vector**はグラフィックス操作のルート名前空間です。

## クラス

| クラス | 説明 |
| --- | --- |
| [GraphicElement](./graphicelement/) | ページ上のグラフィックスオブジェクトのベースクラスを表します。 |
| [GraphicElementCollection](./graphicelementcollection/) | [`GraphicElement`](../aspose.pdf.vector/graphicelement/) コレクションを表します。 |
| [GraphicsAbsorber](./graphicsabsorber/) | グラフィックス要素のアブソーバーオブジェクトを表します。グラフィックス検索を実行し、[`Elements`](../aspose.pdf.vector/graphicsabsorber/elements/) コレクションを介して検索結果にアクセスを提供します。 |
| [GraphicState](./graphicstate/) | 現在の[`GraphicElement`](../aspose.pdf.vector/graphicelement/)のグラフィック状態を表します。 |
| [SubPath](./subpath/) | ページ上のベクターグラフィックスオブジェクトを表します。基本的に、ベクターグラフィックスオブジェクトは2つのグループのSubPathsによって表されます。そのうちの1つは線と曲線のセットによって表されます。他は長方形として表され、時には混同されることがあります。通常、色を持つ長方形の領域ですが、この長方形はページの先頭に配置され、ページ全体の空間を白で定義します。したがって、SubPathを取得しますが、視覚的にはページ上のテキストのみが表示されます。 |
| [SubPathGroup](./subpathgroup/) | グラフィック要素コンテナのグループのためのクラスを表します。クラスオブジェクトはグループサイズを考慮するためのバウンディングボックスを持っています。 |
| [SvgExtractionOptions](./svgextractionoptions/) | PDFドキュメントページからベクターグラフィックスを抽出するためのオプションクラスを表します。 |
| [SvgExtractor](./svgextractor/) | ページからSVG画像を抽出するためのクラスを表します。 |
| [XFormPlacement](./xformplacement/) | XFormの配置を表します。XFormがページに1回以上表示される場合、このXFormに関連付けられたすべてのXformPlacementsは共通のグラフィカル要素を持ちますが、異なるグラフィック状態を持ちます。 |