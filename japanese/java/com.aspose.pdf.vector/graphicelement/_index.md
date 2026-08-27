---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページ上のグラフィックオブジェクトの基底クラスを表します。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

ページ上のグラフィックオブジェクトの基底クラスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | ページに現在の要素を追加します。追加する要素が多数ある場合は、Page#addGraphics(GraphicElementCollection,Rectangle) を使用した方が良いです。 |
| [dispose](#dispose--) | {@link GraphicElement} クラスが使用するすべてのリソースを解放します。 |
| [getMatrix](#getMatrix--) | グラフィック要素の行列を取得します。行列は要素が作成されたときに設定され、SetPosition() が呼び出されたときに変更されます。 |
| [getOperators](#getOperators--) | 要素を表すオペレーターのコレクションを取得します。 |
| [getParent](#getParent--) | 要素が配置されている現在の {@link XFormPlacement} を取得します。 |
| [getPosition](#getPosition--) | 現在の座標空間における位置を取得または設定します。Parent の #getParent/#setParent(XFormPlacement) が null でない場合、要素は xForm 座標空間を持ちます。 |
| [getRectangle](#getRectangle--) | {@link GraphicElement} のバウンディング矩形を取得します。 |
| [getSourcePage](#getSourcePage--) | グラフィック要素が抽出されるページを取得します。 |
| [remove](#remove--) | 現在の要素をページから削除します。削除する要素が多数ある場合は、Page#deleteGraphics(GraphicElementCollection) を使用した方が良いです。 |
| [saveToSvg](#saveToSvg--) | 要素を単一の SVG 画像に変換します。 |
| [saveToSvg](#saveToSvg-java.lang.String-) | 要素を単一の SVG 画像に変換します。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 現在の座標空間における位置を取得または設定します。Parent の #getParent/#setParent(XFormPlacement) が null でない場合、要素は xForm 座標空間を持ちます。 |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
ページに現在の要素を追加します。追加する要素が多数ある場合は、Page#addGraphics(GraphicElementCollection,Rectangle) を使用した方が良いです。

### dispose {#dispose--}
```
public final void dispose()
```

{@link GraphicElement} クラスが使用するすべてのリソースを解放します。

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

グラフィック要素の行列を取得します。行列は要素が作成されたときに設定され、SetPosition() が呼び出されたときに変更されます。

**Returns:**
行列インスタンス

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

要素を表すオペレーターのコレクションを取得します。

**Returns:**
Operator インスタンスのリスト

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

要素が配置されている現在の {@link XFormPlacement} を取得します。

**Returns:**
XFormPlacement インスタンス

### getPosition {#getPosition--}
```
public Point getPosition()
```

現在の座標空間における位置を取得または設定します。Parent の #getParent/#setParent(XFormPlacement) が null でない場合、要素は xForm 座標空間を持ちます。

**Returns:**
Point インスタンス

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

{@link GraphicElement} のバウンディング矩形を取得します。

**Returns:**
矩形インスタンス

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

グラフィック要素が抽出されるページを取得します。

**Returns:**
ページインスタンス

### remove {#remove--}
```
public final void remove()
```

現在の要素をページから削除します。削除する要素が多数ある場合は、Page#deleteGraphics(GraphicElementCollection) を使用した方が良いです。

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

要素を単一の SVG 画像に変換します。

**Returns:**
SVG 文字列です。

### saveToSvg {#saveToSvg-java.lang.String-}
要素を単一の SVG 画像に変換します。

**Returns:**
SVG 文字列です。

### setPosition {#setPosition-com.aspose.pdf.Point-}
現在の座標空間における位置を取得または設定します。Parent の #getParent/#setParent(XFormPlacement) が null でない場合、要素は xForm 座標空間を持ちます。
