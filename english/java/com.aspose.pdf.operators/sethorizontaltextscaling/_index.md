---
title: SetHorizontalTextScaling
second_title: Aspose.PDF for Java API Reference
description: Class representing Tz operator set horizontal text scaling.
type: docs
weight: 72
url: /java/com.aspose.pdf.operators/sethorizontaltextscaling/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextStateOperator](../../com.aspose.pdf.operators/textstateoperator)
```
public class SetHorizontalTextScaling extends TextStateOperator
```

Class representing Tz operator (set horizontal text scaling).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetHorizontalTextScaling(int index, ICommand command)](#SetHorizontalTextScaling-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetHorizontalTextScaling(double horizintalScaling)](#SetHorizontalTextScaling-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getHorizontalScaling()](#getHorizontalScaling--) | Gets the horizontal scaling. |
| [setHorizontalScaling(double value)](#setHorizontalScaling-double-) | Sets the horizontal scaling. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetHorizontalTextScaling(int index, ICommand command) {#SetHorizontalTextScaling-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetHorizontalTextScaling(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetHorizontalTextScaling(double horizintalScaling) {#SetHorizontalTextScaling-double-}
```
public SetHorizontalTextScaling(double horizintalScaling)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| horizintalScaling | double | Horizontal scaling. |

### getHorizontalScaling() {#getHorizontalScaling--}
```
public double getHorizontalScaling()
```


Gets the horizontal scaling.

**Returns:**
double - double value
### setHorizontalScaling(double value) {#setHorizontalScaling-double-}
```
public void setHorizontalScaling(double value)
```


Sets the horizontal scaling.

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

