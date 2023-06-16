---
title: SetColorRenderingIntent
second_title: Aspose.PDF for Java API Reference
description: Class representing ri operator set color rendering intent.
type: docs
weight: 65
url: /java/com.aspose.pdf.operators/setcolorrenderingintent/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class SetColorRenderingIntent extends Operator
```

Class representing ri operator (set color rendering intent).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorRenderingIntent()](#SetColorRenderingIntent--) | Initializes operator. |
| [SetColorRenderingIntent(String intentName)](#SetColorRenderingIntent-java.lang.String-) | Set Color Rendering Intent operator constructor. |
| [SetColorRenderingIntent(int index, ICommand command)](#SetColorRenderingIntent-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
## Methods

| Method | Description |
| --- | --- |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getIntentName()](#getIntentName--) | Gets or sets color rendering intent name. |
| [setIntentName(String value)](#setIntentName-java.lang.String-) | Gets or sets color rendering intent name. |
### SetColorRenderingIntent() {#SetColorRenderingIntent--}
```
public SetColorRenderingIntent()
```


Initializes operator.

### SetColorRenderingIntent(String intentName) {#SetColorRenderingIntent-java.lang.String-}
```
public SetColorRenderingIntent(String intentName)
```


Set Color Rendering Intent operator constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| intentName | java.lang.String | Color Rendering Intent. |

### SetColorRenderingIntent(int index, ICommand command) {#SetColorRenderingIntent-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetColorRenderingIntent(int index, ICommand command)
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

### getIntentName() {#getIntentName--}
```
public String getIntentName()
```


Gets or sets color rendering intent name.

**Returns:**
java.lang.String - String object
### setIntentName(String value) {#setIntentName-java.lang.String-}
```
public void setIntentName(String value)
```


Gets or sets color rendering intent name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

