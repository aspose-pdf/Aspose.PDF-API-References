---
title: SetLineJoin
second_title: Aspose.PDF for Java API Reference
description: Class representing j operator set line join style.
type: docs
weight: 76
url: /java/com.aspose.pdf.operators/setlinejoin/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetLineJoin extends Operator
```

Class representing j operator (set line join style).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetLineJoin()](#SetLineJoin--) | Initializes operator. |
| [SetLineJoin(int join)](#SetLineJoin-int-) |  |
| [SetLineJoin(int index, ICommand command)](#SetLineJoin-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getJoin()](#getJoin--) |  |
| [setJoin(int value)](#setJoin-int-) |  |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetLineJoin() {#SetLineJoin--}
```
public SetLineJoin()
```


Initializes operator.

### SetLineJoin(int join) {#SetLineJoin-int-}
```
public SetLineJoin(int join)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| join | int |  |

### SetLineJoin(int index, ICommand command) {#SetLineJoin-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetLineJoin(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getJoin() {#getJoin--}
```
public final int getJoin()
```




**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public final void setJoin(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

