---
title: Path
linktitle: Path
second_title: Aspose.PDF for Java API Reference
description: Represents arc.
type: docs
weight: 100
url: /java/com.aspose.pdf.drawing/path/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Path, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Path

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Path extends Shape
```

Represents arc.

## Constructors

| Constructor | Description |
| --- | --- |
| [Path](#Path--) | Initializes a new instance of the {@code Path} class. |
| [Path](#Path-com.aspose.pdf.drawing.Shape:A-) | Initializes a new instance of the {@code Path} class. |

## Methods

| Method | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Checks if the item fits within the given container dimensions (inclusive). |
| [getShapes](#getShapes--) | <p> Gets or sets shapes collection. </p> |
| [getShapesInternal](#getShapesInternal--) | Gets or sets shapes collection. |

### Path {#Path--}
```
public Path()
```

Initializes a new instance of the {@code Path} class.

### Path {#Path-com.aspose.pdf.drawing.Shape:A-}
Initializes a new instance of the {@code Path} class.

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Checks if the item fits within the given container dimensions (inclusive).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
True if fits; otherwise, false.

### getShapes {#getShapes--}
```
public List < Shape > getShapes()
```

<p> Gets or sets shapes collection. </p>

**Returns:**
{@code java.util.List<Shape> }object

### getShapesInternal {#getShapesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< Shape > getShapesInternal()
```

Gets or sets shapes collection.

**Returns:**
internal object
