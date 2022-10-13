---
title: SetCharacterSpacing
second_title: Aspose.PDF for Java API Reference
description: Class representing Tc operator set character spacing.
type: docs
weight: 60
url: /java/com.aspose.pdf.operators/setcharacterspacing/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Operator](../../com.aspose.pdf/operator), [com.aspose.pdf.operators.TextOperator](../../com.aspose.pdf.operators/textoperator), [com.aspose.pdf.operators.TextStateOperator](../../com.aspose.pdf.operators/textstateoperator)
```
public class SetCharacterSpacing extends TextStateOperator
```

Class representing Tc operator (set character spacing).
## Constructors

| Constructor | Description |
| --- | --- |
| [SetCharacterSpacing(int index, ICommand command)](#SetCharacterSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Constructor for operator class. |
| [SetCharacterSpacing(double charSpacing)](#SetCharacterSpacing-double-) | Initializes operator. |
## Methods

| Method | Description |
| --- | --- |
| [getCharSpacing()](#getCharSpacing--) | Gets the character spacing. |
| [setCharSpacing(double value)](#setCharSpacing-double-) | Sets the character spacing. |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
### SetCharacterSpacing(int index, ICommand command) {#SetCharacterSpacing-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
```
public SetCharacterSpacing(int index, ICommand command)
```


Constructor for operator class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. |
| command | [ICommand](../../com.aspose.pdf.engine.commondata.pagecontent.operators.commands/icommand) | Operator command. |

### SetCharacterSpacing(double charSpacing) {#SetCharacterSpacing-double-}
```
public SetCharacterSpacing(double charSpacing)
```


Initializes operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| charSpacing | double | Character spacing. |

### getCharSpacing() {#getCharSpacing--}
```
public double getCharSpacing()
```


Gets the character spacing.

**Returns:**
double - character spacing.
### setCharSpacing(double value) {#setCharSpacing-double-}
```
public void setCharSpacing(double value)
```


Sets the character spacing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | character spacing. |

### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts visitor object to process operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object. |

