---
title: "TextParagraph"
linktitle: "TextParagraph"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt Textabsätze als mehrzeiliges Textobjekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man ein TextParagraph‑Objekt erstellt und es an die PDF‑Seite anhängt. Document doc."
type: docs
weight: 5200
url: /de/java/com.aspose.pdf/textparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextParagraph

```
public final class TextParagraph extends Object
```

<p> Stellt Textabsätze als mehrzeiliges Textobjekt dar. </p> <hr> <pre> Das Beispiel zeigt, wie man ein Textabsatz-Objekt erstellt und es an die PDF-Seite anhängt. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // create text paragraph TextParagraph paragraph = new TextParagraph(); // set the paragraph rectangle paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // set word wrapping options paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // append string lines paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // append the paragraph to the Pdf page with the TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // save Pdf document doc.save(outFile); </pre>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextParagraph](#TextParagraph--) | Erstellt {@code TextParagraph} Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendLine](#appendLine-java.lang.String-) | Fügt Textzeile hinzu |
| [appendLine](#appendLine-java.lang.String-float-) | Fügt Textzeile hinzu. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-) | Fügt Textzeile mit Textzustands‑Parametern hinzu. |
| [appendLine](#appendLine-java.lang.String-com.aspose.pdf.TextState-float-) | Fügt Textzeile mit Textzustands‑Parametern hinzu |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-) | Fügt Textzeile mit Textzustands‑Parametern hinzu. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-) | Fügt Textzeile mit Textzustands‑Parametern hinzu. |
| [appendLine](#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-) | Fügt Textzeile mit Textzustands‑Parametern hinzu |
| [beginEdit](#beginEdit--) | Beginnt die Bearbeitung des TextParagraph. <p> Verbessert die Leistung der TextParagraph‑Population. Jede Layout‑Berechnung wird ausgesetzt, bis die EndEdit‑Methode aufgerufen wird. <p> Hinweis: Der Methodenaufruf kann nicht geschachtelt werden. </p> |
| [endEdit](#endEdit--) | Beendet die Bearbeitung des TextParagraph. <p> Verbessert die Leistung der TextParagraph‑Population. Jede Layout‑Berechnung wird ausgesetzt, bis die EndEdit‑Methode aufgerufen wird. <p> Hinweis: Der Methodenaufruf kann nicht geschachtelt werden. </p> |
| [getFirstLineIndent](#getFirstLineIndent--) | Liest oder setzt den Einzugswert für nachfolgende Zeilen. Wenn ein von Null verschiedener Wert gesetzt wird, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent. |
| [getFormattingOptions](#getFormattingOptions--) | Liest Formatierungsoptionen. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Liest die horizontale Ausrichtung für den Text innerhalb des Rechtecks des Absatzes. HorizontalAlignment.None entspricht HorizontalAlignment.Left. |
| [getHyphenSymbol](#getHyphenSymbol--) | Liest das Trennstrich‑Symbol, das im Silbentrennungsprozess verwendet wird. Das Trennstrich‑Symbol ist standardmäßig "-". Um das Zeichnen des Trennstrichs zu vermeiden (während das Zeilenumbruch‑Verfahren weiterhin aktiv bleibt), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty. |
| [getMargin](#getMargin--) | Liefert den Innenabstand. |
| [getPosition](#getPosition--) | Liest die Position des Absatzes. |
| [getRectangle](#getRectangle--) | Ermittelt das Rechteck des Absatzes. |
| [getRotation](#getRotation--) | Ermittelt oder legt den Rotationswinkel in Grad fest. |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Ermittelt den Einzugswert für nachfolgende Zeilen. |
| [getTextRectangle](#getTextRectangle--) | Ermittelt das Rechteck des Textes, der im Absatz platziert ist. |
| [getVerticalAlignment](#getVerticalAlignment--) | <p> Ermittelt die vertikale Ausrichtung für den Text innerhalb des {@code Rectangle} des Absatzes. </p> |
| [isJustify](#isJustify--) | Ermittelt, ob der Text im Blocksatz ist. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Legt die Hintergrundfarbe für den Textabsatz fest. |
| [setBackgroundMode](#setBackgroundMode-int-) | Lege den Hintergrundmodus für den Textabsatz fest. |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Liest oder setzt den Einzugswert für nachfolgende Zeilen. Wenn ein von Null verschiedener Wert gesetzt wird, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent. |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Legt Formatierungsoptionen fest. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Legt die horizontale Ausrichtung für den Text innerhalb des Rectangle des Absatzes fest. HorizontalAlignment.None entspricht HorizontalAlignment.Left. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | Legt das Trennzeichen fest, das im Trennungsprozess verwendet wird. Das Trennzeichen ist standardmäßig "-". Um das Zeichnen des Trennzeichens zu entfernen (während das Zeilenumbruchverfahren weiterhin aktiv bleibt), setzen Sie für HyphenSymbol die leere Zeichenkette string.Empty. |
| [setJustify](#setJustify-boolean-) | Legt fest, ob der Text im Blocksatz ist. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Legt den Innenabstand fest. |
| [setMatrix](#setMatrix-com.aspose.pdf.Matrix-) | Legt die Rotation des Absatzes fest. |
| [setOldCodeCompatibilityMode](#setOldCodeCompatibilityMode-boolean-) | Lege den Kompatibilitätsmodus für alten Code fest. |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | Legt die Position des Absatzes fest. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Legt das Rechteck des Absatzes fest. |
| [setRotation](#setRotation-double-) | Ermittelt oder legt den Rotationswinkel in Grad fest. |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Legt den Einzugswert für nachfolgende Zeilen fest. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Legt die vertikale Ausrichtung für den Text innerhalb des {@code Rectangle} des Absatzes fest. VerticalAlignment.None entspricht VerticalAlignment.Bottom. |

### TextParagraph {#TextParagraph--}
```
public TextParagraph()
```

Erstellt {@code TextParagraph} Objekt.

### appendLine {#appendLine-java.lang.String-}
Fügt Textzeile hinzu

### appendLine {#appendLine-java.lang.String-float-}
Fügt Textzeile hinzu.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-}
Fügt Textzeile mit Textzustands‑Parametern hinzu.

### appendLine {#appendLine-java.lang.String-com.aspose.pdf.TextState-float-}
Fügt Textzeile mit Textzustands‑Parametern hinzu

### appendLine {#appendLine-com.aspose.pdf.TextFragment-}
Fügt Textzeile mit Textzustands‑Parametern hinzu.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-}
Fügt Textzeile mit Textzustands‑Parametern hinzu.

### appendLine {#appendLine-com.aspose.pdf.TextFragment-com.aspose.pdf.TextState-float-}
Fügt Textzeile mit Textzustands‑Parametern hinzu

### beginEdit {#beginEdit--}
```
public void beginEdit()
```

Beginnt die Bearbeitung des TextParagraph. <p> Verbessert die Leistung der TextParagraph‑Population. Jede Layout‑Berechnung wird ausgesetzt, bis die EndEdit‑Methode aufgerufen wird. <p> Hinweis: Der Methodenaufruf kann nicht geschachtelt werden. </p>

### endEdit {#endEdit--}
```
public void endEdit()
```

Beendet die Bearbeitung des TextParagraph. <p> Verbessert die Leistung der TextParagraph‑Population. Jede Layout‑Berechnung wird ausgesetzt, bis die EndEdit‑Methode aufgerufen wird. <p> Hinweis: Der Methodenaufruf kann nicht geschachtelt werden. </p>

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Liest oder setzt den Einzugswert für nachfolgende Zeilen. Wenn ein von Null verschiedener Wert gesetzt wird, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent.

**Returns:**
float-Wert

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Liest Formatierungsoptionen.

**Returns:**
TextFormattingOptions-Objekt

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Liest die horizontale Ausrichtung für den Text innerhalb des Rechtecks des Absatzes. HorizontalAlignment.None entspricht HorizontalAlignment.Left.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getHyphenSymbol {#getHyphenSymbol--}
```
public String getHyphenSymbol()
```

Liest das Trennstrich‑Symbol, das im Silbentrennungsprozess verwendet wird. Das Trennstrich‑Symbol ist standardmäßig "-". Um das Zeichnen des Trennstrichs zu vermeiden (während das Zeilenumbruch‑Verfahren weiterhin aktiv bleibt), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty.

**Returns:**
String Wert

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Liefert den Innenabstand.

**Returns:**
MarginInfo-Wert

### getPosition {#getPosition--}
```
public Position getPosition()
```

Liest die Position des Absatzes.

**Returns:**
Positionswert

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Ermittelt das Rechteck des Absatzes.

**Returns:**
Rectangle-Objekt

### getRotation {#getRotation--}
```
public double getRotation()
```

Ermittelt oder legt den Rotationswinkel in Grad fest.

**Returns:**
double-Wert

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Ermittelt den Einzugswert für nachfolgende Zeilen.

**Returns:**
float-Wert

### getTextRectangle {#getTextRectangle--}
```
public Rectangle getTextRectangle()
```

Ermittelt das Rechteck des Textes, der im Absatz platziert ist.

**Returns:**
Rectangle-Objekt

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

<p> Ermittelt die vertikale Ausrichtung für den Text innerhalb des {@code Rectangle} des Absatzes. </p>

**Returns:**
VerticalAlignment-Wert @see VerticalAlignment <hr> <p> VerticalAlignment.None entspricht VerticalAlignment.Bottom. </p>

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Ermittelt, ob der Text im Blocksatz ist.

**Returns:**
boolescher Wert

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Legt die Hintergrundfarbe für den Textabsatz fest.

### setBackgroundMode {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```

Lege den Hintergrundmodus für den Textabsatz fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see TextBackgroundMode |

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Liest oder setzt den Einzugswert für nachfolgende Zeilen. Wenn ein von Null verschiedener Wert gesetzt wird, hat er einen Vorteil gegenüber dem Wert FormattingOptions.SubsequentLinesIndent.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Legt Formatierungsoptionen fest.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Legt die horizontale Ausrichtung für den Text innerhalb des Rectangle des Absatzes fest. HorizontalAlignment.None entspricht HorizontalAlignment.Left.

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
Legt das Trennzeichen fest, das im Trennungsprozess verwendet wird. Das Trennzeichen ist standardmäßig "-". Um das Zeichnen des Trennzeichens zu entfernen (während das Zeilenumbruchverfahren weiterhin aktiv bleibt), setzen Sie für HyphenSymbol die leere Zeichenkette string.Empty.

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Legt fest, ob der Text im Blocksatz ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Legt den Innenabstand fest.

### setMatrix {#setMatrix-com.aspose.pdf.Matrix-}
Legt die Rotation des Absatzes fest.

### setOldCodeCompatibilityMode {#setOldCodeCompatibilityMode-boolean-}
```
public void setOldCodeCompatibilityMode(boolean value)
```

Lege den Kompatibilitätsmodus für alten Code fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPosition {#setPosition-com.aspose.pdf.Position-}
Legt die Position des Absatzes fest.

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Legt das Rechteck des Absatzes fest.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Ermittelt oder legt den Rotationswinkel in Grad fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Legt den Einzugswert für nachfolgende Zeilen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Legt die vertikale Ausrichtung für den Text innerhalb des {@code Rectangle} des Absatzes fest. VerticalAlignment.None entspricht VerticalAlignment.Bottom.
