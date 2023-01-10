---
title: SetMiterLimit
second_title: Aspose.PDF for Java API Reference
description: Class representing M operator set miter limit.
type: docs
weight: 76
url: /java/com.aspose.pdf.operators/setmiterlimit/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetMiterLimit extends Operator
```

Class representing M operator (set miter limit).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetMiterLimit(int index, ICommand command)](#SetMiterLimit-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetMiterLimit(double miterLimit)](#SetMiterLimit-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getMiterLimit()](#getMiterLimit--) | Gets the miter limit. |
| [setMiterLimit(double value)](#setMiterLimit-double-) | Sets the miter limit. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetMiterLimit(int index, ICommand command) {#SetMiterLimit-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetMiterLimit(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetMiterLimit(double miterLimit) {#SetMiterLimit-double-}
```
public SetMiterLimit(double miterLimit)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| miterLimit | double | Mitel limit. |

### getMiterLimit() {#getMiterLimit--}
```
public double getMiterLimit()
```


Gets the miter limit.

**Returns:**
double - double value
### setMiterLimit(double value) {#setMiterLimit-double-}
```
public void setMiterLimit(double value)
```


Sets the miter limit.

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

