---
title: EndPath
second_title: Aspose.PDF for Java API Reference
description: Class representing n operator end path without filling or stroking.
type: docs
weight: 36
url: /java/com.aspose.pdf.operators/endpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class EndPath extends Operator
```

Class representing n operator (end path without filling or stroking).
## Constructors

| Constructor | Description |
| --- | --- |
| [EndPath(int index, ICommand command)](#EndPath-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [EndPath()](#EndPath--) | Constructor for writing program. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Text representation of operator. |
### EndPath(int index, ICommand command) {#EndPath-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public EndPath(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### EndPath() {#EndPath--}
```
public EndPath()
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


Text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
