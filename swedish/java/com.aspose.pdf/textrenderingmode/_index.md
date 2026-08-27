---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Aspose.PDF för Java API-referens"
description: "Textrenderingsläget, Tmode, bestämmer om visning av text ska leda till att glyfkonturer streckas, fylls, används som en beskärningsgräns, eller någon kombination av de tre."
type: docs
weight: 5240
url: /sv/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

Textrenderingsläget, Tmode, bestämmer om visning av text ska leda till att glyfkonturer streckas, fylls, används som en beskärningsgräns, eller någon kombination av de tre.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Lägg till text till sökväg för klippning. |
| [FillText](#FillText) | Fyll text. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Fyll text och lägg till i sökväg för klippning (se 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Fyll, sedan konturera text. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Fyll, sedan konturera text och lägg till i sökväg för klippning. |
| [Invisible](#Invisible) | Varken fyll eller konturera text (osynlig). |
| [StrokeText](#StrokeText) | Konturera text. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Konturera text och lägg till i sökväg för klippning. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Returnerar enum‑konstanten av denna typ med det angivna namnet. |
| [values](#values--) | Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Lägg till text till sökväg för klippning.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Fyll text.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Fyll text och lägg till i sökväg för klippning (se 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Fyll, sedan konturera text.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Fyll, sedan konturera text och lägg till i sökväg för klippning.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Varken fyll eller konturera text (osynlig).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Konturera text.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Konturera text och lägg till i sökväg för klippning.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### valueOf {#valueOf-java.lang.String-}
Returnerar enum‑konstanten av denna typ med det angivna namnet.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Returnerar en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras.

**Returns:**
en array som innehåller konstanterna för denna enum‑typ, i den ordning de deklareras
