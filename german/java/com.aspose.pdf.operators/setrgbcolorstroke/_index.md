---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den RG-Operator (setzt die RGB-Farbe für strichende Operatoren) darstellt."
type: docs
weight: 720
url: /de/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Klasse, die den RG-Operator (setzt die RGB-Farbe für strichende Operatoren) darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Initialisiert den Operator mit Farbe. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Konstruktor für das Schreibprogramm. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getB](#getB--) | Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0 |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Gibt die vom Operator angegebene Farbe zurück. |
| [getG](#getG--) | Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0 |
| [getR](#getR--) | Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0 |
| [setB](#setB-double-) | Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0 |
| [setG](#setG-double-) | Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0 |
| [setR](#setR-double-) | Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0 |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Initialisiert den Operator mit Farbe.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Konstruktor für das Schreibprogramm.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r |  | Der Rotwert von 0.0 bis 1.0 |
| g |  | Der Grünwert von 0.0 bis 1.0 |
| b |  | Der Blauwert von 0.0 bis 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getB {#getB--}
```
public final double getB()
```

Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Gibt die vom Operator angegebene Farbe zurück.

**Returns:**
Vom Operator angegebene Farbe.

### getG {#getG--}
```
public final double getG()
```

Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### getR {#getR--}
```
public final double getR()
```

Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### setB {#setB-double-}
```
public final void setB(double value)
```

Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |

### setG {#setG-double-}
```
public final void setG(double value)
```

Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |

### setR {#setR-double-}
```
public final void setR(double value)
```

Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.
