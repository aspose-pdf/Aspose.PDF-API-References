---
title: SetGrayStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing gray level for stroking operations.
type: docs
weight: 73
url: /java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.SetColorOperator](../../com.aspose.pdf.operators/setcoloroperator)
```
public class SetGrayStroke extends SetColorOperator
```

Class representing gray level for stroking operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [SetGrayStroke(int index, ICommand command)](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetGrayStroke(double gray)](#SetGrayStroke-double-) | Initializes operator with the specified color. |
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color specified by operator. |
| [getGray()](#getGray--) | Gets or sets the level of gray value. |
| [setGray(double value)](#setGray-double-) | Gets or sets the level of gray value. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### SetGrayStroke(int index, ICommand command) {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetGrayStroke(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetGrayStroke(double gray) {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```


Initializes operator with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| gray | double | The level of gray value. |

### getColor() {#getColor--}
```
public Color getColor()
```


Returns color specified by operator.

**Returns:**
[Color](../../java.awt/color) - Color specified by operator.
### getGray() {#getGray--}
```
public final double getGray()
```


Gets or sets the level of gray value.

**Returns:**
double - double value
### setGray(double value) {#setGray-double-}
```
public final void setGray(double value)
```


Gets or sets the level of gray value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

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
