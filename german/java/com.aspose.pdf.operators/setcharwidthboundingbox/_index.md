---
title: "SetCharWidthBoundingBox"
linktitle: "SetCharWidthBoundingBox"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den d1-Operator darstellt (Glyph und Begrenzungsrahmen festlegen)."
type: docs
weight: 520
url: /de/java/com.aspose.pdf.operators/setcharwidthboundingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetCharWidthBoundingBox, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetCharWidthBoundingBox

```
public class SetCharWidthBoundingBox extends Operator
```

Klasse, die den d1-Operator darstellt (Glyph und Begrenzungsrahmen festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-double-double-double-double-double-double-) | Initialisiert den SetCharWidthBoundingBox-Operator. |
| [SetCharWidthBoundingBox](#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getLlx](#getLlx--) | Horizontale Koordinate unten links des Begrenzungsrechtecks. |
| [getLly](#getLly--) | Vertikale Koordinate unten links des Begrenzungsrechtecks. |
| [getUrx](#getUrx--) | Horizontale Koordinate oben rechts des Begrenzungsrechtecks. |
| [getUry](#getUry--) | Vertikale Koordinate oben rechts des Begrenzungsrechtecks. |
| [getWx](#getWx--) | Horizontale Verschiebung des Glyphen. |
| [getWy](#getWy--) | Vertikale Verschiebung des Glyphen. |
| [toCommand](#toCommand--) | Nur für den internen Gebrauch! |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-double-double-double-double-double-double-}
```
public SetCharWidthBoundingBox(double wx, double wy, double llx, double lly, double urx, double ury)
```

Initialisiert den SetCharWidthBoundingBox-Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| wx |  | Gibt die horizontale Verschiebung im Glyphenkoordinatensystem an. |
| wy |  | Gibt die vertikale Verschiebung im Glyphenkoordinatensystem an. Sollte 0 sein. |
| llx |  | Gibt die X-Koordinate der unteren linken Ecke an. |
| lly |  | Gibt die Y-Koordinate der unteren linken Ecke an. |
| urx |  | Gibt die X-Koordinate der oberen rechten Ecke an. |
| ury |  | Gibt die Y-Koordinate der oberen rechten Ecke an. |

### SetCharWidthBoundingBox {#SetCharWidthBoundingBox-int-com.aspose.pdf.engine.commondata.pagecontent.operators.type3fonts.SetWidthAndBoundingInformation-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getLlx {#getLlx--}
```
public double getLlx()
```

Horizontale Koordinate unten links des Begrenzungsrechtecks.

**Returns:**
double-Wert

### getLly {#getLly--}
```
public double getLly()
```

Vertikale Koordinate unten links des Begrenzungsrechtecks.

**Returns:**
double-Wert

### getUrx {#getUrx--}
```
public double getUrx()
```

Horizontale Koordinate oben rechts des Begrenzungsrechtecks.

**Returns:**
double-Wert

### getUry {#getUry--}
```
public double getUry()
```

Vertikale Koordinate oben rechts des Begrenzungsrechtecks.

**Returns:**
double-Wert

### getWx {#getWx--}
```
public double getWx()
```

Horizontale Verschiebung des Glyphen.

**Returns:**
double-Wert

### getWy {#getWy--}
```
public double getWy()
```

Vertikale Verschiebung des Glyphen.

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
