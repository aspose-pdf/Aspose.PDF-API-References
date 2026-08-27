---
title: "SetCMYKColorStroke"
linktitle: "SetCMYKColorStroke"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar K-operatorn (ställer in CMYK‑färg för strokande operationer)."
type: docs
weight: 540
url: /sv/java/com.aspose.pdf.operators/setcmykcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetCMYKColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetCMYKColorStroke

```
public class SetCMYKColorStroke extends SetColorOperator
```

Klass som representerar K-operatorn (ställer in CMYK‑färg för strokande operationer).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetCMYKColorStroke](#SetCMYKColorStroke-double-double-double-double-) | Initierar operatorn. |
| [SetCMYKColorStroke](#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getC](#getC--) | Hämtar eller sätter cyan-komponenten. |
| [getColor](#getColor--) | Returnerar RGB-färgen |
| [getK](#getK--) | Hämtar eller sätter den svarta komponenten. |
| [getM](#getM--) | Hämtar eller sätter magentakomponenten. |
| [getRGBColor](#getRGBColor-double:A-double:A-) |  |
| [getY](#getY--) | Hämtar eller sätter den gula komponenten. |
| [setC](#setC-double-) | Hämtar eller sätter cyan-komponenten. |
| [setK](#setK-double-) | Hämtar eller sätter den svarta komponenten. |
| [setM](#setM-double-) | Hämtar eller sätter magentakomponenten. |
| [setY](#setY-double-) | Hämtar eller sätter den gula komponenten. |

### SetCMYKColorStroke {#SetCMYKColorStroke-double-double-double-double-}
```
public SetCMYKColorStroke(double c, double m, double y, double k)
```

Initierar operatorn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c |  | Nivån av cyan från 0.0 till 1.0 |
| m |  | Nivån av magenta från 0.0 till 1.0 |
| y |  | Nivån av gul från 0.0 till 1.0 |
| k |  | Nivån av svart från 0.0 till 1.0 |

### SetCMYKColorStroke {#SetCMYKColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetCMYKStrokingColor-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getC {#getC--}
```
public final double getC()
```

Hämtar eller sätter cyan-komponenten.

**Returns:**
genomförbart värde

### getColor {#getColor--}
```
public Color getColor()
```

Returnerar RGB-färgen

**Returns:**
Färg som specificerats av operator.

### getK {#getK--}
```
public final double getK()
```

Hämtar eller sätter den svarta komponenten.

**Returns:**
genomförbart värde

### getM {#getM--}
```
public final double getM()
```

Hämtar eller sätter magentakomponenten.

**Returns:**
genomförbart värde

### getRGBColor {#getRGBColor-double:A-double:A-}
```
public void getRGBColor(double[] cmyk, double[] rgbOut)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmyk |  |  |
| rgbOut |  |  |

### getY {#getY--}
```
public final double getY()
```

Hämtar eller sätter den gula komponenten.

**Returns:**
genomförbart värde

### setC {#setC-double-}
```
public final void setC(double value)
```

Hämtar eller sätter cyan-komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### setK {#setK-double-}
```
public final void setK(double value)
```

Hämtar eller sätter den svarta komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### setM {#setM-double-}
```
public final void setM(double value)
```

Hämtar eller sätter magentakomponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### setY {#setY-double-}
```
public final void setY(double value)
```

Hämtar eller sätter den gula komponenten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |
