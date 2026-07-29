---
title: "SetGray"
linktitle: "SetGray"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Graustufenwert für nicht-strichende Vorgänge festlegen."
type: docs
weight: 640
url: /de/java/com.aspose.pdf.operators/setgray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGray, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGray

```
public class SetGray extends SetColorOperator
```

Graustufenwert für nicht-strichende Vorgänge festlegen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetGray](#SetGray-double-) | Konstruktor für das Schreibprogramm. |
| [SetGray](#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getColor](#getColor--) | Gibt die vom Operator angegebene Farbe zurück. |
| [getGray](#getGray--) | Liest oder setzt den Grauwert. |
| [setGray](#setGray-double-) | Liest oder setzt den Grauwert. |
| [toString](#toString--) | Gibt die Zeichenkettenrepräsentation des Operators zurück. |

### SetGray {#SetGray-double-}
```
public SetGray(double gray)
```

Konstruktor für das Schreibprogramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| grau |  | Der Grauwert. |

### SetGray {#SetGray-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayNonstrokingColor-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getColor {#getColor--}
```
public Color getColor()
```

Gibt die vom Operator angegebene Farbe zurück.

**Returns:**
Vom Operator angegebene Farbe.

### getGray {#getGray--}
```
public final double getGray()
```

Liest oder setzt den Grauwert.

**Returns:**
double-Wert

### setGray {#setGray-double-}
```
public final void setGray(double value)
```

Liest oder setzt den Grauwert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toString {#toString--}
```
public String toString()
```

Gibt die Zeichenkettenrepräsentation des Operators zurück.

**Returns:**
Zeichenkettenrepräsentation des Operators.
