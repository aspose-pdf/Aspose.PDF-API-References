---
title: SubPath
linktitle: SubPath
second_title: Aspose.PDF for Java API Reference
description: Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and.
type: docs
weight: 60
url: /java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.SubPath, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.SubPath

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class SubPath extends GraphicElement
```

Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page.

## Methods

| Method | Description |
| --- | --- |
| [getRectangle](#getRectangle--) | Gets the bounding rectangle of the GraphicElement . |

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Gets the bounding rectangle of the GraphicElement .

**Returns:**
Rectangle instance
