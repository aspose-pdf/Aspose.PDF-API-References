---
title: "TextState"
linktitle: "TextState"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett texttillstånd för en text"
type: docs
weight: 5340
url: /sv/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Representerar ett texttillstånd för en text

## Fält

| Fält | Beskrivning |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Standardvärde för tabulering i bredden på mellanslagstecknet för standardtypsnittet. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextState](#TextState--) | Skapar texttillståndsobjekt. |
| [TextState](#TextState-java.awt.Color-) | Skapar texttillståndsobjekt. |
| [TextState](#TextState-java.awt.Color-double-) | Skapar texttillståndsobjekt. |
| [TextState](#TextState-double-) | Skapar texttillståndsobjekt med specifikation av teckenstorlek. |
| [TextState](#TextState-java.lang.String-) | Skapar texttillståndsobjekt. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Skapar texttillståndsobjekt. |
| [TextState](#TextState-java.lang.String-double-) | Skapar texttillståndsobjekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Tillämpar inställningar från ett annat textState </p> <hr> <p> Endast de egenskaper som ändrats explicit kommer att kopieras. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Beräknar teckenstorleken för rektangeln. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Hämtar bakgrundsfärgen för texten. </p> <hr> <p> Observera att värdet inte bevaras som en textegenskap i dokumentet. BackgroundColor‑egenskaps‑getter fungerar för ett objekt om det tidigare explicit satts med BackgroundColor‑setter för det objektet. Egenskapen används av körtiden i samband med den aktuella genererings‑/modifieringsprocessen. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Hämtar teckenavståndet för texten. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| [getFont](#getFont--) | Hämtar teckensnittet för texten. |
| [getfontSize](#getfontSize--) | Representerar getfontSize‑metoden |
| [getFontSize](#getFontSize--) | Hämtar teckenstorleken för texten. |
| [getFontStyle](#getFontStyle--) | Anger teckensnittsstilen för texten. |
| [getForegroundColor](#getForegroundColor--) | Hämtar förgrundsfärg för texten. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Hämtar horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextState.HorizontalAlignment‑egenskapen endast fungerar i scenarier för ny dokumentgenerering. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Hämtar horisontell skalning för texten. |
| [getLineSpacing](#getLineSpacing--) | <p> Hämtar radavstånd för texten. </p> |
| [getRenderingMode](#getRenderingMode--) | Hämtar eller anger renderingsläge för texten. |
| [getStrokingColor](#getStrokingColor--) | Hämtar eller anger förgrundsfärg för texten. |
| [getTabTag](#getTabTag--) | <p> Du kan placera den här taggen i texten för att deklarera tabulering. </p> <hr> <p> Den har effekt endast i kombination med {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Hämtar texthöjd. |
| [getWordSpacing](#getWordSpacing--) | Hämtar ordavstånd för texten. |
| [isInvisible](#isInvisible--) | Hämtar textens osynlighet. Detta speglar i princip {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})‑tillståndet, förutom i vissa specialfall (t.ex. beskärning). |
| [isStrikeOut](#isStrikeOut--) | Hämtar genomstrykning för texten, representerad av {@code TextFragment}-objektet |
| [isSubscript](#isSubscript--) | Hämtar eller anger nedsänkt text (subscript). |
| [isSuperscript](#isSuperscript--) | Hämtar upphöjd text (superscript). |
| [isUnderline](#isUnderline--) | Hämtar understrykning för texten, representerad av {@code TextFragment}-objektet |
| [measureHeight](#measureHeight-char-) | Mäter teckenhöjd. |
| [measureString](#measureString-java.lang.String-) | Mäter strängen. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Mäter strängen. </p> <hr> <p> insideLine indikerar att strängen inte avslutas. Om en del av hela strängen mäts – bör insideLine vara true. Om hela strängen mäts – bör insideLine vara false. Med andra ord: när insideLine = true tas endast teckenbredd in i beräkningen. Inga ytterligare transformationer tas med när insideLine = false. Strängens slut hanteras korrekt – kursiv transformation tas med. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Anger bakgrundsfärg för texten. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Anger teckenavstånd för texten. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Hämtar teckensnittet för texten. |
| [setFontSize](#setFontSize-float-) | Anger teckenstorlek för texten. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Anger teckenstorlek för texten med undertryckt uppdatering. |
| [setFontStyle](#setFontStyle-int-) | Anger teckensnittsstilen för texten. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Hämtar teckensnitt för texten med undertryckt uppdatering. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Anger förgrundsfärg för texten. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Anger horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextState.HorizontalAlignment‑egenskapen endast fungerar i scenarier för ny dokumentgenerering. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Anger horisontell skalning för texten. |
| [setInvisible](#setInvisible-boolean-) | Ställer in textens osynlighet. Detta speglar i princip {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})‑tillståndet, förutom i vissa speciella fall (som beskärning). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Ställer in radavståndet för texten. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Hämtar eller anger renderingsläge för texten. |
| [setStrikeOut](#setStrikeOut-boolean-) | Ställer in genomstrykning för texten, representerad av {@code TextFragment}-objektet |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Hämtar eller anger förgrundsfärg för texten. |
| [setSubscript](#setSubscript-boolean-) | Hämtar eller anger nedsänkt text (subscript). |
| [setSuperscript](#setSuperscript-boolean-) | Ställer in upphöjd text. |
| [setUnderline](#setUnderline-boolean-) | Ställer in understrykning för texten, representerad av {@code TextFragment}-objektet |
| [setWordSpacing](#setWordSpacing-float-) | Ställer in ordavstånd för texten. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Standardvärde för tabulering i bredden på mellanslagstecknet för standardtypsnittet.

### TextState {#TextState--}
```
public TextState()
```

Skapar texttillståndsobjekt.

### TextState {#TextState-java.awt.Color-}
Skapar texttillståndsobjekt.

### TextState {#TextState-java.awt.Color-double-}
Skapar texttillståndsobjekt.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Skapar texttillståndsobjekt med specifikation av teckenstorlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSize |  | Teckenstorlek. |

### TextState {#TextState-java.lang.String-}
Skapar texttillståndsobjekt.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Skapar texttillståndsobjekt.

### TextState {#TextState-java.lang.String-double-}
Skapar texttillståndsobjekt.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Tillämpar inställningar från ett annat textState </p> <hr> <p> Endast de egenskaper som ändrats explicit kommer att kopieras. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Beräknar teckenstorleken för rektangeln.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Hämtar bakgrundsfärgen för texten. </p> <hr> <p> Observera att värdet inte bevaras som en textegenskap i dokumentet. BackgroundColor‑egenskaps‑getter fungerar för ett objekt om det tidigare explicit satts med BackgroundColor‑setter för det objektet. Egenskapen används av körtiden i samband med den aktuella genererings‑/modifieringsprocessen. </p>

**Returns:**
Färgvärde

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Hämtar teckenavståndet för texten.

**Returns:**
flyttalsvärde

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering.

**Returns:**
CoordinateOrigin‑element

### getFont {#getFont--}
```
public Font getFont()
```

Hämtar teckensnittet för texten.

**Returns:**
Font‑objekt

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Representerar getfontSize‑metoden

**Returns:**
flyttalsvärde

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Hämtar teckenstorleken för texten.

**Returns:**
flyttalsvärde

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Anger teckensnittsstilen för texten.

**Returns:**
FontStyles‑element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Hämtar förgrundsfärg för texten.

**Returns:**
Färgvärde

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Hämtar horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextState.HorizontalAlignment‑egenskapen endast fungerar i scenarier för ny dokumentgenerering. </p>

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Hämtar horisontell skalning för texten.

**Returns:**
flyttalsvärde

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Hämtar radavstånd för texten. </p>

**Returns:**
flyttalsvärde <hr> <p> Observera att värdet inte bevaras som en textegenskap i dokumentet. LineSpacing‑egenskaps‑getter fungerar för ett objekt om det tidigare explicit har satts med LineSpacing‑setter för det objektet. Egenskapen används av körtiden i sammanhanget för den aktuella genererings-/modifieringsprocessen. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Hämtar eller anger renderingsläge för texten.

**Returns:**
TextRenderingMode‑element @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Hämtar eller anger förgrundsfärg för texten.

**Returns:**
Color-instans

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Du kan placera den här taggen i texten för att deklarera tabulering. </p> <hr> <p> Den har effekt endast i kombination med {@code TabStops}. </p>

**Returns:**
Strängvärde "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Hämtar texthöjd.

**Returns:**
flyttalsvärde

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Hämtar ordavstånd för texten.

**Returns:**
flyttalsvärde

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Hämtar textens osynlighet. Detta speglar i princip {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})‑tillståndet, förutom i vissa specialfall (t.ex. beskärning).

**Returns:**
booleskt värde

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Hämtar genomstrykning för texten, representerad av {@code TextFragment}-objektet

**Returns:**
booleskt värde

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Hämtar eller anger nedsänkt text (subscript).

**Returns:**
booleskt värde

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Hämtar upphöjd text (superscript).

**Returns:**
booleskt värde

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Hämtar understrykning för texten, representerad av {@code TextFragment}-objektet

**Returns:**
booleskt värde

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Mäter teckenhöjd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| tecken |  | Tecken att mäta. |

**Returns:**
Höjd på tecknet om vi kan hämta det från teckensnittet; annars 0.

### measureString {#measureString-java.lang.String-}
Mäter strängen.

### measureString {#measureString-java.lang.String-boolean-}
<p> Mäter strängen. </p> <hr> <p> insideLine indikerar att strängen inte avslutas. Om en del av hela strängen mäts – bör insideLine vara true. Om hela strängen mäts – bör insideLine vara false. Med andra ord: när insideLine = true tas endast teckenbredd in i beräkningen. Inga ytterligare transformationer tas med när insideLine = false. Strängens slut hanteras korrekt – kursiv transformation tas med. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Anger bakgrundsfärg för texten.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Anger teckenavstånd för texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering.

### setFont {#setFont-com.aspose.pdf.Font-}
Hämtar teckensnittet för texten.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Anger teckenstorlek för texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Anger teckenstorlek för texten med undertryckt uppdatering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Anger teckensnittsstilen för texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | FontStyles‑värde @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Hämtar teckensnitt för texten med undertryckt uppdatering.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Anger förgrundsfärg för texten.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Anger horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextState.HorizontalAlignment‑egenskapen endast fungerar i scenarier för ny dokumentgenerering. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Anger horisontell skalning för texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Ställer in textens osynlighet. Detta speglar i princip {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})‑tillståndet, förutom i vissa speciella fall (som beskärning).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Ställer in radavståndet för texten. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde <hr> <p> Observera att värdet inte bevaras som en textegenskap i dokumentet. LineSpacing‑egenskaps‑getter fungerar för ett objekt om det tidigare explicit har satts med LineSpacing‑setter för det objektet. Egenskapen används av körtiden i sammanhanget för den aktuella genererings-/modifieringsprocessen. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Hämtar eller anger renderingsläge för texten.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Ställer in genomstrykning för texten, representerad av {@code TextFragment}-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Hämtar eller anger förgrundsfärg för texten.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Hämtar eller anger nedsänkt text (subscript).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Ställer in upphöjd text.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Ställer in understrykning för texten, representerad av {@code TextFragment}-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Ställer in ordavstånd för texten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |
