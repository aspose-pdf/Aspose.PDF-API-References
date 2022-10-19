---
title: Fill
second_title: Aspose.PDF for Java API Reference
description: Class representing f operator fill path with nonzero winding number rule.
type: docs
weight: 37
url: /java/com.aspose.pdf.operators/fill/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class Fill extends Operator
```

Class representing f operator (fill path with nonzero winding number rule).
## Constructors

| Constructor | Description |
| --- | --- |
| [Fill(int index, ICommand command)](#Fill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [Fill()](#Fill--) | Initilizes new f operator. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [toString()](#toString--) | Returns text representation of operator. |
### Fill(int index, ICommand command) {#Fill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public Fill(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### Fill() {#Fill--}
```
public Fill()
```


Initilizes new f operator.

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


Returns text representation of operator.

**Returns:**
java.lang.String - Text representation of operator.
