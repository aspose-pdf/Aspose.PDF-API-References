---
title: "SetColor"
linktitle: "SetColor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Klasse für den sc-Operator dar (Farbe für nicht-strichende Vorgänge festlegen)."
type: docs
weight: 550
url: /de/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

Stellt die Klasse für den sc-Operator dar (Farbe für nicht-strichende Vorgänge festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetColor](#SetColor--) | Initialisiert den Operator. |
| [SetColor](#SetColor-double-) | Farbe für Strichoperatoren für DeviceGray, CalGray und Indexed Farbräume festlegen. |
| [SetColor](#SetColor-double:A-) | Konstruktor, der das Festlegen von Farbkomponenten ermöglicht. |
| [SetColor](#SetColor-double-double-double-) | Farbe für Strichoperator für DeviceRGB, CalRGB und Lab Farbräume festlegen |
| [SetColor](#SetColor-double-double-double-double-) | Setzt die Farbe für nicht‑konturierende Operatoren im CMYK-Farbraum. |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Initialisiert den Operator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getB](#getB--) | Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0 |
| [getC](#getC--) | Liest oder setzt die Cyan-Komponente. |
| [getColor](#getColor--) | Noch nicht unterstützt. Gibt die vom Operator angegebene Farbe zurück. |
| [getG](#getG--) | Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0 |
| [getK](#getK--) | Liest oder setzt die schwarze Komponente. |
| [getM](#getM--) | Liest oder setzt die Magenta-Komponente. |
| [getR](#getR--) | Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0 |
| [getY](#getY--) | Liest oder setzt die gelbe Komponente. |
| [setB](#setB-double-) | Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0 |
| [setC](#setC-double-) | Liest oder setzt die Cyan-Komponente. |
| [setG](#setG-double-) | Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0 |
| [setK](#setK-double-) | Liest oder setzt die schwarze Komponente. |
| [setM](#setM-double-) | Liest oder setzt die Magenta-Komponente. |
| [setR](#setR-double-) | Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0 |
| [setY](#setY-double-) | Liest oder setzt die gelbe Komponente. |
| [toString](#toString--) | Gibt die String‑Darstellung der Farbe zurück. |

### SetColor {#SetColor--}
```
public SetColor()
```

Initialisiert den Operator.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

Farbe für Strichoperatoren für DeviceGray, CalGray und Indexed Farbräume festlegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g |  | Farbwert. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Konstruktor, der das Festlegen von Farbkomponenten ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Farbe |  | Array von Farbkomponenten. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

Farbe für Strichoperator für DeviceRGB, CalRGB und Lab Farbräume festlegen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r |  | Rote Komponente. |
| g |  | Grüne Komponente. |
| b |  | Blaue Komponente. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

Setzt die Farbe für nicht‑konturierende Operatoren im CMYK-Farbraum.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c |  | Cyan-Komponente. |
| m |  | Magenta-Komponente. |
| y |  | Gelbe Komponente. |
| k |  | Schwarze Komponente. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
Initialisiert den Operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

### getB {#getB--}
```
public final double getB()
```

Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### getC {#getC--}
```
public final double getC()
```

Liest oder setzt die Cyan-Komponente.

**Returns:**
machbarer Wert

### getColor {#getColor--}
```
public Color getColor()
```

Noch nicht unterstützt. Gibt die vom Operator angegebene Farbe zurück.

**Returns:**
Operatorfarbe.

### getG {#getG--}
```
public final double getG()
```

Liest oder setzt die grüne Komponente. Wert: Der Grünwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### getK {#getK--}
```
public final double getK()
```

Liest oder setzt die schwarze Komponente.

**Returns:**
machbarer Wert

### getM {#getM--}
```
public final double getM()
```

Liest oder setzt die Magenta-Komponente.

**Returns:**
machbarer Wert

### getR {#getR--}
```
public final double getR()
```

Liest oder setzt die rote Komponente. Wert: Der Rotwert von 0,0 bis 1,0

**Returns:**
machbarer Wert

### getY {#getY--}
```
public final double getY()
```

Liest oder setzt die gelbe Komponente.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Liest oder setzt die Cyan-Komponente.

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

### setK {#setK-double-}
```
public final void setK(double value)
```

Liest oder setzt die schwarze Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |

### setM {#setM-double-}
```
public final void setM(double value)
```

Liest oder setzt die Magenta-Komponente.

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Liest oder setzt die gelbe Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |

### toString {#toString--}
```
public String toString()
```

Gibt die String‑Darstellung der Farbe zurück.

**Returns:**
String‑Darstellung der Farbe.
