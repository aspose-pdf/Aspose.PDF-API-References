---
title: SubPath
second_title: Aspose.PDF for Java API Reference
description: Represents vector graphics object on the page.
type: docs
weight: 10
url: /java/com.aspose.pdf.vector/subpath/
---
**Inheritance:**
java.lang.Object
```
public final class SubPath
```

Represents vector graphics object on the page. Basically, vector graphics objects are represented by two groups of SubPaths. One of them is represented by a set of lines and curves. Others are presented as rectangles and can sometimes be confused. Usually it is a rectangular area that has a color, but very often this rectangle is placed at the beginning of the page and defines the entire space of the page in white. So you get the SubPath, but visually you only see the text on the page.
## Methods

| Method | Description |
| --- | --- |
| [getPosition()](#getPosition--) | Gets or sets the position of the SubPaths in [Point](../../com.aspose.pdf/point). |
| [setPosition(Point value)](#setPosition-com.aspose.pdf.Point-) | Gets or sets the position of the SubPaths in [Point](../../com.aspose.pdf/point). |
### getPosition() {#getPosition--}
```
public final Point getPosition()
```


Gets or sets the position of the SubPaths in [Point](../../com.aspose.pdf/point).

**Returns:**
[Point](../../com.aspose.pdf/point) - Point instance
### setPosition(Point value) {#setPosition-com.aspose.pdf.Point-}
```
public final void setPosition(Point value)
```


Gets or sets the position of the SubPaths in [Point](../../com.aspose.pdf/point).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.pdf/point) |  |

