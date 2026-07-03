---
title: SetLineWidth
second_title: Aspose.PDF for Java API Reference
description: Class representing w operator (set line width).
type: docs
weight: 690
url: /java/com.aspose.pdf.operators/setlinewidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetLineWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetLineWidth

```
public class SetLineWidth extends Operator
```

Class representing w operator (set line width).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetLineWidth](#SetLineWidth-double-) | Initializes operator with width value. |
| [SetLineWidth](#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-) | Constructor for operator class. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getWidth](#getWidth--) | Gets width of the line. |
| [setWidth](#setWidth-double-) | Sets width of the line. |
| [toString](#toString--) | Returns text representation of operator. |

### SetLineWidth {#SetLineWidth-double-}
```
public SetLineWidth(double width)
```

Initializes operator with width value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Value of width. |

### SetLineWidth {#SetLineWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineWidth-}
Constructor for operator class.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getWidth {#getWidth--}
```
public double getWidth()
```

Gets width of the line.

**Returns:**
width of the line.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Sets width of the line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | width of the line. |

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
