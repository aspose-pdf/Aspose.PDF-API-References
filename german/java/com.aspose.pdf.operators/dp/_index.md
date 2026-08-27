---
title: "DP"
linktitle: "DP"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den DP-Operator (designierten markierten Inhalts-Punkt) darstellt."
type: docs
weight: 190
url: /de/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

Klasse, die den DP-Operator (designierten markierten Inhalts-Punkt) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Konstruktor für die Operator-Klasse. |
| [DP](#DP-java.lang.String-) | Initialisiert den Operator. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Ruft das Eigenschaftenverzeichnis ab |
| [getTag](#getTag--) | Liest Markierungs-Tag |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Setzt das Eigenschaftenverzeichnis |
| [setTag](#setTag-java.lang.String-) | Setzt Markierungs-Tag |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Konstruktor für die Operator-Klasse.

### DP {#DP-java.lang.String-}
Initialisiert den Operator.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Ruft das Eigenschaftenverzeichnis ab

**Returns:**
IPdfDictionary-Wert

### getTag {#getTag--}
```
public String getTag()
```

Liest Markierungs-Tag

**Returns:**
String Wert

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Setzt das Eigenschaftenverzeichnis

### setTag {#setTag-java.lang.String-}
Setzt Markierungs-Tag

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
