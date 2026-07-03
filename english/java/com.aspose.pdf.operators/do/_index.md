---
title: Do
second_title: Aspose.PDF for Java API Reference
description: Class representing Do operator (Invoke XObject).
type: docs
weight: 180
url: /java/com.aspose.pdf.operators/do/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Do, com.aspose.pdf.Operator, com.aspose.pdf.operators.Do

```
public class Do extends Operator
```

Class representing Do operator (Invoke XObject).

## Constructors

| Constructor | Description |
| --- | --- |
| [Do](#Do--) | Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names. |
| [Do](#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-) | Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names. |
| [Do](#Do-java.lang.String-) | Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names. |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getCommandName](#getCommandName--) | Gets command name |
| [getName](#getName--) | Get name of XObject argument of the operator. |
| [setName](#setName-java.lang.String-) | Set name of XObject argument of the operator. |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### Do {#Do--}
```
public Do()
```

Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names.

### Do {#Do-int-com.aspose.pdf.engine.commondata.pagecontent.operators.xobjects.PaintXObject-}
Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names.

### Do {#Do-java.lang.String-}
Constructs new Do operator. Used for retrieving all Do operators, i.e. without checking their argument names.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Gets command name

**Returns:**
String value

### getName {#getName--}
```
public String getName()
```

Get name of XObject argument of the operator.

**Returns:**
String value

### setName {#setName-java.lang.String-}
Set name of XObject argument of the operator.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

For internal usage only!

**Returns:**
ICommand value ICommand object

### toString {#toString--}
```
public String toString()
```

Returns text representation of operator.

**Returns:**
Text representation of operator.
