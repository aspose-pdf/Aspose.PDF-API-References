---
title: BorderInfo
linktitle: BorderInfo
second_title: Aspose.PDF for Java API Reference
description: This class represents border for graphics elements.
type: docs
weight: 370
url: /java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

This class represents border for graphics elements.

## Constructors

| Constructor | Description |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Initializes a new instance of the {@code BorderInfo} class. |
| [BorderInfo](#BorderInfo-int-) | Initializes a new instance of the {@code BorderInfo} class. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Initializes a new instance of the {@code BorderInfo} class. |
| [BorderInfo](#BorderInfo-int-float-) | Initializes a new instance of the {@code BorderInfo} class. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Initializes a new instance of the {@code BorderInfo} class. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Initializes a new instance of the {@code BorderInfo} class. |

## Methods

| Method | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clones a new BorderInfo object. |
| [getBottom](#getBottom--) | Gets object that indicates bottom of the border. |
| [getLeft](#getLeft--) | Gets {@code GraphInfo} object that indicates left of the border. |
| [getRight](#getRight--) | Gets {@code GraphInfo} object that indicates right of the border. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Gets rounded border radius. |
| [getTop](#getTop--) | Gets {@code GraphInfo} object that indicates the top border. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Sets object that indicates bottom of the border. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Sets {@code GraphInfo} object that indicates left of the border. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Sets {@code GraphInfo} object that indicates right of the border. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Sets rounded border radius. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Sets {@code GraphInfo} object that indicates top of the border. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Initializes a new instance of the {@code BorderInfo} class.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Initializes a new instance of the {@code BorderInfo} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| borderSide |  | Indicates the border sides info. For example: (BorderSide.Left \| BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Initializes a new instance of the {@code BorderInfo} class.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Initializes a new instance of the {@code BorderInfo} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| borderSide |  | Indicates the border sides info. For example: (BorderSide.Left \| BorderSide.Top). |
| borderWidth |  | The width of the border. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Initializes a new instance of the {@code BorderInfo} class.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Initializes a new instance of the {@code BorderInfo} class.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clones a new BorderInfo object.

**Returns:**
The new BorderInfo object.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Gets object that indicates bottom of the border.

**Returns:**
bottom

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Gets {@code GraphInfo} object that indicates left of the border.

**Returns:**
object that indicates left of the border.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Gets {@code GraphInfo} object that indicates right of the border.

**Returns:**
object that indicates right of the border.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Gets rounded border radius.

**Returns:**
value

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Gets {@code GraphInfo} object that indicates the top border.

**Returns:**
object that indicates the top border

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Sets object that indicates bottom of the border.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Sets {@code GraphInfo} object that indicates left of the border.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Sets {@code GraphInfo} object that indicates right of the border.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Sets rounded border radius.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Sets {@code GraphInfo} object that indicates top of the border.
