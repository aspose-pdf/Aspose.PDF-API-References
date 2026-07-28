---
title: "IconFit"
linktitle: "IconFit"
second_title: "Aspose.PDF för Java API-referens"
description: "Beskriver hur widget-annotationens ikon ska visas inom dess annoteringsrektangel."
type: docs
weight: 2210
url: /sv/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

Beskriver hur widget-annotationens ikon ska visas inom dess annoteringsrektangel.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | Hämtar utrymme att tilldela längst ner på ikonen. |
| [getLeftoverLeft](#getLeftoverLeft--) | Hämtar utrymme att tilldela till vänster om ikonen. |
| [getScalingMode](#getScalingMode--) | Typen av skalning som ska användas. |
| [getScalingReason](#getScalingReason--) | Hämtar skalningsorsak. |
| [isSpreadOnBorder](#isSpreadOnBorder--) | Om true, indikerar att knappens utseende ska skalas så att det helt passar inom annoteringens gränser utan att ta hänsyn till kantlinjens bredd. |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | Konverterar skalningslägesnamn till ScalingMode-objekt. |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | Konverterar namn på skalningsorsak till ScalingReason-objekt. |
| [scalingModeToName](#scalingModeToName-int-) | Konverterar skalningslägesobjekt till namn. |
| [scalingReasonToName](#scalingReasonToName-int-) | Konverterar skalningsorsaksobjekt till namn. |
| [setLeftoverBottom](#setLeftoverBottom-double-) | Ställer in utrymme att tilldela längst ner på ikonen. |
| [setLeftoverLeft](#setLeftoverLeft-double-) | Ställer in utrymme att tilldela till vänster om ikonen. |
| [setScalingMode](#setScalingMode-int-) | Typen av skalning som ska användas. |
| [setScalingReason](#setScalingReason-int-) | Ställer in skalningsorsak. |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | Om true, indikerar att knappens utseende ska skalas så att det helt passar inom annoteringens gränser utan att ta hänsyn till kantlinjens bredd. |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

Hämtar utrymme att tilldela längst ner på ikonen.

**Returns:**
utrymme att tilldela längst ner

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

Hämtar utrymme att tilldela till vänster om ikonen.

**Returns:**
utrymme att tilldela till vänster om ikonen.

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

Typen av skalning som ska användas.

**Returns:**
ScalingMode-värde @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

Hämtar skalningsorsak.

**Returns:**
ScalingReason-värde @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

Om true, indikerar att knappens utseende ska skalas så att det helt passar inom annoteringens gränser utan att ta hänsyn till kantlinjens bredd.

**Returns:**
booleskt värde

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
Konverterar skalningslägesnamn till ScalingMode-objekt.

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
Konverterar namn på skalningsorsak till ScalingReason-objekt.

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

Konverterar skalningslägesobjekt till namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge |  | Objekt för skalningsläge. |

**Returns:**
Namn för skalningsläge.

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

Konverterar skalningsorsaksobjekt till namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orsak |  | Skalningsorsaksobjekt som ska konverteras. |

**Returns:**
Namn på skalningsorsak.

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

Ställer in utrymme att tilldela längst ner på ikonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | utrymme att tilldela längst ner |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

Ställer in utrymme att tilldela till vänster om ikonen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | utrymme att tilldela till vänster om ikonen. |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

Typen av skalning som ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ScalingMode-värde @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

Ställer in skalningsorsak.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | ScalingReason-värde @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

Om true, indikerar att knappens utseende ska skalas så att det helt passar inom annoteringens gränser utan att ta hänsyn till kantlinjens bredd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |
