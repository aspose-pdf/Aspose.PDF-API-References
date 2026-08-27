---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar textparagrafer som ett flerradigt textobjekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan. Document doc."
type: docs
weight: 5200
url: /sv/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Representerar textparagrafer som ett flerradigt textobjekt. </p> <hr> <pre> Exemplet visar hur man skapar ett textparagrafobjekt och lägger till det på Pdf-sidan. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // skapa textparagraf TextParagraph paragraph = new TextParagraph(); // sätt paragrafens rektangel paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // sätt ordbrytningsalternativ paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // lägg till strängrader paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // lägg till paragrafen på Pdf-sidan med TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // spara Pdf-dokument doc.save(outFile); </pre>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Skapar {@code TextParagraph} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Lägger till textrad |
| [appendLine](#appendLine-java.lang.String-float-) | Lägger till textrad. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Lägger till textrad med texttillståndsparametrar. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Lägger till textrad med texttillståndsparametrar |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Lägger till textrad med texttillståndsparametrar. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Lägger till textrad med texttillståndsparametrar. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Lägger till textrad med texttillståndsparametrar |
| [beginEdit](#beginEdit--) | Påbörjar redigeringen av TextParagraph. <p> Förbättrar prestanda för TextParagraph‑befolkning. Alla layoutberäkningar är suspenderade tills EndEdit‑metoden anropas. <p> Observera att metodanropet inte kan vara nästlat. </p> |
| [endEdit](#endEdit--) | Avslutar redigeringen av TextParagraph. <p> Förbättrar prestanda för TextParagraph‑befolkning. Alla layoutberäkningar är suspenderade tills EndEdit‑metoden anropas. <p> Observera att metodanropet inte kan vara nästlat. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Hämtar eller anger indenteringsvärde för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med FormattingOptions.SubsequentLinesIndent‑värdet. |
| [getFormattingOptions](#getFormattingOptions--) | Hämtar formateringsalternativ. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar horisontell justering för texten i paragrafens Rectangle. HorizontalAlignment.None är lika med HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Hämtar bindestreckssymbolen som används i avstavningsprocessen. Avstavningssymbolen är "-" som standard. För att eliminera bindestrecksritning (med omslagproceduren fortfarande aktiv) vänligen sätt en tom sträng string.Empty för HyphenSymbol. |
| [getMargin](#getMargin--) | Hämtar utfyllnaden. |
| [getPosition](#getPosition--) | Hämtar positionen för paragrafen. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för paragrafen. |
| [getRotation](#getRotation--) | Hämtar eller anger rotationsvinkel i grader. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Hämtar indenteringsvärde för efterföljande rader. |
| [getTextRectangle](#getTextRectangle--) | Hämtar rektangeln för texten placerad i paragrafen. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Hämtar vertikal justering för texten i paragrafens {@code Rectangle}. </p> |
| [isJustify](#isJustify--) | Hämtar värdet om texten är justerad. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ställer in bakgrundsfärg för textstycket. |
| [setBackgroundMode](#setBackgroundMode-int-) | Ställ in bakgrundsläge för textstycket |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Hämtar eller anger indenteringsvärde för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med FormattingOptions.SubsequentLinesIndent‑värdet. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Ställer in formateringsalternativ. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in horisontell justering för texten i styckets Rectangle. HorizontalAlignment.None är lika med HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Ställer in bindestreckssymbolen som används i avstavningsprocessen. Avstavningssymbolen är "-" som standard. För att eliminera bindestrecksteckning (med radbrytningsproceduren fortfarande aktiv) vänligen ställ in en tom sträng string.Empty för HyphenSymbol. |
| [setJustify](#setJustify-boolean-) | Ställer in värdet för om texten är justerad. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Ställer in utfyllnaden. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Ställer in rotationen för stycket. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Ställ in kompatibilitetsläge för gammal kod |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Ställer in positionen för stycket. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Ställer in rektangeln för stycket. |
| [setRotation](#setRotation-double-) | Hämtar eller anger rotationsvinkel i grader. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Ställer in indragsvärdet för efterföljande rader. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ställer in vertikal justering för texten i styckets {@code Rectangle}. VerticalAlignment.None är lika med VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Skapar {@code TextParagraph} objekt.

### appendLine {#appendLine-java.lang.String-}
Lägger till textrad

### appendLine {#appendLine-java.lang.String-float-}
Lägger till textrad.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Lägger till textrad med texttillståndsparametrar.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Lägger till textrad med texttillståndsparametrar

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Lägger till textrad med texttillståndsparametrar.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Lägger till textrad med texttillståndsparametrar.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Lägger till textrad med texttillståndsparametrar

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Påbörjar redigeringen av TextParagraph. <p> Förbättrar prestanda för TextParagraph‑befolkning. Alla layoutberäkningar är suspenderade tills EndEdit‑metoden anropas. <p> Observera att metodanropet inte kan vara nästlat. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Avslutar redigeringen av TextParagraph. <p> Förbättrar prestanda för TextParagraph‑befolkning. Alla layoutberäkningar är suspenderade tills EndEdit‑metoden anropas. <p> Observera att metodanropet inte kan vara nästlat. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Hämtar eller anger indenteringsvärde för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med FormattingOptions.SubsequentLinesIndent‑värdet.

**Returns:**
flyttalsvärde

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Hämtar formateringsalternativ.

**Returns:**
TextFormattingOptions-objekt

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar horisontell justering för texten i paragrafens Rectangle. HorizontalAlignment.None är lika med HorizontalAlignment.Left.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Hämtar bindestreckssymbolen som används i avstavningsprocessen. Avstavningssymbolen är "-" som standard. För att eliminera bindestrecksritning (med omslagproceduren fortfarande aktiv) vänligen sätt en tom sträng string.Empty för HyphenSymbol.

**Returns:**
String värde

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Hämtar utfyllnaden.

**Returns:**
MarginInfo‑värde

### getPosition {#getPosition--}
```
public Position getPosition()
```

Hämtar positionen för paragrafen.

**Returns:**
Positionsvärde

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln för paragrafen.

**Returns:**
Rectangle‑objekt

### getRotation {#getRotation--}
```
public double getRotation()
```

Hämtar eller anger rotationsvinkel i grader.

**Returns:**
double-värde

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Hämtar indenteringsvärde för efterföljande rader.

**Returns:**
flyttalsvärde

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Hämtar rektangeln för texten placerad i paragrafen.

**Returns:**
Rectangle‑objekt

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Hämtar vertikal justering för texten i paragrafens {@code Rectangle}. </p>

**Returns:**
VerticalAlignment-värde @see VerticalAlignment <hr> <p> VerticalAlignment.None är lika med VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Hämtar värdet om texten är justerad.

**Returns:**
booleskt värde

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ställer in bakgrundsfärg för textstycket.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Ställ in bakgrundsläge för textstycket

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int-värde @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Hämtar eller anger indenteringsvärde för efterföljande rader. Om det sätts till ett icke‑nollvärde har det en fördel jämfört med FormattingOptions.SubsequentLinesIndent‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Ställer in formateringsalternativ.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in horisontell justering för texten i styckets Rectangle. HorizontalAlignment.None är lika med HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Ställer in bindestreckssymbolen som används i avstavningsprocessen. Avstavningssymbolen är "-" som standard. För att eliminera bindestrecksteckning (med radbrytningsproceduren fortfarande aktiv) vänligen ställ in en tom sträng string.Empty för HyphenSymbol.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Ställer in värdet för om texten är justerad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Ställer in utfyllnaden.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Ställer in rotationen för stycket.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Ställ in kompatibilitetsläge för gammal kod

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Ställer in positionen för stycket.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Ställer in rektangeln för stycket.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Hämtar eller anger rotationsvinkel i grader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Ställer in indragsvärdet för efterföljande rader.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ställer in vertikal justering för texten i styckets {@code Rectangle}. VerticalAlignment.None är lika med VerticalAlignment.Bottom.
