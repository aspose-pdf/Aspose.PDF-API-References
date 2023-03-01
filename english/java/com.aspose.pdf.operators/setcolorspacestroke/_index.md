---
title: SetColorSpaceStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing CS operator set color for stroking operations.
type: docs
weight: 65
url: /java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetColorSpaceStroke extends Operator
```

Class representing CS operator (set color for stroking operations).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorSpaceStroke(String name)](#SetColorSpaceStroke-java.lang.String-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets color space name. |
| [setName(String value)](#setName-java.lang.String-) | Sets color space name. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toCommand()](#toCommand--) |  |
### SetColorSpaceStroke(String name) {#SetColorSpaceStroke-java.lang.String-}
```
public SetColorSpaceStroke(String name)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Color space name. |

### getName() {#getName--}
```
public String getName()
```


Gets color space name.

**Returns:**
java.lang.String - String value
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets color space name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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
