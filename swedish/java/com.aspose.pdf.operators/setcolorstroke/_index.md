---
title: "SetColorStroke"
linktitle: "SetColorStroke"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass som representerar SC-operatorn (ställer in färg för strokande färgoperatorer)."
type: docs
weight: 600
url: /sv/java/com.aspose.pdf.operators/setcolorstroke/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetColorOperator com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.SetColorOperator, com.aspose.pdf.operators.BasicSetColorOperator com.aspose.pdf.operators.SetColorStroke, com.aspose.pdf.operators.BasicSetColorOperator, com.aspose.pdf.operators.SetColorStroke

```
public class SetColorStroke extends BasicSetColorOperator
```

Klass som representerar SC-operatorn (ställer in färg för strokande färgoperatorer).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SetColorStroke](#SetColorStroke--) | Initierar operatorn. |
| [SetColorStroke](#SetColorStroke-double-) | Ställ in färg för stroke-operatorer för DeviceGray, CalGray och Indexed-färgrymder. |
| [SetColorStroke](#SetColorStroke-double:A-) | Konstruktor som tillåter att sätta färgkomponenter. |
| [SetColorStroke](#SetColorStroke-double-double-double-) | Ställ in färg för stroke-operator för DeviceRGB, CalRGB och Lab-färgrymder. |
| [SetColorStroke](#SetColorStroke-double-double-double-double-) | Ställ in färg för stroke-operator för CMYK-färgrymd. |
| [SetColorStroke](#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-) | Initierar operatorn. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar besökarobjekt för att bearbeta operatorn. |
| [getB](#getB--) | Hämtar eller sätter den blå komponenten. Värde: Nivån av blått från 0,0 till 1,0. |
| [getC](#getC--) | Hämtar eller sätter cyan-komponenten. |
| [getColor](#getColor--) | Returnerar färg som specificerats av operator. |
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

### SetColorStroke {#SetColorStroke--}
```
public SetColorStroke()
```

Initierar operatorn.

### SetColorStroke {#SetColorStroke-double-}
```
public SetColorStroke(double g)
```

Ställ in färg för stroke-operatorer för DeviceGray, CalGray och Indexed-färgrymder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| g |  | Färgvärde. |

### SetColorStroke {#SetColorStroke-double:A-}
```
public SetColorStroke(double[] color)
```

Konstruktor som tillåter att sätta färgkomponenter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color |  | Array av färgkomponenter. |

### SetColorStroke {#SetColorStroke-double-double-double-}
```
public SetColorStroke(double r, double g, double b)
```

Ställ in färg för stroke-operator för DeviceRGB, CalRGB och Lab-färgrymder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| r |  | Röd komponent. |
| g |  | Grön komponent. |
| b |  | Blå komponent. |

### SetColorStroke {#SetColorStroke-double-double-double-double-}
```
public SetColorStroke(double c, double m, double y, double k)
```

Ställ in färg för stroke-operator för CMYK-färgrymd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| c |  | Cyan komponent. |
| m |  | Magenta komponent. |
| y |  | Gul komponent. |
| k |  | Svart komponent. |

### SetColorStroke {#SetColorStroke-int-com.aspose.pdf.engine.commondata.pagecontent.operators.color.SetStrokingColor-}
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
| värde |  | double-värde |

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
