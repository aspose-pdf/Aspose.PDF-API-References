---
title: "com.aspose.pdf.vector"
linktitle: "com.aspose.pdf.vector"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "Aspose.Pdf.Vector は、グラフィック操作のためのルート名前空間です。"
type: docs
weight: 390
url: /ja/java/com.aspose.pdf.vector/
---
Aspose.Pdf.Vector は、グラフィック操作のためのルート名前空間です。

## クラス

| クラス | 説明 |
| --- | --- |
| [GraphicElement](./graphicelement/) | ページ上のグラフィックオブジェクトの基底クラスを表します。 |
| [GraphicElementCollection](./graphicelementcollection/) | {@link GraphicElement} コレクションを表します。 |
| [GraphicsAbsorber](./graphicsabsorber/) | グラフィック要素の吸収オブジェクトを表します。グラフィック検索を実行し、{@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}) コレクションを介して検索結果へのアクセスを提供します。 |
| [GraphicState](./graphicstate/) | 現在の {@link GraphicElement} のグラフィック状態を表します。 |
| [InternalHelper](./internalhelper/) |  |
| [SubPath](./subpath/) | ページ上のベクターグラフィックオブジェクトを表します。基本的に、ベクターグラフィックオブジェクトは 2 つの SubPath グループで表現されます。そのうちの一方は線と曲線の集合で表され、もう一方は矩形として提示され、時には混同されることがあります。通常、色を持つ矩形領域ですが、この矩形はページの先頭に配置され、ページ全体を白で覆うことが多いです。そのため SubPath は取得できますが、視覚的にはページ上のテキストのみが表示されます。 |
| [XFormPlacement](./xformplacement/) | XForm の配置を表します。XForm がページ上に 1 回以上表示される場合、この XForm に関連付けられたすべての XformPlacements は共通のグラフィック要素を持ちますが、グラフィック状態は異なります。 |
