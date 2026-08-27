---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den SC-Operator darstellt, Farbe für strichende Farboperatoren festlegt."
type: docs
weight: 600
url: /de/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Klasse, die den SC-Operator darstellt, Farbe für strichende Farboperatoren festlegt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Initialisiert den Operator. |
| [SetColorStroke](#SetColorStroke-double-) | Farbe für Strichoperatoren für DeviceGray, CalGray und Indexed Farbräume festlegen. |
| [SetColorStroke](#SetColorStroke-double:A-) | Konstruktor, der das Festlegen von Farbkomponenten ermöglicht. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Farbe für Strichoperator für DeviceRGB, CalRGB und Lab Farbräume festlegen |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Farbe für Strichoperator für CMYK Farbraum festlegen |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Initialisiert den Operator. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getB](#getB--) | Liest oder setzt die blaue Komponente. Wert: Der Blauwert von 0,0 bis 1,0 |
| [getC](#getC--) | Liest oder setzt die Cyan-Komponente. |
| [getColor](#getColor--) | Gibt die vom Operator angegebene Farbe zurück. |
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

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Initialisiert den Operator.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Farbe für Strichoperatoren für DeviceGray, CalGray und Indexed Farbräume festlegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| g |  | Farbwert. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Konstruktor, der das Festlegen von Farbkomponenten ermöglicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Farbe |  | Array von Farbkomponenten. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Farbe für Strichoperator für DeviceRGB, CalRGB und Lab Farbräume festlegen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| r |  | Rote Komponente. |
| g |  | Grüne Komponente. |
| b |  | Blaue Komponente. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Farbe für Strichoperator für CMYK Farbraum festlegen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c |  | Cyan-Komponente. |
| m |  | Magenta-Komponente. |
| y |  | Gelbe Komponente. |
| k |  | Schwarze Komponente. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
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
| Wert |  | double-Wert |

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
