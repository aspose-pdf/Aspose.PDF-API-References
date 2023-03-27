---
title: SetCharWidthBoundingBox
second_title: Aspose.PDF for Java API Reference
description: Class representing d1 operator set glyph and bounding box.
type: docs
weight: 59
url: /java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetCharWidthBoundingBox extends Operator
```

Class representing d1 operator (set glyph and bounding box).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Initializes operator. |
| [SetCharWidthBoundingBox(int index, ICommand command)](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getWx()](#getWx--) | Horizontal displacement of glyph. |
| [getWy()](#getWy--) | Vertical displacement of glyph. |
| [getLlx()](#getLlx--) | Lower-left horizontal coordinate of bounding rectangle. |
| [getLly()](#getLly--) | Lower-left vertical coordinate of bounding rectangle. |
| [getUrx()](#getUrx--) | Upper-right horizontal coordinate of bounding rectangle. |
| [getUry()](#getUry--) | Upper-right vertical coordinate of bounding rectangle. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [fromCommand(ICommand command)](#fromCommand-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
| [toCommand()](#toCommand--) |  |
| [toString()](#toString--) | Returns text representation of operator. |
### SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury) {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| wx | double | double value |
| wy | double | double value |
| llx | double | double value |
| lly | double | double value |
| urx | double | double value |
| ury | double | double value |

### SetCharWidthBoundingBox(int index, ICommand command) {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCharWidthBoundingBox(int index, ICommand command)
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


Horizontal displacement of glyph.

**Returns:**
double - double value
### getWy() {#getWy--}
```
public double getWy()
```


Vertical displacement of glyph.

**Returns:**
double - double value
### getLlx() {#getLlx--}
```
public double getLlx()
```


Lower-left horizontal coordinate of bounding rectangle.

**Returns:**
double - double value
### getLly() {#getLly--}
```
public double getLly()
```


Lower-left vertical coordinate of bounding rectangle.

**Returns:**
double - double value
### getUrx() {#getUrx--}
```
public double getUrx()
```


Upper-right horizontal coordinate of bounding rectangle.

**Returns:**
double - double value
### getUry() {#getUry--}
```
public double getUry()
```


Upper-right vertical coordinate of bounding rectangle.

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
### toString() {#toString--}
```
public String toString()
```


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of representation
