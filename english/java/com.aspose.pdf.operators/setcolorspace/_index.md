---
title: SetColorSpace
second_title: Aspose.PDF for Java API Reference
description: Class representing cs operator (set colorspace for non-stroking operations)
type: docs
weight: 580
url: /java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Class representing cs operator (set colorspace for non-stroking operations)

## Constructors

| Constructor | Description |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Constructor for operator class. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Initializes operator. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getCommandName](#getCommandName--) | Gets command name. |
| [getName](#getName--) | Gets color space name. |
| [setName](#setName-java.lang.String-) | Sets color space name. |
| [toCommand](#toCommand--) | For internal usage only! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Constructor for operator class.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Initializes operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Gets command name.

**Returns:**
String value

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
