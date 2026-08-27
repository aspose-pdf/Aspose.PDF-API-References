---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XForm の配置を表します。XForm がページに 1 回以上表示される場合、この XForm に関連付けられたすべての XFormPlacement は共通のグラフィック要素を持ちますが、"
type: docs
weight: 70
url: /ja/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

XForm の配置を表します。XForm がページ上に 1 回以上表示される場合、この XForm に関連付けられたすべての XformPlacements は共通のグラフィック要素を持ちますが、グラフィック状態は異なります。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | ページに現在の要素を追加します。追加する要素が多数ある場合は、Page#addGraphics(GraphicElementCollection,Rectangle) を使用した方が良いです。 |
| [getElements](#getElements--) | この XForm 内のグラフィック要素を取得します。 |
| [getName](#getName--) | XForm の名前を取得します。 |
| [getRectangle](#getRectangle--) | GraphicElement の境界矩形を取得します。 |
| [getXForm](#getXForm--) | この XFormPlacement に関連付けられた XForm を取得します。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 現在の座標空間で位置を取得または設定します。 |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
ページに現在の要素を追加します。追加する要素が多数ある場合は、Page#addGraphics(GraphicElementCollection,Rectangle) を使用した方が良いです。

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

この XForm 内のグラフィック要素を取得します。

**Returns:**
GraphicElementCollection インスタンス

### getName {#getName--}
```
public final String getName()
```

XForm の名前を取得します。

**Returns:**
文字列値

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

GraphicElement の境界矩形を取得します。

**Returns:**
矩形インスタンス

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

この XFormPlacement に関連付けられた XForm を取得します。

**Returns:**
XForm インスタンス

### setPosition {#setPosition-com.aspose.pdf.Point-}
現在の座標空間で位置を取得または設定します。
