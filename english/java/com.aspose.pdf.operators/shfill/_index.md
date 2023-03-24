---
title: ShFill
second_title: Aspose.PDF for Java API Reference
description: Class representing sh operator paint area with shading pattern.
type: docs
weight: 85
url: /java/com.aspose.pdf.operators/shfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator)
```
public class ShFill extends Operator
```

Class representing sh operator (paint area with shading pattern).
## Constructors

| Constructor | Description |
| --- | --- |
| [ShFill()](#ShFill--) | Initializes operator. |
| [ShFill(int index, ICommand command)](#ShFill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [ShFill(String shadingName)](#ShFill-java.lang.String-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the shading name. |
| [setName(String value)](#setName-java.lang.String-) | Sets the shading name. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### ShFill() {#ShFill--}
```
public ShFill()
```


Initializes operator.

### ShFill(int index, ICommand command) {#ShFill-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public ShFill(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### ShFill(String shadingName) {#ShFill-java.lang.String-}
```
public ShFill(String shadingName)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shadingName | java.lang.String | String Shading name. |

### getName() {#getName--}
```
public String getName()
```


Gets the shading name.

**Returns:**
java.lang.String - String value
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets the shading name.

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

