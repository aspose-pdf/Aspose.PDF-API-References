---
title: CurveTo2
second_title: Aspose.PDF for Java API Reference
description: Class representing y operator append curve to path final point replicated.
type: docs
weight: 26
url: /java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class CurveTo2 extends Operator
```

Class representing y operator (append curve to path, final point replicated).
## Constructors

| Constructor | Description |
| --- | --- |
| [CurveTo2(int index, ICommand command)](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [CurveTo2(double x1, double y1, double x3, double y3)](#CurveTo2-double-double-double-double-) | Initializes curve operator. |
## Methods

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | Points of the curve. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### CurveTo2(int index, ICommand command) {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public CurveTo2(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### CurveTo2(double x1, double y1, double x3, double y3) {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```


Initializes curve operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Abscissa of second point. |
| y1 | double | Ordinate of second point. |
| x3 | double | Abscissa of third point. |
| y3 | double | Ordinate of third point. |

### getPoints() {#getPoints--}
```
public Point[] getPoints()
```


Points of the curve.

**Returns:**
com.aspose.pdf.Point[] - array of Point instances
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

