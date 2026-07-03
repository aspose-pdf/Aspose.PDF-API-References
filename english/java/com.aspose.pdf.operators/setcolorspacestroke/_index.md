---
title: SetColorSpaceStroke
second_title: Aspose.PDF for Java API Reference
description: Class representing CS operator (set color for stroking operations).
type: docs
weight: 590
url: /java/com.aspose.pdf.operators/setcolorspacestroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpaceStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpaceStroke

```
public class SetColorSpaceStroke extends Operator
```

Class representing CS operator (set color for stroking operations).

## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorSpaceStroke](#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-) | Constructor for operator class. |
| [SetColorSpaceStroke](#SetColorSpaceStroke-java.lang.String-) | Initializes operator. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts a visitor object to process operator. |
| [getName](#getName--) | Gets color space name. |
| [setName](#setName-java.lang.String-) | Sets color space name. |
| [toCommand](#toCommand--) | For internal usage only! |

### SetColorSpaceStroke {#SetColorSpaceStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceStroking-}
Constructor for operator class.

### SetColorSpaceStroke {#SetColorSpaceStroke-java.lang.String-}
Initializes operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts a visitor object to process operator.

### getName {#getName--}
```
public String getName()
```

Gets color space name.

**Returns:**
String value

### setName {#setName-java.lang.String-}
Sets color space name.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object
