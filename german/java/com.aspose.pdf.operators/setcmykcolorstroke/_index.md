---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die den K-Operator darstellt (CMYK-Farbe für strichende Vorgänge festlegen)."
type: docs
weight: 540
url: /de/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Klasse, die den K-Operator darstellt (CMYK-Farbe für strichende Vorgänge festlegen).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Initialisiert den Operator. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Konstruktor für die Operator-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten. |
| [getC](#getC--) | Liest oder setzt die Cyan-Komponente. |
| [getColor](#getColor--) | Gibt die RGB-Farbe zurück |
| [getK](#getK--) | Liest oder setzt die schwarze Komponente. |
| [getM](#getM--) | Liest oder setzt die Magenta-Komponente. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Liest oder setzt die gelbe Komponente. |
| [setC](#setC-double-) | Liest oder setzt die Cyan-Komponente. |
| [setK](#setK-double-) | Liest oder setzt die schwarze Komponente. |
| [setM](#setM-double-) | Liest oder setzt die Magenta-Komponente. |
| [setY](#setY-double-) | Liest oder setzt die gelbe Komponente. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Initialisiert den Operator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| c |  | Der Cyan-Wert von 0.0 bis 1.0 |
| m |  | Der Magenta-Wert von 0.0 bis 1.0 |
| y |  | Der Gelb-Wert von 0.0 bis 1.0 |
| k |  | Der Schwarz-Wert von 0.0 bis 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Konstruktor für die Operator-Klasse.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein Besucherobjekt, um den Operator zu verarbeiten.

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

Gibt die RGB-Farbe zurück

**Returns:**
Vom Operator angegebene Farbe.

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

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Liest oder setzt die gelbe Komponente.

**Returns:**
machbarer Wert

### setC {#setC-double-}
```
public final void setC(double value)
```

Liest oder setzt die Cyan-Komponente.

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

### setY {#setY-double-}
```
public final void setY(double value)
```

Liest oder setzt die gelbe Komponente.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | machbarer Wert |
