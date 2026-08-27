---
title: "SetCharWidth"
linktitle: "SetCharWidth"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den d0-Operator darstellt (Glyphenbreite festlegen)."
type: docs
weight: 510
url: /de/java/com.aspose.pdf.operators/setcharwidth/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidth, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidth

```
public class SetCharWidth extends Operator
```

Klasse, die den d0-Operator darstellt (Glyphenbreite festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetCharWidth](#SetCharWidth-double-double-) | Konstruktor. |
| [SetCharWidth](#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getWx](#getWx--) | Horizontale Verschiebung der Glyphenkoordinate. |
| [getWy](#getWy--) | Vertikale Verschiebung der Glyphenkoordinate. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetCharWidth {#SetCharWidth-double-double-}
```
public SetCharWidth(double wx, double wy)
```

Konstruktor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| wx |  | Horizontale Verschiebung des Glyphen. |
| wy |  | Vertikale Verschiebung des Glyphen. |

### SetCharWidth {#SetCharWidth-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getWx {#getWx--}
```
public double getWx()
```

Horizontale Verschiebung der Glyphenkoordinate.

**Returns:**
double-Wert

### getWy {#getWy--}
```
public double getWy()
```

Vertikale Verschiebung der Glyphenkoordinate.

**Returns:**
double-Wert

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
Textdarstellung der Darstellung
