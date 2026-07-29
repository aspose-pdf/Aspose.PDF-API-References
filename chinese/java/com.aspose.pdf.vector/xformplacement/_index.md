---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 XForm 的放置位置。如果 XForm 在页面上显示超过一次，则与该 XForm 关联的所有 XformPlacement 将拥有共同的图形元素，但。"
type: docs
weight: 70
url: /zh/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

表示 XForm 的放置。如果 XForm 在页面上显示超过一次，则与该 XForm 关联的所有 XformPlacements 将拥有相同的图形元素，但图形状态不同。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | 在页面上添加当前元素。如果要添加的元素很多，最好使用 Page#addGraphics(GraphicElementCollection,Rectangle)。 |
| [getElements](#getElements--) | 获取此 XForm 内的图形元素。 |
| [getName](#getName--) | 获取 XForm 的名称。 |
| [getRectangle](#getRectangle--) | 获取 GraphicElement 的边界矩形。 |
| [getXForm](#getXForm--) | 获取与此 XFormPlacement 关联的 XForm。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 获取或设置当前坐标空间中的位置。 |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
在页面上添加当前元素。如果要添加的元素很多，最好使用 Page#addGraphics(GraphicElementCollection,Rectangle)。

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

获取此 XForm 内的图形元素。

**Returns:**
GraphicElementCollection 实例

### getName {#getName--}
```
public final String getName()
```

获取 XForm 的名称。

**Returns:**
字符串值

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取 GraphicElement 的边界矩形。

**Returns:**
Rectangle 实例

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

获取与此 XFormPlacement 关联的 XForm。

**Returns:**
XForm 实例

### setPosition {#setPosition-com.aspose.pdf.Point-}
获取或设置当前坐标空间中的位置。
