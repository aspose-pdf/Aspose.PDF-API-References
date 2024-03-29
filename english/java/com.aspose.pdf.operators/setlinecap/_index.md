---
title: SetLineCap
second_title: Aspose.PDF for Java API Reference
description: Class representing J operator set line cap style.
type: docs
weight: 75
url: /java/com.aspose.pdf.operators/setlinecap/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetLineCap extends Operator
```

Class representing J operator (set line cap style).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetLineCap(int cap)](#SetLineCap-int-) |  |
| [SetLineCap(int index, ICommand command)](#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCap()](#getCap--) | Gets line caps style. |
| [setCap(int value)](#setCap-int-) | Sets line caps style. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetLineCap(int cap) {#SetLineCap-int-}
```
public SetLineCap(int cap)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cap | int |  |

### SetLineCap(int index, ICommand command) {#SetLineCap-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetLineCap(int index, ICommand command)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) |  |

### getCap() {#getCap--}
```
public final int getCap()
```


Gets line caps style.

**Returns:**
int - int value
### setCap(int value) {#setCap-int-}
```
public final void setCap(int value)
```


Sets line caps style.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

