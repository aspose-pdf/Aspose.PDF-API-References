---
title: "TextStamp"
linktitle: "TextStamp"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Textstempel dar."
type: docs
weight: 5320
url: /de/java/com.aspose.pdf/textstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp

```
public class TextStamp extends Stamp
```

Stellt einen Textstempel dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-) | Initialisiert eine neue Instanz der {@code TextStamp}-Klasse mit dem formattedText-Objekt |
| [TextStamp](#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-) | Initialisiert eine neue Instanz der {@code TextStamp}-Klasse mit dem formattedText-Objekt |
| [TextStamp](#TextStamp-java.lang.String-) | Initialisiert eine neue Instanz der {@code TextStamp}-Klasse. |
| [TextStamp](#TextStamp-java.lang.String-com.aspose.pdf.TextState-) | Initialisiert eine neue Instanz der TextStamp-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAutoAdjustFontSizePrecision](#getAutoAdjustFontSizePrecision--) | Automatisch die Schriftgröße‑Präzision anpassen. Standardwert: 0.1; |
| [getAutoAdjustFontSizeToFitStampRectangle](#getAutoAdjustFontSizeToFitStampRectangle--) | Wenn aktiviert, wird die Schriftgröße automatisch angepasst, um das Stempelrechteck der Größe {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) und {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) zu füllen. Standardbreite und -höhe werden aus dem Seitenrechteck abgeleitet. |
| [getDefaultFont](#getDefaultFont--) | Gibt die Standardschrift zurück |
| [getDefaultFontSize](#getDefaultFontSize--) | Standard‑Schriftgröße |
| [getDraw](#getDraw--) | Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als Grafikoperatoren gezeichnet, und wenn draw = false, wird der Stempel als Text gezeichnet. |
| [getFontSize](#getFontSize--) | Tatsächliche Schriftgröße nach dem Platzieren des Stempels. (Kann von der initialen Schriftgröße abweichen, die über den Konstruktor bereitgestellt wurde, wenn die Option 'AutoAdjustFontSizeToFitStampRectangle' aktiviert ist.) |
| [getHeight](#getHeight--) | Gewünschte Höhe des Stempels auf der Seite. |
| [getMaxRowWidth](#getMaxRowWidth--) | Maximale Zeilenhöhe für die WordWrap‑Option. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Liest oder setzt den Modus, der das Verhalten definiert, falls Schriften die angeforderten Zeichen nicht enthalten. |
| [getReplacementFont](#getReplacementFont--) | Liest oder setzt die Schrift, die als Ersatz verwendet wird, wenn die Benutzerschrift das erforderliche Zeichen nicht enthält. |
| [getTextAlignment](#getTextAlignment--) | Ausrichtung des Textes innerhalb des Stempels. |
| [getTextState](#getTextState--) | Liest die Texteigenschaften des Stempels. Siehe {@code TextState} für Details. |
| [getTreatYIndentAsBaseLine](#getTreatYIndentAsBaseLine--) | Definiert den Koordinatenursprung für das Platzieren von Text. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true), wird der YIndent-Wert als Textgrundlinie behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false), wird der YIndent-Wert als Unterkante (Deszendentlinie) des Textes behandelt. |
| [getValue](#getValue--) | Liest den Zeichenkettenwert, der als Stempel auf der Seite verwendet wird. |
| [getWidth](#getWidth--) | Gewünschte Breite des Stempels auf der Seite. |
| [getWordWrapMode](#getWordWrapMode--) | Liest oder setzt den Zeilenumbruchmodus für die Textdarstellung. |
| [isJustify](#isJustify--) | Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, werden sowohl linke als auch rechte Textkanten ausgerichtet. Standardwert: false. |
| [isScale](#isScale--) | Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text skaliert, um die angegebene Breite zu füllen. |
| [isWordWrap](#isWordWrap--) | Definiert den Zeilenumbruch. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text in mehrere Zeilen umbrochen, um in die angegebene Breite zu passen. Standardwert: false. |
| [put](#put-com.aspose.pdf.Page-) | Fügt einen Textstempel auf der Seite hinzu. |
| [setAutoAdjustFontSizePrecision](#setAutoAdjustFontSizePrecision-float-) | Automatisch die Schriftgröße‑Präzision anpassen. Standardwert: 0.1; |
| [setAutoAdjustFontSizeToFitStampRectangle](#setAutoAdjustFontSizeToFitStampRectangle-boolean-) | Wenn aktiviert, wird die Schriftgröße automatisch angepasst, um das Stempelrechteck der Größe {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) und {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) zu füllen. Standardbreite und -höhe werden aus dem Seitenrechteck abgeleitet. |
| [setDraw](#setDraw-boolean-) | Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als Grafikoperatoren gezeichnet, und wenn draw = false, wird der Stempel als Text gezeichnet. |
| [setHeight](#setHeight-double-) | Gewünschte Höhe des Stempels auf der Seite. |
| [setJustify](#setJustify-boolean-) | Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, werden sowohl linke als auch rechte Textkanten ausgerichtet. Standardwert: false. |
| [setMaxRowWidth](#setMaxRowWidth-double-) | Maximale Zeilenhöhe für die WordWrap‑Option. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-int-) | Liest oder setzt den Modus, der das Verhalten definiert, falls Schriften die angeforderten Zeichen nicht enthalten. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Liest oder setzt die Schrift, die als Ersatz verwendet wird, wenn die Benutzerschrift das erforderliche Zeichen nicht enthält. |
| [setScale](#setScale-boolean-) | Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text skaliert, um die angegebene Breite zu füllen. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Ausrichtung des Textes innerhalb des Stempels. |
| [setTreatYIndentAsBaseLine](#setTreatYIndentAsBaseLine-boolean-) | Definiert den Koordinatenursprung für das Platzieren von Text. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true), wird der YIndent-Wert als Textgrundlinie behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false), wird der YIndent-Wert als Unterkante (Deszendentlinie) des Textes behandelt. |
| [setValue](#setValue-java.lang.String-) | Setzt den Zeichenkettenwert, der als Stempel auf der Seite verwendet wird. |
| [setWidth](#setWidth-double-) | Gewünschte Breite des Stempels auf der Seite. |
| [setWordWrap](#setWordWrap-boolean-) | Definiert den Zeilenumbruch. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text in mehrere Zeilen umbrochen, um in die angegebene Breite zu passen. Standardwert: false. |
| [setWordWrapMode](#setWordWrapMode-int-) | Liest oder setzt den Zeilenumbruchmodus für die Textdarstellung. |

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-}
Initialisiert eine neue Instanz der {@code TextStamp}-Klasse mit dem formattedText-Objekt

### TextStamp {#TextStamp-com.aspose.pdf.facades.FormattedText-com.aspose.pdf.TextState-}
Initialisiert eine neue Instanz der {@code TextStamp}-Klasse mit dem formattedText-Objekt

### TextStamp {#TextStamp-java.lang.String-}
Initialisiert eine neue Instanz der {@code TextStamp}-Klasse.

### TextStamp {#TextStamp-java.lang.String-com.aspose.pdf.TextState-}
Initialisiert eine neue Instanz der TextStamp-Klasse.

### getAutoAdjustFontSizePrecision {#getAutoAdjustFontSizePrecision--}
```
public final float getAutoAdjustFontSizePrecision()
```

Automatisch die Schriftgröße‑Präzision anpassen. Standardwert: 0.1;

**Returns:**
float-Wert

### getAutoAdjustFontSizeToFitStampRectangle {#getAutoAdjustFontSizeToFitStampRectangle--}
```
public final boolean getAutoAdjustFontSizeToFitStampRectangle()
```

Wenn aktiviert, wird die Schriftgröße automatisch angepasst, um das Stempelrechteck der Größe {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) und {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) zu füllen. Standardbreite und -höhe werden aus dem Seitenrechteck abgeleitet.

**Returns:**
boolescher Wert

### getDefaultFont {#getDefaultFont--}
```
public static Font getDefaultFont()
```

Gibt die Standardschrift zurück

**Returns:**
com.aspose.pdf.Font-Objekt

### getDefaultFontSize {#getDefaultFontSize--}
```
public static float getDefaultFontSize()
```

Standard‑Schriftgröße

**Returns:**
float-Wert

### getDraw {#getDraw--}
```
public boolean getDraw()
```

Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als Grafikoperatoren gezeichnet, und wenn draw = false, wird der Stempel als Text gezeichnet.

**Returns:**
boolescher Wert

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Tatsächliche Schriftgröße nach dem Platzieren des Stempels. (Kann von der initialen Schriftgröße abweichen, die über den Konstruktor bereitgestellt wurde, wenn die Option 'AutoAdjustFontSizeToFitStampRectangle' aktiviert ist.)

**Returns:**
float-Wert

### getHeight {#getHeight--}
```
public double getHeight()
```

Gewünschte Höhe des Stempels auf der Seite.

**Returns:**
double-Wert

### getMaxRowWidth {#getMaxRowWidth--}
```
public double getMaxRowWidth()
```

Maximale Zeilenhöhe für die WordWrap‑Option.

**Returns:**
double-Wert

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public final int getNoCharacterBehavior()
```

Liest oder setzt den Modus, der das Verhalten definiert, falls Schriften die angeforderten Zeichen nicht enthalten.

**Returns:**
NoCharacterAction-Element

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Liest oder setzt die Schrift, die als Ersatz verwendet wird, wenn die Benutzerschrift das erforderliche Zeichen nicht enthält.

**Returns:**
Font Instanz

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Ausrichtung des Textes innerhalb des Stempels.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Liest die Texteigenschaften des Stempels. Siehe {@code TextState} für Details.

**Returns:**
TextState-Element

### getTreatYIndentAsBaseLine {#getTreatYIndentAsBaseLine--}
```
public boolean getTreatYIndentAsBaseLine()
```

Definiert den Koordinatenursprung für das Platzieren von Text. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true), wird der YIndent-Wert als Textgrundlinie behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false), wird der YIndent-Wert als Unterkante (Deszendentlinie) des Textes behandelt.

**Returns:**
boolescher Wert

### getValue {#getValue--}
```
public String getValue()
```

Liest den Zeichenkettenwert, der als Stempel auf der Seite verwendet wird.

**Returns:**
String Wert

### getWidth {#getWidth--}
```
public double getWidth()
```

Gewünschte Breite des Stempels auf der Seite.

**Returns:**
double-Wert

### getWordWrapMode {#getWordWrapMode--}
```
public final int getWordWrapMode()
```

Liest oder setzt den Zeilenumbruchmodus für die Textdarstellung.

**Returns:**
WordWrapMode-Element

### isJustify {#isJustify--}
```
public boolean isJustify()
```

Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, werden sowohl linke als auch rechte Textkanten ausgerichtet. Standardwert: false.

**Returns:**
boolescher Wert

### isScale {#isScale--}
```
public boolean isScale()
```

Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text skaliert, um die angegebene Breite zu füllen.

**Returns:**
boolescher Wert

### isWordWrap {#isWordWrap--}
```
@Deprecated public boolean isWordWrap()
```

Definiert den Zeilenumbruch. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text in mehrere Zeilen umbrochen, um in die angegebene Breite zu passen. Standardwert: false.

**Returns:**
boolescher Wert @deprecated "Verwenden Sie WordWrapMode stattdessen."

### put {#put-com.aspose.pdf.Page-}
Fügt einen Textstempel auf der Seite hinzu.

### setAutoAdjustFontSizePrecision {#setAutoAdjustFontSizePrecision-float-}
```
public final void setAutoAdjustFontSizePrecision(float value)
```

Automatisch die Schriftgröße‑Präzision anpassen. Standardwert: 0.1;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setAutoAdjustFontSizeToFitStampRectangle {#setAutoAdjustFontSizeToFitStampRectangle-boolean-}
```
public final void setAutoAdjustFontSizeToFitStampRectangle(boolean value)
```

Wenn aktiviert, wird die Schriftgröße automatisch angepasst, um das Stempelrechteck der Größe {@code Width}({@code Stamp#getWidth}/{@code Stamp#setWidth(double)}) und {@code Height}({@code Stamp#getHeight}/{@code Stamp#setHeight(double)}) zu füllen. Standardbreite und -höhe werden aus dem Seitenrechteck abgeleitet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setDraw {#setDraw-boolean-}
```
public void setDraw(boolean value)
```

Diese Eigenschaft bestimmt, wie der Stempel auf der Seite gezeichnet wird. Wenn Draw = true, wird der Stempel als Grafikoperatoren gezeichnet, und wenn draw = false, wird der Stempel als Text gezeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Gewünschte Höhe des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setJustify {#setJustify-boolean-}
```
public void setJustify(boolean value)
```

Definiert die Textausrichtung. Wenn diese Eigenschaft auf true gesetzt ist, werden sowohl linke als auch rechte Textkanten ausgerichtet. Standardwert: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMaxRowWidth {#setMaxRowWidth-double-}
```
public void setMaxRowWidth(double value)
```

Maximale Zeilenhöhe für die WordWrap‑Option.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setNoCharacterBehavior {#setNoCharacterBehavior-int-}
```
public final void setNoCharacterBehavior(int value)
```

Liest oder setzt den Modus, der das Verhalten definiert, falls Schriften die angeforderten Zeichen nicht enthalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | NoCharacterAction-Element |

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Liest oder setzt die Schrift, die als Ersatz verwendet wird, wenn die Benutzerschrift das erforderliche Zeichen nicht enthält.

### setScale {#setScale-boolean-}
```
public void setScale(boolean value)
```

Definiert die Skalierung des Textes. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text skaliert, um die angegebene Breite zu füllen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Ausrichtung des Textes innerhalb des Stempels.

### setTreatYIndentAsBaseLine {#setTreatYIndentAsBaseLine-boolean-}
```
public void setTreatYIndentAsBaseLine(boolean value)
```

Definiert den Koordinatenursprung für das Platzieren von Text. Wenn TreatYIndentAsBaseLine = true (Standard, wenn Draw = true), wird der YIndent-Wert als Textgrundlinie behandelt. Wenn TreatYIndentAsBaseLine = false (Standard, wenn Draw = false), wird der YIndent-Wert als Unterkante (Deszendentlinie) des Textes behandelt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setValue {#setValue-java.lang.String-}
Setzt den Zeichenkettenwert, der als Stempel auf der Seite verwendet wird.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Gewünschte Breite des Stempels auf der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setWordWrap {#setWordWrap-boolean-}
```
@Deprecated public void setWordWrap(boolean value)
```

Definiert den Zeilenumbruch. Wenn diese Eigenschaft auf true gesetzt ist und ein Width-Wert angegeben wurde, wird der Text in mehrere Zeilen umbrochen, um in die angegebene Breite zu passen. Standardwert: false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert @deprecated "Verwenden Sie WordWrapMode stattdessen." |

### setWordWrapMode {#setWordWrapMode-int-}
```
public final void setWordWrapMode(int value)
```

Liest oder setzt den Zeilenumbruchmodus für die Textdarstellung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | WordWrapMode-Element @see WordWrapMode |
