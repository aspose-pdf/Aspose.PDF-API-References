---
title: CurveTo
second_title: Aspose.PDF for Java API Reference
description: Class representing c operator append curve to path.
type: docs
weight: 24
url: /java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class CurveTo extends Operator
```

Class representing c operator (append curve to path).
## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo(int index, ICommand command)](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)](#CurveTo-double-double-double-double-double-double-) | Initializes curve operator. |
## Methods

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Points of the curve. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [toCommand()](#toCommand--) |  |
### CurveTo(int index, ICommand command) {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public CurveTo(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### CurveTo(double x1, double y1, double x2, double y2, double x3, double y3) {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```


Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Abscissa of first point. |
| y1 | double | Ordinate of first point. |
| x2 | double | Abscissa of second point. |
| y2 | double | Ordinate of second point. |
| x3 | double | Abscissa of third point. |
| y3 | double | Ordinate of third point. |

### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Points of the curve.

**Returns:**
com.aspose.pdf.Point[] - Points[] object
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
