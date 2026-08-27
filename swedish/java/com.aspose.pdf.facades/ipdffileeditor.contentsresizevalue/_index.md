---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Aspose.PDF för Java API-referens"
description: "Värde för marginal eller innehållsstorlek angivet i procent av standardenhetsmått. Denna klass används i ContentsResizeParameters."
type: docs
weight: 310
url: /sv/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Värde för marginal eller innehållsstorlek angivet i procent av standardenhetsmått. Denna klass används i ContentsResizeParameters.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [auto](#auto--) | Initierar automatiskt beräknat värde. |
| [getValue](#getValue--) | Hämtar angivet värde. Använd Unit-egenskapen för att få värdeenheter. |
| [isPercent](#isPercent--) | Returnerar true om värdet är uttryckt i procent; False om värdet är uttryckt i standardenheter. |
| [percents](#percents-double-) | Initierar värde i procent. |
| [setPercentValue](#setPercentValue-double-) | Ställer in värde i procent av sidans storlek. |
| [setUnitValue](#setUnitValue-double-) | Ställer in värde i standardrymdsenheter. |
| [units](#units-double-) | Initierar värde i standardrymdsenheter. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Initierar automatiskt beräknat värde.

**Returns:**
Ny värdeinstans.

### getValue {#getValue--}
```
public final double getValue()
```

Hämtar angivet värde. Använd Unit-egenskapen för att få värdeenheter.

**Returns:**
double-värde

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Returnerar true om värdet är uttryckt i procent; False om värdet är uttryckt i standardenheter.

**Returns:**
booleskt värde

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Initierar värde i procent.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Värde i procent. |

**Returns:**
Ny värdeinstans.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Ställer in värde i procent av sidans storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Ställer in värde i standardrymdsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Initierar värde i standardrymdsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Värde i enheter. |

**Returns:**
Ny värdeinstans.
