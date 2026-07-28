---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för textformatering"
type: docs
weight: 5080
url: /sv/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Representerar alternativ för textformatering

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Initierar en ny instans av {@code TextFormattingOptions}-objektet med odefinierat radbrytningsläge. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Initierar en ny instans av {@code TextFormattingOptions}-objektet för det angivna radbrytningsläget. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Hämtar eller anger värde för indrag på första raden. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Hämtar eller anger bindestreckssymbol som används i avstavningsprocessen. </p><hr> För att eliminera bindestrecksritning (med radbrytningsprocedur fortfarande aktiv) vänligen ange en tom sträng string.Empty för HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Hämtar radavståndsläge. Standardvärdet är LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Hämtar eller anger indrag för efterföljande rader. |
| [getWrapMode](#getWrapMode--) | Hämtar radbrytningsläge. Standardvärdet är WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Hämtar eller anger värde för indrag på första raden. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Hämtar eller anger bindestreckssymbol som används i avstavningsprocessen. </p><hr> För att eliminera bindestrecksritning (med radbrytningsprocedur fortfarande aktiv) vänligen ange en tom sträng string.Empty för HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Ställer in radavståndsläge. Standardvärdet är LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Hämtar eller anger indrag för efterföljande rader. |
| [setWrapMode](#setWrapMode-int-) | Ställer in radbrytningsläge. Standardvärdet är WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Initierar en ny instans av {@code TextFormattingOptions}-objektet med odefinierat radbrytningsläge.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Initierar en ny instans av {@code TextFormattingOptions}-objektet för det angivna radbrytningsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| wrapMode |  | Radbrytningsläge. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Hämtar eller anger värde för indrag på första raden.

**Returns:**
flyttalsvärde

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Hämtar eller anger bindestreckssymbol som används i avstavningsprocessen. </p><hr> För att eliminera bindestrecksritning (med radbrytningsprocedur fortfarande aktiv) vänligen ange en tom sträng string.Empty för HyphenSymbol.

**Returns:**
String värde

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Hämtar radavståndsläge. Standardvärdet är LineSpacingMode.FontSize

**Returns:**
int‑värde @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Hämtar eller anger indrag för efterföljande rader.

**Returns:**
flyttalsvärde

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Hämtar radbrytningsläge. Standardvärdet är WordWrapMode.NoWrap

**Returns:**
WordWrapMode värde @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Hämtar eller anger värde för indrag på första raden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Hämtar eller anger bindestreckssymbol som används i avstavningsprocessen. </p><hr> För att eliminera bindestrecksritning (med radbrytningsprocedur fortfarande aktiv) vänligen ange en tom sträng string.Empty för HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Ställer in radavståndsläge. Standardvärdet är LineSpacingMode.FontSize

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Hämtar eller anger indrag för efterföljande rader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Ställer in radbrytningsläge. Standardvärdet är WordWrapMode.NoWrap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | WordWrapMode värde @see WordWrapMode |
