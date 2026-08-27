---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett texttillstånd för ett textfragment. </p> <hr> <pre> Exemplet visar hur man ändrar textfärg och teckenstorlek för texten med {@code TextState} objektet. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Tillhandahåller ett sätt att ändra följande egenskaper för texten: teckensnitt ({@code TextFragmentState.Font} property) teckenstorlek ({@code TextFragmentState.FontSize} property) teckenstil ({@code TextFragmentState.FontStyle} property) förgrundsfärg ({@code TextFragmentState.ForegroundColor} property) bakgrundsfärg ({@code TextFragmentState.BackgroundColor} property) </p> <p> Observera att ändring av {@code TextFragmentState}-egenskaper kan ändra den inre {@code TextFragment.Segments}-samlingen eftersom TextFragment är ett aggregatobjekt och kan omarrangera interna segment eller slå ihop dem till ett enda segment. Om ditt krav är att låta {@code TextFragment.Segments}-samlingen förbli oförändrad, ändra de interna segmenten individuellt. </p> @see TextFragmentAbsorber @see IDocument"
type: docs
weight: 5150
url: /sv/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
Initierar en ny instans av {@code TextFragmentState}-objektet med angivet {@code TextFragment}-objekt. Denna {@code TextFragmentState}-initialisering stöds inte. TextFragmentState är endast tillgänglig med {@code TextFragment.TextState}-egenskapen.

```
public final class TextFragmentState extends TextState
```

<p> Tillämpar inställningar från ett annat textState </p>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Tillämpar inställningar från ett annat textState |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | Anger bakgrundsfärg för texten, representerad av {@code TextFragment}-objektet |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Tillämpar inställningar från en annan textState |
| [getBackgroundColor](#getBackgroundColor--) | Ställer in bakgrundsfärg för texten, representerad av {@code TextFragment} objektet |
| [getCharacterSpacing](#getCharacterSpacing--) | Hämtar teckenavståndet för texten, representerat av {@code TextFragment}-objektet. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Hämtar om flaggan för att rita textrutans kant är satt. |
| [getFont](#getFont--) | Hämtar teckensnittet för texten, representerat av {@code TextFragment}-objektet |
| [getFontSize](#getFontSize--) | Hämtar teckenstorleken för texten, representerat av {@code TextFragment}-objektet |
| [getFontStyle](#getFontStyle--) | Ställer in teckensnittsstilen för texten, representerat av {@code TextFragment}-objektet |
| [getForegroundColor](#getForegroundColor--) | Hämtar förgrundsfärgen för texten, representerat av {@code TextFragment}-objektet |
| [getFormattingOptions](#getFormattingOptions--) | Hämtar eller anger formateringsalternativ. Inställning av alternativen är endast effektiv i generator‑scenarier. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Hämtar horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att egenskapen TextFragmentState.VerticalAlignment endast fungerar i nya dokumentgenereringsscenarier. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Hämtar horisontell skalning av texten, representerat av {@code TextFragment}-objektet. |
| [getLineSpacing](#getLineSpacing--) | <p> Hämtar radavstånd för texten. </p> |
| [getRenderingMode](#getRenderingMode--) | Hämtar eller anger renderingsläge för texten. |
| [getRotation](#getRotation--) | Hämtar eller anger rotationsvinkel i grader. |
| [getStrokingColor](#getStrokingColor--) | Hämtar eller anger färgstrokoperationer för {@code TextFragment}-rendering (strecka text, textrutans kant) |
| [getTabStops](#getTabStops--) | <p> Hämtar tabbstopp för texten. </p> <hr> <p> Observera att Tabstops‑egenskapen endast fungerar i nya dokumentgenereringsscenarier. Tabstops kan läggas till under {@code TextFragment}-initialisering. Tabstops måste konstrueras före texten. </p> |
| [getTextHeight](#getTextHeight--) | Hämtar texthöjden, representerat av {@code TextFragment}-objektet |
| [getWordSpacing](#getWordSpacing--) | Hämtar ordavstånd för texten. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Kontrollerar om inmatningssträngen kan placeras inom den definierade rektangeln. |
| [isInvisible](#isInvisible--) | Hämtar textens osynlighet. |
| [isStrikeOut](#isStrikeOut--) | Hämtar eller anger genomstrykning för texten, representerat av {@link TextFragment}-objektet |
| [isSubscript](#isSubscript--) | Hämtar eller anger nedsänkt text för texten, representerat av {@code TextFragment}-objektet. |
| [isSuperscript](#isSuperscript--) | Hämtar eller anger upphöjd text för texten, representerat av {@code TextFragment}-objektet. |
| [isUnderline](#isUnderline--) | Hämtar eller anger understrykning för texten, representerat av {@link TextFragment}-objektet |
| [measureHeight](#measureHeight-char-) | Mäter teckenhöjd. |
| [measureString](#measureString-java.lang.String-) | Mäter strängen. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ställer in bakgrundsfärgen för texten, representerat av TextFragment-objektet |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Ställer in teckenavståndet för texten, representerat av {@code TextFragment}-objektet. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Ställer in om flaggan för att rita textrutans kant är satt. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Ställer in teckensnittet för texten, representerat av {@code TextFragment}-objektet |
| [setFontSize](#setFontSize-float-) | Ställer in teckenstorleken för texten, representerat av {@code TextFragment}-objektet |
| [setFontStyle](#setFontStyle-int-) | Ställer in teckensnittsstilen för texten, representerat av {@link TextFragment}-objektet |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Ställer in förgrundsfärgen för texten, representerad av {@code TextFragment}-objektet |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Hämtar eller anger formateringsalternativ. Inställning av alternativen är endast effektiv i generator‑scenarier. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Ställer in horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextFragmentState.VerticalAlignment‑egenskapen fungerar endast i scenarier för ny dokumentgenerering. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Ställer in horisontell skalning av texten, representerad av {@code TextFragment}-objektet. |
| [setInvisible](#setInvisible-boolean-) | Ställer in textens osynlighet. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Ställer in radavståndet för texten. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Hämtar eller anger renderingsläge för texten. |
| [setRotation](#setRotation-double-) | Hämtar eller anger rotationsvinkel i grader. |
| [setStrikeOut](#setStrikeOut-boolean-) | Ställer in genomstrykning för texten, representerad av {@code TextFragment}-objektet |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Hämtar eller anger färgstrokoperationer för {@code TextFragment}-rendering (strecka text, textrutans kant) |
| [setSubscript](#setSubscript-boolean-) | Hämtar eller anger nedsänkt text för texten, representerat av {@code TextFragment}-objektet. |
| [setSuperscript](#setSuperscript-boolean-) | Hämtar eller anger upphöjd text för texten, representerat av {@code TextFragment}-objektet. |
| [setUnderline](#setUnderline-boolean-) | Ställer in understrykning för texten, representerad av {@code TextFragment}-objektet |
| [setWordSpacing](#setWordSpacing-float-) | Ställer in ordavstånd för texten. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Tillämpar inställningar från ett annat textState

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
Anger bakgrundsfärg för texten, representerad av {@code TextFragment}-objektet

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Tillämpar inställningar från en annan textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Ställer in bakgrundsfärg för texten, representerad av {@code TextFragment} objektet

**Returns:**
värde Color-objekt

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Hämtar teckenavståndet för texten, representerat av {@code TextFragment}-objektet.

**Returns:**
flyttalsvärde

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering.

**Returns:**
CoordinateOrigin‑element

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Hämtar om flaggan för att rita textrutans kant är satt.

**Returns:**
booleskt värde

### getFont {#getFont--}
```
public Font getFont()
```

Hämtar teckensnittet för texten, representerat av {@code TextFragment}-objektet

**Returns:**
Teckensnittsvärde

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Hämtar teckenstorleken för texten, representerat av {@code TextFragment}-objektet

**Returns:**
flyttalsvärde

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Ställer in teckensnittsstilen för texten, representerat av {@code TextFragment}-objektet

**Returns:**
FontStyles‑element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Hämtar förgrundsfärgen för texten, representerat av {@code TextFragment}-objektet

**Returns:**
Color‑objekt

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Hämtar eller anger formateringsalternativ. Inställning av alternativen är endast effektiv i generator‑scenarier.

**Returns:**
TextFormattingOptions‑instans

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Hämtar horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att egenskapen TextFragmentState.VerticalAlignment endast fungerar i nya dokumentgenereringsscenarier. </p>

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Hämtar horisontell skalning av texten, representerat av {@code TextFragment}-objektet.

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
TextRenderingMode‑element

### getRotation {#getRotation--}
```
public double getRotation()
```

Hämtar eller anger rotationsvinkel i grader.

**Returns:**
double-värde

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Hämtar eller anger färgstrokoperationer för {@code TextFragment}-rendering (strecka text, textrutans kant)

**Returns:**
Color-instans

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Hämtar tabbstopp för texten. </p> <hr> <p> Observera att Tabstops‑egenskapen endast fungerar i nya dokumentgenereringsscenarier. Tabstops kan läggas till under {@code TextFragment}-initialisering. Tabstops måste konstrueras före texten. </p>

**Returns:**
TabStops‑objekt

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Hämtar texthöjden, representerat av {@code TextFragment}-objektet

**Returns:**
flyttalsvärde

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Hämtar ordavstånd för texten.

**Returns:**
flyttalsvärde

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Kontrollerar om inmatningssträngen kan placeras inom den definierade rektangeln.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Hämtar textens osynlighet.

**Returns:**
booleskt värde

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Hämtar eller anger genomstrykning för texten, representerat av {@link TextFragment}-objektet

**Returns:**
booleskt värde

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Hämtar eller anger nedsänkt text för texten, representerat av {@code TextFragment}-objektet.

**Returns:**
booleskt värde

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Hämtar eller anger upphöjd text för texten, representerat av {@code TextFragment}-objektet.

**Returns:**
värde boolean‑värde

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Hämtar eller anger understrykning för texten, representerat av {@link TextFragment}-objektet

**Returns:**
booleskt värde

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ställer in bakgrundsfärgen för texten, representerat av TextFragment-objektet

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Ställer in teckenavståndet för texten, representerat av {@code TextFragment}-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Hämtar eller anger textens CoordinateOrigin. Om CoordinateOrigin är Descender motsvarar textens Y‑koordinat tecknets lägsta punkt. Om CoordinateOrigin är BaseLine motsvarar textens Y‑koordinat tecknets baslinje. Standardvärdet är Descender. Om tecknets Descent‑värde är för stort kan texten renderas högre än andra teckensnitt. I så fall kan CoordinateOrigin BaseLine väljas för bättre textrendering.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Ställer in om flaggan för att rita textrutans kant är satt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setFont {#setFont-com.aspose.pdf.Font-}
Ställer in teckensnittet för texten, representerat av {@code TextFragment}-objektet

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Ställer in teckenstorleken för texten, representerat av {@code TextFragment}-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Ställer in teckensnittsstilen för texten, representerat av {@link TextFragment}-objektet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Ställer in förgrundsfärgen för texten, representerad av {@code TextFragment}-objektet

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Hämtar eller anger formateringsalternativ. Inställning av alternativen är endast effektiv i generator‑scenarier.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Ställer in horisontell justering för texten. </p> <hr> <p> HorizontalAlignment.None är lika med HorizontalAlignment.Left. Observera att TextFragmentState.VerticalAlignment‑egenskapen fungerar endast i scenarier för ny dokumentgenerering. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Ställer in horisontell skalning av texten, representerad av {@code TextFragment}-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Ställer in textens osynlighet.

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

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Hämtar eller anger rotationsvinkel i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

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
Hämtar eller anger färgstrokoperationer för {@code TextFragment}-rendering (strecka text, textrutans kant)

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Hämtar eller anger nedsänkt text för texten, representerat av {@code TextFragment}-objektet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Hämtar eller anger upphöjd text för texten, representerat av {@code TextFragment}-objektet.

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
