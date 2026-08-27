---
title: "DP"
linktitle: "DP"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar DP-operatorn (designamte marked content point)."
type: docs
weight: 190
url: /sv/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Klassen representerar DP-operatorn (designamte marked content point).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Konstruktor för operator-klassen. |
| [DP](#DP-java.lang.String-) | Initierar operatorn. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Hämtar egenskapsordbok |
| [getTag](#getTag--) | Hämtar markerat innehållstag |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Ställer in egenskapsordbok |
| [setTag](#setTag-java.lang.String-) | Ställer in markerat innehållstag |
| [toCommand](#toCommand--) | Endast för internt bruk! |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Konstruktor för operator-klassen.

### DP {#DP-java.lang.String-}
Initierar operatorn.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Hämtar egenskapsordbok

**Returns:**
IPdfDictionary value

### getTag {#getTag--}
```
public String getTag()
```

Hämtar markerat innehållstag

**Returns:**
String värde

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Ställer in egenskapsordbok

### setTag {#setTag-java.lang.String-}
Ställer in markerat innehållstag

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Endast för internt bruk!

**Returns:**
ICommand värde ICommand objekt

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.
