---
title: "SubPath"
linktitle: "SubPath"
second_title: "Aspose.PDF for Java API 参考"
description: "表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPath 表示。其中一组由一组线段表示。"
type: docs
weight: 60
url: /zh/java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

表示页面上的矢量图形对象。基本上，矢量图形对象由两组 SubPath 组成。其中一组由一系列直线和曲线表示。另一组表现为矩形，有时会被混淆。通常它是一个带颜色的矩形区域，但经常该矩形位于页面的起始位置，以白色定义整个页面的空间。因此你会得到 SubPath，但在视觉上只看到页面上的文本。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRectangle](#getRectangle--) | 获取 GraphicElement 的边界矩形。 |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

获取 GraphicElement 的边界矩形。

**Returns:**
Rectangle 实例
