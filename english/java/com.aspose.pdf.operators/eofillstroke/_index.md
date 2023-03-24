---
title: EOFillStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing B operator fill and stroke path usign even-odd rule.
type: docs
weight: 33
url: /java/com.aspose.pdf.operators/eofillstroke/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class EOFillStroke extends Operator
```

Class representing B\* operator (fill and stroke path usign even-odd rule).
## Constructors

| Constructor | Description |
| --- | --- |
| [EOFillStroke()](#EOFillStroke--) | Initializes operator. |
| [EOFillStroke(int index, ICommand command)](#EOFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### EOFillStroke() {#EOFillStroke--}
```
public EOFillStroke()
```


Initializes operator.

### EOFillStroke(int index, ICommand command) {#EOFillStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public EOFillStroke(int index, ICommand command)
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

