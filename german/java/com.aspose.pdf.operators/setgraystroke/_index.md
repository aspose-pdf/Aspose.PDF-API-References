---
title: "SetGrayStroke"
linktitle: "SetGrayStroke"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den Graustufenwert für strichende Vorgänge darstellt."
type: docs
weight: 650
url: /de/java/com.aspose.pdf.operators/setgraystroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetGrayStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetGrayStroke

```
public class SetGrayStroke extends SetColorOperator
```

Klasse, die den Graustufenwert für strichende Vorgänge darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetGrayStroke](#SetGrayStroke-double-) | Initialisiert den Operator mit der angegebenen Farbe. |
| [SetGrayStroke](#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getColor](#getColor--) | Gibt die vom Operator angegebene Farbe zurück. |
| [getGray](#getGray--) | Liest oder setzt den Grauwert. |
| [setGray](#setGray-double-) | Liest oder setzt den Grauwert. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetGrayStroke {#SetGrayStroke-double-}
```
public SetGrayStroke(double gray)
```

Initialisiert den Operator mit der angegebenen Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| grau |  | Der Grauwert. |

### SetGrayStroke {#SetGrayStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetGrayStrokingColor-}
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

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
