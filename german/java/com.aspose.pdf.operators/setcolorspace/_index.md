---
title: "SetColorSpace"
linktitle: "SetColorSpace"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den cs-Operator darstellt (Farbraum für nicht-strichende Vorgänge festlegen)"
type: docs
weight: 580
url: /de/java/com.aspose.pdf.operators/setcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorSpace, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorSpace

```
public class SetColorSpace extends Operator
```

Klasse, die den cs-Operator darstellt (Farbraum für nicht-strichende Vorgänge festlegen)

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetColorSpace](#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-) | Konstruktor für die Operator-Klasse. |
| [SetColorSpace](#SetColorSpace-java.lang.String-) | Initialisiert den Operator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getCommandName](#getCommandName--) | Liest Befehlsnamen. |
| [getName](#getName--) | Liefert den Namen des Farbraums. |
| [setName](#setName-java.lang.String-) | Setzt den Namen des Farbraums. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |

### SetColorSpace {#SetColorSpace-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetColorSpaceNonstroking-}
Konstruktor für die Operator-Klasse.

### SetColorSpace {#SetColorSpace-java.lang.String-}
Initialisiert den Operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Liest Befehlsnamen.

**Returns:**
String Wert

### getName {#getName--}
```
public String getName()
```

Liefert den Namen des Farbraums.

**Returns:**
String Wert

### setName {#setName-java.lang.String-}
Setzt den Namen des Farbraums.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Nur für den internen Gebrauch!

**Returns:**
ICommand-Wert ICommand-Objekt
