---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面上图形对象的基类。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

表示页面上图形对象的基类。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | 在页面上添加当前元素。如果要添加的元素很多，最好使用 Page#addGraphics(GraphicElementCollection,Rectangle)。 |
| [dispose](#dispose--) | 释放 {@link GraphicElement} 类使用的所有资源。 |
| [getMatrix](#getMatrix--) | 获取图形元素矩阵。矩阵在元素创建时设置。调用 SetPosition() 时会更改矩阵。 |
| [getOperators](#getOperators--) | 获取表示该元素的运算符集合。 |
| [getParent](#getParent--) | 获取元素所在的当前 {@link XFormPlacement}。 |
| [getPosition](#getPosition--) | 获取或设置当前坐标空间中的位置。如果 Parent #getParent/#setParent(XFormPlacement) 不为 null，则该元素具有 xForm 坐标空间。 |
| [getRectangle](#getRectangle--) | 获取 {@link GraphicElement} 的边界矩形。 |
| [getSourcePage](#getSourcePage--) | 获取提取该图形元素的页面。 |
| [remove](#remove--) | 从页面中移除当前元素。如果要删除的元素很多，最好使用 Page#deleteGraphics(GraphicElementCollection)。 |
| [saveToSvg](#saveToSvg--) | 将元素转换为单个 SVG 图像。 |
| [saveToSvg](#saveToSvg-java.lang.String-) | 将元素转换为单个 SVG 图像。 |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | 获取或设置当前坐标空间中的位置。如果 Parent #getParent/#setParent(XFormPlacement) 不为 null，则该元素具有 xForm 坐标空间。 |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
在页面上添加当前元素。如果要添加的元素很多，最好使用 Page#addGraphics(GraphicElementCollection,Rectangle)。

### dispose {#dispose--}
```
public final void dispose()
```

释放 {@link GraphicElement} 类使用的所有资源。

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

获取图形元素矩阵。矩阵在元素创建时设置。调用 SetPosition() 时会更改矩阵。

**Returns:**
矩阵实例

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

获取表示该元素的运算符集合。

**Returns:**
Operator 实例列表

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

获取元素所在的当前 {@link XFormPlacement}。

**Returns:**
XFormPlacement 实例

### getPosition {#getPosition--}
```
public Point getPosition()
```

获取或设置当前坐标空间中的位置。如果 Parent #getParent/#setParent(XFormPlacement) 不为 null，则该元素具有 xForm 坐标空间。

**Returns:**
Point 实例

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

获取 {@link GraphicElement} 的边界矩形。

**Returns:**
Rectangle 实例

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

获取提取该图形元素的页面。

**Returns:**
页面实例

### remove {#remove--}
```
public final void remove()
```

从页面中移除当前元素。如果要删除的元素很多，最好使用 Page#deleteGraphics(GraphicElementCollection)。

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

将元素转换为单个 SVG 图像。

**Returns:**
SVG 字符串。

### saveToSvg {#saveToSvg-java.lang.String-}
将元素转换为单个 SVG 图像。

**Returns:**
SVG 字符串。

### setPosition {#setPosition-com.aspose.pdf.Point-}
获取或设置当前坐标空间中的位置。如果 Parent #getParent/#setParent(XFormPlacement) 不为 null，则该元素具有 xForm 坐标空间。
