---
title: ClosePathFillStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing b operator close fill and stroke path with nonzer winding rule.
type: docs
weight: 21
url: /java/com.aspose.pdf.operators/closepathfillstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ClosePathFillStroke extends Operator
```

Class representing b operator (close, fill and stroke path with nonzer winding rule).
## Constructors

| Constructor | Description |
| --- | --- |
| [ClosePathFillStroke()](#ClosePathFillStroke--) | Initializes operator. |
| [ClosePathFillStroke(int index, ICommand command)](#ClosePathFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns string representation of operator. |
| [getCommandName()](#getCommandName--) | Returns string representation of operator. |
### ClosePathFillStroke() {#ClosePathFillStroke--}
```
public ClosePathFillStroke()
```


Initializes operator.

### ClosePathFillStroke(int index, ICommand command) {#ClosePathFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ClosePathFillStroke(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

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


Returns string representation of operator.

**Returns:**
java.lang.String - String representation
### getCommandName() {#getCommandName--}
```
public String getCommandName()
```


Returns string representation of operator.

**Returns:**
java.lang.String - String representation
