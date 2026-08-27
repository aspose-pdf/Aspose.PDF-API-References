---
title: "SetRGBColorStroke"
linktitle: "SetRGBColorStroke"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar RG-operatorn (sätter RGB-färg för strokande operatorer)."
type: docs
weight: 720
url: /sv/java/com.aspose.pdf.operators/setrgbcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.SetRGBColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.SetRGBColorStroke

```
public class SetRGBColorStroke extends SetColorOperator
```

Klass som representerar RG-operatorn (sätter RGB-färg för strokande operatorer).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetRGBColorStroke](#SetRGBColorStroke-java.awt.Color-) | Initierar operator med färg. |
| [SetRGBColorStroke](#SetRGBColorStroke-double-double-double-) | Konstruktor för skrivprogrammet. |
| [SetRGBColorStroke](#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-) | Konstruktor för operator-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getB](#getB--) | Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0. |
| [getCMYKColor](#getCMYKColor-double:A-double:A-) |  |
| [getColor](#getColor--) | Returnerar färg som specificerats av operator. |
| [getG](#getG--) | Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0. |
| [getR](#getR--) | Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0. |
| [setB](#setB-double-) | Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0. |
| [setG](#setG-double-) | Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0. |
| [setR](#setR-double-) | Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |

### SetRGBColorStroke {#SetRGBColorStroke-java.awt.Color-}
Initierar operator med färg.

### SetRGBColorStroke {#SetRGBColorStroke-double-double-double-}
```
public SetRGBColorStroke(double r, double g, double b)
```

Konstruktor för skrivprogrammet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r |  | Rödnivån från 0.0 till 1.0 |
| g |  | Grönnivån från 0.0 till 1.0 |
| b |  | Blånivån från 0.0 till 1.0 |

### SetRGBColorStroke {#SetRGBColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetRGBStrokingColor-}
Konstruktor för operator-klassen.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getB {#getB--}
```
public final double getB()
```

Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0.

**Returns:**
genomförbart värde

### getCMYKColor {#getCMYKColor-double:A-double:A-}
```
public void getCMYKColor(double[] rgb, double[] cmykOut)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rgb |  |  |
| cmykOut |  |  |

### getColor {#getColor--}
```
public Color getColor()
```

Returnerar färg som specificerats av operator.

**Returns:**
Färg som specificerats av operator.

### getG {#getG--}
```
public final double getG()
```

Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0.

**Returns:**
genomförbart värde

### getR {#getR--}
```
public final double getR()
```

Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0.

**Returns:**
genomförbart värde

### setB {#setB-double-}
```
public final void setB(double value)
```

Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### setG {#setG-double-}
```
public final void setG(double value)
```

Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### setR {#setR-double-}
```
public final void setR(double value)
```

Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | genomförbart värde |

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.
