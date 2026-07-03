---
title: SetCharWidthBoundingBox
second_title: Aspose.PDF for Java API Reference
description: Class representing d1 operator (set glyph and bounding box).
type: docs
weight: 520
url: /java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Class representing d1 operator (set glyph and bounding box).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Initializes SetCharWidthBoundingBox operator. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getLlx](#getLlx--) | Lower-left horizontal coordinate of bounding rectangle. |
| [getLly](#getLly--) | Lower-left vertical coordinate of bounding rectangle. |
| [getUrx](#getUrx--) | Upper-right horizontal coordinate of bounding rectangle. |
| [getUry](#getUry--) | Upper-right vertical coordinate of bounding rectangle. |
| [getWx](#getWx--) | Horizontal displacement of glyph. |
| [getWy](#getWy--) | Vertical displacement of glyph. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Initializes SetCharWidthBoundingBox operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wx |  | Denotes the horizontal displacement in the glyph coordinate. |
| wy |  | Denotes the vertical displacement in the glyph coordinate. Shall be 0. |
| llx |  | Denotes X coordinate of the lower-left corner. |
| lly |  | Denotes Y coordinate of the lower-left corner. |
| urx |  | Denotes X coordinate of upper-right corner. |
| ury |  | Denotes Y coordinate of upper-right corner. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getLlx {#getLlx--}
```
public double getLlx()
```

Lower-left horizontal coordinate of bounding rectangle.

**Returns:**
double value

### getLly {#getLly--}
```
public double getLly()
```

Lower-left vertical coordinate of bounding rectangle.

**Returns:**
double value

### getUrx {#getUrx--}
```
public double getUrx()
```

Upper-right horizontal coordinate of bounding rectangle.

**Returns:**
double value

### getUry {#getUry--}
```
public double getUry()
```

Upper-right vertical coordinate of bounding rectangle.

**Returns:**
double value

### getWx {#getWx--}
```
public double getWx()
```

Horizontal displacement of glyph.

**Returns:**
double value

### getWy {#getWy--}
```
public double getWy()
```

Vertical displacement of glyph.

**Returns:**
double value

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of representation
