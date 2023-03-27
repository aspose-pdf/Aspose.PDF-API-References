---
title: GSave
second_title: Aspose.PDF for Java API Reference
description: Class representing q operator save graphics state.
type: docs
weight: 41
url: /java/com.aspose.pdf.operators/gsave/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class GSave extends Operator
```

Class representing q operator (save graphics state).
## Constructors

| Constructor | Description |
| --- | --- |
| [GSave(int index, ICommand command)](#GSave-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [GSave()](#GSave--) | Constructor for q operator. |
## Methods

| Method | Description |
| --- | --- |
| [toString()](#toString--) | Returns text of the operator. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### GSave(int index, ICommand command) {#GSave-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public GSave(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### GSave() {#GSave--}
```
public GSave()
```


Constructor for q operator.

### toString() {#toString--}
```
public String toString()
```


Returns text of the operator.

**Returns:**
java.lang.String - Text representation of the operator.
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

