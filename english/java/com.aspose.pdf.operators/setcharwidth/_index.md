---
title: SetCharWidth
second_title: Aspose.PDF for Java API Reference
description: Class representing d0 operator (set glyph width).
type: docs
weight: 510
url: /java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Class representing d0 operator (set glyph width).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Constructor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getWx](#getWx--) | Horizontal displacement of glyph coordinate. |
| [getWy](#getWy--) | Vertical displacement of glyph coordinate. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wx |  | Horizontal displacement of glyph. |
| wy |  | Vertical displacement of glyph. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getWx {#getWx--}
```
public double getWx()
```

Horizontal displacement of glyph coordinate.

**Returns:**
double value

### getWy {#getWy--}
```
public double getWy()
```

Vertical displacement of glyph coordinate.

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
