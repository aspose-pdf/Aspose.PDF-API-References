---
title: Clip
second_title: Aspose.PDF for Java API Reference
description: Class representing W operator set clipping path using non-zero winding rule.
type: docs
weight: 18
url: /java/com.aspose.pdf.operators/clip/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Clip extends Operator
```

Class representing W operator (set clipping path using non-zero winding rule).
## Constructors

| Constructor | Description |
| --- | --- |
| [Clip(int index, ICommand command)](#Clip-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [Clip()](#Clip--) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operators. |
### Clip(int index, ICommand command) {#Clip-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Clip(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### Clip() {#Clip--}
```
public Clip()
```


Constructor for writing program.

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


Returns text representation of operators.

**Returns:**
java.lang.String - Text representation of operator.
