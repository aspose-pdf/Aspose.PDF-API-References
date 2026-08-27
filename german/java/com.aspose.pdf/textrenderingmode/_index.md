---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Der Textdarstellungsmodus, Tmode, bestimmt, ob das Anzeigen von Text dazu führt, dass Glyphenkonturen gestrichelt, gefüllt, als Beschneidungsgrenze verwendet werden oder eine Kombination dieser drei Optionen."
type: docs
weight: 5240
url: /de/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

Der Textdarstellungsmodus, Tmode, bestimmt, ob das Anzeigen von Text dazu führt, dass Glyphenkonturen gestrichelt, gefüllt, als Beschneidungsgrenze verwendet werden oder eine Kombination dieser drei Optionen.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Text zum Pfad hinzufügen zum Ausschneiden. |
| [FillText](#FillText) | Text füllen. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Text füllen und zum Pfad hinzufügen zum Ausschneiden (siehe 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Füllen, dann Text nachziehen. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Füllen, dann Text nachziehen und zum Pfad hinzufügen zum Ausschneiden. |
| [Invisible](#Invisible) | Weder füllen noch Text nachziehen (unsichtbar). |
| [StrokeText](#StrokeText) | Text nachziehen. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Text nachziehen und zum Pfad hinzufügen zum Ausschneiden. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück. |
| [values](#values--) | Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Text zum Pfad hinzufügen zum Ausschneiden.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Text füllen.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Text füllen und zum Pfad hinzufügen zum Ausschneiden (siehe 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Füllen, dann Text nachziehen.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Füllen, dann Text nachziehen und zum Pfad hinzufügen zum Ausschneiden.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Weder füllen noch Text nachziehen (unsichtbar).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Text nachziehen.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Text nachziehen und zum Pfad hinzufügen zum Ausschneiden.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### valueOf {#valueOf-java.lang.String-}
Gibt die Enum-Konstante dieses Typs mit dem angegebenen Namen zurück.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Gibt ein Array zurück, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält.

**Returns:**
ein Array, das die Konstanten dieses Enum-Typs in der Reihenfolge ihrer Deklaration enthält
