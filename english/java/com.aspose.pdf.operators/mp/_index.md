---
title: MP
second_title: Aspose.PDF for Java API Reference
description: Class representing MP operator define marked-content point.
type: docs
weight: 47
url: /java/com.aspose.pdf.operators/mp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class MP extends Operator
```

Class representing MP operator (define marked-content point).
## Constructors

| Constructor | Description |
| --- | --- |
| [MP(String tag)](#MP-java.lang.String-) | Initializes operator. |
| [MP(int index, ICommand command)](#MP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [getTag()](#getTag--) | Gets marked content tag |
| [setTag(String value)](#setTag-java.lang.String-) | Sets marked content tag |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### MP(String tag) {#MP-java.lang.String-}
```
public MP(String tag)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | Marked content tag. |

### MP(int index, ICommand command) {#MP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public MP(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### getTag() {#getTag--}
```
public String getTag()
```


Gets marked content tag

**Returns:**
java.lang.String - String value
### setTag(String value) {#setTag-java.lang.String-}
```
public void setTag(String value)
```


Sets marked content tag

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

