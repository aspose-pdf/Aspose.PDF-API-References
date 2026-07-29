---
title: "SetColor"
linktitle: "SetColor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar klass för sc-operatorn (ställer in färg för icke‑strokande operationer)."
type: docs
weight: 550
url: /sv/java/com.aspose.pdf.operators/setcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColor, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColor

```
public class SetColor extends BasicSetColorOperator
```

Representerar klass för sc-operatorn (ställer in färg för icke‑strokande operationer).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetColor](#SetColor--) | Initierar operatorn. |
| [SetColor](#SetColor-double-) | Ställ in färg för stroke-operatorer för DeviceGray, CalGray och Indexed-färgrymder. |
| [SetColor](#SetColor-double:A-) | Konstruktor som tillåter att specificera färgkomponenter. |
| [SetColor](#SetColor-double-double-double-) | Ställ in färg för stroke-operator för DeviceRGB, CalRGB och Lab-färgrymder. |
| [SetColor](#SetColor-double-double-double-double-) | Ställ in färg för icke‑konturoperator för CMYK-färgrymden. |
| [SetColor](#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-) | Initierar operatorn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getB](#getB--) | Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0. |
| [getC](#getC--) | Hämtar eller sätter cyan-komponenten. |
| [getColor](#getColor--) | Stöds ännu inte. Returnerar färg som specificeras av operatorn. |
| [getG](#getG--) | Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0. |
| [getK](#getK--) | Hämtar eller sätter den svarta komponenten. |
| [getM](#getM--) | Hämtar eller sätter magentakomponenten. |
| [getR](#getR--) | Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0. |
| [getY](#getY--) | Hämtar eller sätter den gula komponenten. |
| [setB](#setB-double-) | Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0. |
| [setC](#setC-double-) | Hämtar eller sätter cyan-komponenten. |
| [setG](#setG-double-) | Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0. |
| [setK](#setK-double-) | Hämtar eller sätter den svarta komponenten. |
| [setM](#setM-double-) | Hämtar eller sätter magentakomponenten. |
| [setR](#setR-double-) | Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0. |
| [setY](#setY-double-) | Hämtar eller sätter den gula komponenten. |
| [toString](#toString--) | Returnerar strängrepresentation av färg. |

### SetColor {#SetColor--}
```
public SetColor()
```

Initierar operatorn.

### SetColor {#SetColor-double-}
```
public SetColor(double g)
```

Ställ in färg för stroke-operatorer för DeviceGray, CalGray och Indexed-färgrymder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g |  | Färgvärde. |

### SetColor {#SetColor-double:A-}
```
public SetColor(double[] color)
```

Konstruktor som tillåter att specificera färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color |  | Array av färgkomponenter. |

### SetColor {#SetColor-double-double-double-}
```
public SetColor(double r, double g, double b)
```

Ställ in färg för stroke-operator för DeviceRGB, CalRGB och Lab-färgrymder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r |  | Röd komponent. |
| g |  | Grön komponent. |
| b |  | Blå komponent. |

### SetColor {#SetColor-double-double-double-double-}
```
public SetColor(double c, double m, double y, double k)
```

Ställ in färg för icke‑konturoperator för CMYK-färgrymden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c |  | Cyan komponent. |
| m |  | Magenta komponent. |
| y |  | Gul komponent. |
| k |  | Svart komponent. |

### SetColor {#SetColor-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetNonstrokingColor-}
Initierar operatorn.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar besökarobjekt för att bearbeta operatorn.

### getB {#getB--}
```
public final double getB()
```

Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0.

**Returns:**
genomförbart värde

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

Stöds ännu inte. Returnerar färg som specificeras av operatorn.

**Returns:**
Operatorfärg.

### getG {#getG--}
```
public final double getG()
```

Hämtar eller sätter den gröna komponenten. Värde: Nivån av grönt från 0,0 till 1,0.

**Returns:**
genomförbart värde

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

### getR {#getR--}
```
public final double getR()
```

Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0.

**Returns:**
genomförbart värde

### getY {#getY--}
```
public final double getY()
```

Hämtar eller sätter den gula komponenten.

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

### setC {#setC-double-}
```
public final void setC(double value)
```

Hämtar eller sätter cyan-komponenten.

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

### setR {#setR-double-}
```
public final void setR(double value)
```

Hämtar eller sätter den röda komponenten. Värde: Nivån av rött från 0,0 till 1,0.

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

### toString {#toString--}
```
public String toString()
```

Returnerar strängrepresentation av färg.

**Returns:**
Strängrepresentation av färg.
