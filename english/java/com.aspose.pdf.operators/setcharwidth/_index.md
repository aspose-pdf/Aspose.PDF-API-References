---
title: SetCharWidth
second_title: Aspose.PDF for Java API Reference
description: Class representing d0 operator set glyph width.
type: docs
weight: 60
url: /java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetCharWidth extends Operator
```

Class representing d0 operator (set glyph width).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCharWidth(double wx, double wy)](#SetCharWidth-double-double-) | Constructor. |
| [SetCharWidth(int index, ICommand command)](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getWx()](#getWx--) | Horizontal displacement of glyph coordinate. |
| [getWy()](#getWy--) | Vertical displacement of glyph coordinate. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toCommand()](#toCommand--) |  |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [toString()](#toString--) | Returns text representation of operator. |
### SetCharWidth(double wx, double wy) {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```


Constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wx | double | Horizontal displacement of glyph. |
| wy | double | Vertical displacement of glyph. |

### SetCharWidth(int index, ICommand command) {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCharWidth(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getWx() {#getWx--}
```
public double getWx()
```


Horizontal displacement of glyph coordinate.

**Returns:**
double - double value
### getWy() {#getWy--}
```
public double getWy()
```


Vertical displacement of glyph coordinate.

**Returns:**
double - double value
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

### toCommand() {#toCommand--}
```
public ICommand toCommand()
```




**Returns:**
[ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand)
### fromCommand(ICommand command) {#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public void fromCommand(ICommand command)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of representation
