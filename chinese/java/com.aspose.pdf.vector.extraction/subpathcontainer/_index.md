---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于图形元素的容器类。"
type: docs
weight: 10
url: /zh/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

表示用于图形元素的容器类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | 实例化用于图形元素的容器类。 |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | 实例化用于图形元素的容器类。 |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | 实例化用于图形元素的容器类。 |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | 实例化用于图形元素的容器类。 |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | 实例化用于图形元素的容器类。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | 计算两个容器之间的距离。 |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | 比较当前的 SubPathContainer 对象与另一个 SubPathContainer 对象，并返回一个整数，指示当前对象是小于、等于还是大于另一个对象。比较是基于它们的数值 ID。 |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | 计算此容器与另一个容器之间的距离。 |
| [getGraphElement](#getGraphElement--) | 获取包含的图形元素。 |
| [getId](#getId--) | 获取 SubPathContainer 的 Id。Id 在调试和渲染期间对元素的排序非常有用。 |
| [getRect](#getRect--) | 表示包含元素的矩形。 |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

实例化用于图形元素的容器类。

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
实例化用于图形元素的容器类。

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
实例化用于图形元素的容器类。

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
实例化用于图形元素的容器类。

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
实例化用于图形元素的容器类。

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
计算两个容器之间的距离。

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
比较当前的 SubPathContainer 对象与另一个 SubPathContainer 对象，并返回一个整数，指示当前对象是小于、等于还是大于另一个对象。比较是基于它们的数值 ID。

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
计算此容器与另一个容器之间的距离。

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

获取包含的图形元素。

**Returns:**
GraphicElement 实例

### getId {#getId--}
```
public final int getId()
```

获取 SubPathContainer 的 Id。Id 在调试和渲染期间对元素的排序非常有用。

**Returns:**
int 值

### getRect {#getRect--}
```
public final Rectangle getRect()
```

表示包含元素的矩形。

**Returns:**
Rectangle 实例

### toString {#toString--}
```
public String toString()
```

{@code }
