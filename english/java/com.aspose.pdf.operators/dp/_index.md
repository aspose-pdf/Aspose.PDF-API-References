---
title: DP
linktitle: DP
second_title: Aspose.PDF for Java API Reference
description: Class represeting DP operator (designamte marked content point).
type: docs
weight: 190
url: /java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Class represeting DP operator (designamte marked content point).

## Constructors

| Constructor | Description |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Constructor for operator class. |
| [DP](#DP-java.lang.String-) | Initializes operator. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts visitor object to process operator. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Gets properties dictionary |
| [getTag](#getTag--) | Gets marked content tag |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Sets properties' dictionary |
| [setTag](#setTag-java.lang.String-) | Sets marked content tag |
| [toCommand](#toCommand--) | For internal usage only! |
| [toString](#toString--) | Returns text representation of operator. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Constructor for operator class.

### DP {#DP-java.lang.String-}
Initializes operator.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts visitor object to process operator.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Gets properties dictionary

**Returns:**
IPdfDictionary value

### getTag {#getTag--}
```
public String getTag()
```

Gets marked content tag

**Returns:**
String value

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Sets properties' dictionary

### setTag {#setTag-java.lang.String-}
Sets marked content tag

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
