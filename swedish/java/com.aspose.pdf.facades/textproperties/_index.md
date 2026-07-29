---
title: "TextProperties"
linktitle: "TextProperties"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar textegenskaper såsom: textstorlek, färg, stil osv."
type: docs
weight: 740
url: /sv/java/com.aspose.pdf.facades/textproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.TextProperties

```
public final class TextProperties extends Object
```

Representerar textegenskaper såsom: textstorlek, färg, stil osv.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextProperties](#TextProperties-double-) | Skapar {@code TextProperties}-objekt för den angivna textstorleken |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor](#getColor--) | Hämtar textfärg. |
| [getTextSize](#getTextSize--) | Hämtar textstorlek. |
| [isColorSpecified](#isColorSpecified--) | Hämtar ett värde som indikerar om egenskapen {@code Color} är specificerad. |
| [isTextSizeSpecified](#isTextSizeSpecified--) | Hämtar ett värde som indikerar om egenskapen {@code TextSize} är specificerad. |
| [setColor](#setColor-java.awt.Color-) | Ställer in textfärg. |
| [setTextSize](#setTextSize-double-) | Ställer in textstorlek. |

### TextProperties {#TextProperties-double-}
```
public TextProperties(double textSize)
```

Skapar {@code TextProperties}-objekt för den angivna textstorleken

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textSize |  | Värde för textstorlek. |

### getColor {#getColor--}
```
public Color getColor()
```

Hämtar textfärg.

**Returns:**
Color‑objekt

### getTextSize {#getTextSize--}
```
public double getTextSize()
```

Hämtar textstorlek.

**Returns:**
double-värde

### isColorSpecified {#isColorSpecified--}
```
public boolean isColorSpecified()
```

Hämtar ett värde som indikerar om egenskapen {@code Color} är specificerad.

**Returns:**
booleskt värde

### isTextSizeSpecified {#isTextSizeSpecified--}
```
public boolean isTextSizeSpecified()
```

Hämtar ett värde som indikerar om egenskapen {@code TextSize} är specificerad.

**Returns:**
booleskt värde

### setColor {#setColor-java.awt.Color-}
Ställer in textfärg.

### setTextSize {#setTextSize-double-}
```
public void setTextSize(double value)
```

Ställer in textstorlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
