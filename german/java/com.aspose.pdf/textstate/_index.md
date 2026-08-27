---
title: "TextState"
linktitle: "TextState"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Textzustand eines Textes dar"
type: docs
weight: 5340
url: /de/java/com.aspose.pdf/textstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState

```
public class TextState extends Object
```

Stellt einen Textzustand eines Textes dar

## Felder

| Feld | Beschreibung |
| --- | --- |
| [TabstopDefaultValue](#TabstopDefaultValue) | Standardwert der Tabulation in den Breiten des Leerzeichens der Standardschriftart. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextState](#TextState--) | Erstellt ein TextState-Objekt. |
| [TextState](#TextState-java.awt.Color-) | Erstellt ein TextState-Objekt. |
| [TextState](#TextState-java.awt.Color-double-) | Erstellt ein TextState-Objekt. |
| [TextState](#TextState-double-) | Erstellt ein TextState-Objekt mit Angabe der Schriftgröße. |
| [TextState](#TextState-java.lang.String-) | Erstellt ein TextState-Objekt. |
| [TextState](#TextState-java.lang.String-boolean-boolean-) | Erstellt ein TextState-Objekt. |
| [TextState](#TextState-java.lang.String-double-) | Erstellt ein TextState-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Übernimmt Einstellungen von einem anderen TextState </p> <hr> <p> Nur jene Eigenschaften werden kopiert, die explizit geändert wurden. </p> |
| [calculateFontSize](#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-) | Berechnet die Schriftgröße für das Rechteck. |
| [getBackgroundColor](#getBackgroundColor--) | <p> Ermittelt die Hintergrundfarbe des Textes. </p> <hr> <p> Beachten Sie, dass der Wert nicht als Texteigenschaft im Dokument erhalten bleibt. Der Getter der BackgroundColor-Eigenschaft funktioniert für ein Objekt, falls es zuvor explizit mit dem BackgroundColor-Setter für dieses Objekt gesetzt wurde. Die Eigenschaft wird zur Laufzeit im Kontext des aktuellen Erstellungs-/Änderungsprozesses verwendet. </p> |
| [getCharacterSpacing](#getCharacterSpacing--) | Ermittelt den Zeichenabstand des Textes. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| [getFont](#getFont--) | Ermittelt die Schriftart des Textes. |
| [getfontSize](#getfontSize--) | Repräsentiert die getfontSize-Methode. |
| [getFontSize](#getFontSize--) | Ermittelt die Schriftgröße des Textes. |
| [getFontStyle](#getFontStyle--) | Setzt den Schriftstil des Textes. |
| [getForegroundColor](#getForegroundColor--) | Ermittelt die Vordergrundfarbe des Textes. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Ermittelt die horizontale Ausrichtung des Textes. </p> <hr> <p> HorizontalAlignment.None ist gleichbedeutend mit HorizontalAlignment.Left. Beachten Sie, dass die TextState.HorizontalAlignment-Eigenschaft nur in Szenarien der Neuerstellung von Dokumenten funktioniert. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Ermittelt die horizontale Skalierung des Textes. |
| [getLineSpacing](#getLineSpacing--) | <p> Ermittelt den Zeilenabstand des Textes. </p> |
| [getRenderingMode](#getRenderingMode--) | Ermittelt oder setzt den Rendermodus des Textes. |
| [getStrokingColor](#getStrokingColor--) | Ermittelt oder setzt die Vordergrundfarbe des Textes. |
| [getTabTag](#getTabTag--) | <p> Sie können dieses Tag im Text platzieren, um eine Tabulation zu deklarieren. </p> <hr> <p> Es wirkt nur in Kombination mit {@code TabStops}. </p> |
| [getTextHeight](#getTextHeight--) | Ermittelt die Texthöhe. |
| [getWordSpacing](#getWordSpacing--) | Ermittelt den Wortabstand des Textes. |
| [isInvisible](#isInvisible--) | Ermittelt die Unsichtbarkeit des Textes. Dies spiegelt im Wesentlichen den {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})-Zustand wider, mit Ausnahme einiger Sonderfälle (wie Clipping). |
| [isStrikeOut](#isStrikeOut--) | Ermittelt den Durchstrich für den Text, dargestellt durch das {@code TextFragment}-Objekt. |
| [isSubscript](#isSubscript--) | Liest oder setzt die Tiefstellung des Textes. |
| [isSuperscript](#isSuperscript--) | Liest die Hochstellung des Textes. |
| [isUnderline](#isUnderline--) | Liest die Unterstreichung für den Text, dargestellt durch das {@code TextFragment}-Objekt |
| [measureHeight](#measureHeight-char-) | Misst die Zeichenhöhe. |
| [measureString](#measureString-java.lang.String-) | Misst die Zeichenkette. |
| [measureString](#measureString-java.lang.String-boolean-) | <p> Misst die Zeichenkette. </p> <hr> <p> insideLine gibt an, dass die Zeichenkette nicht endet. Falls ein Teil der gesamten Zeichenkette gemessen wird – insideLine sollte true sein. Falls die gesamte Zeichenkette gemessen wird, sollte insideLine false sein. Mit anderen Worten: Wenn insideLine = true, werden nur Zeichenbreiten berücksichtigt. Bei insideLine = false werden keine zusätzlichen Transformationen berücksichtigt; das Ende der Zeichenkette wird korrekt behandelt – die kursive Transformation wird berücksichtigt. </p> |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Setzt die Hintergrundfarbe des Textes. |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Setzt den Zeichenabstand des Textes. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Ermittelt die Schriftart des Textes. |
| [setFontSize](#setFontSize-float-) | Setzt die Schriftgröße des Textes. |
| [setFontSizeSuppressedUpdate](#setFontSizeSuppressedUpdate-float-) | Setzt die Schriftgröße des Textes mit unterdrücktem Update. |
| [setFontStyle](#setFontStyle-int-) | Setzt den Schriftstil des Textes. |
| [setFontSuppressedUpdate](#setFontSuppressedUpdate-com.aspose.pdf.Font-) | Liest die Schrift des Textes mit unterdrücktem Update. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Setzt die Vordergrundfarbe des Textes. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Setzt die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None ist gleichbedeutend mit HorizontalAlignment.Left. Hinweis: Die Eigenschaft TextState.HorizontalAlignment funktioniert nur in Szenarien der Neuerstellung von Dokumenten. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Setzt die horizontale Skalierung des Textes. |
| [setInvisible](#setInvisible-boolean-) | Setzt die Unsichtbarkeit des Textes. Dies spiegelt im Wesentlichen den {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})-Zustand wider, außer in einigen Sonderfällen (wie Clipping). |
| [setLineSpacing](#setLineSpacing-float-) | <p> Setzt den Zeilenabstand des Textes. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Ermittelt oder setzt den Rendermodus des Textes. |
| [setStrikeOut](#setStrikeOut-boolean-) | Setzt den Durchstrich für den Text, dargestellt durch das {@code TextFragment}-Objekt |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Ermittelt oder setzt die Vordergrundfarbe des Textes. |
| [setSubscript](#setSubscript-boolean-) | Liest oder setzt die Tiefstellung des Textes. |
| [setSuperscript](#setSuperscript-boolean-) | Setzt die Hochstellung des Textes. |
| [setUnderline](#setUnderline-boolean-) | Setzt die Unterstreichung für den Text, dargestellt durch das {@code TextFragment}-Objekt |
| [setWordSpacing](#setWordSpacing-float-) | Setzt den Wortabstand des Textes. |

### TabstopDefaultValue {#TabstopDefaultValue}
```
public final float TabstopDefaultValue
```

Standardwert der Tabulation in den Breiten des Leerzeichens der Standardschriftart.

### TextState {#TextState--}
```
public TextState()
```

Erstellt ein TextState-Objekt.

### TextState {#TextState-java.awt.Color-}
Erstellt ein TextState-Objekt.

### TextState {#TextState-java.awt.Color-double-}
Erstellt ein TextState-Objekt.

### TextState {#TextState-double-}
```
public TextState(double fontSize)
```

Erstellt ein TextState-Objekt mit Angabe der Schriftgröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSize |  | Schriftgröße. |

### TextState {#TextState-java.lang.String-}
Erstellt ein TextState-Objekt.

### TextState {#TextState-java.lang.String-boolean-boolean-}
Erstellt ein TextState-Objekt.

### TextState {#TextState-java.lang.String-double-}
Erstellt ein TextState-Objekt.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Übernimmt Einstellungen von einem anderen TextState </p> <hr> <p> Nur jene Eigenschaften werden kopiert, die explizit geändert wurden. </p>

### calculateFontSize {#calculateFontSize-java.lang.String-com.aspose.pdf.Rectangle-}
Berechnet die Schriftgröße für das Rechteck.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

<p> Ermittelt die Hintergrundfarbe des Textes. </p> <hr> <p> Beachten Sie, dass der Wert nicht als Texteigenschaft im Dokument erhalten bleibt. Der Getter der BackgroundColor-Eigenschaft funktioniert für ein Objekt, falls es zuvor explizit mit dem BackgroundColor-Setter für dieses Objekt gesetzt wurde. Die Eigenschaft wird zur Laufzeit im Kontext des aktuellen Erstellungs-/Änderungsprozesses verwendet. </p>

**Returns:**
Farbwert

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Ermittelt den Zeichenabstand des Textes.

**Returns:**
float-Wert

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden.

**Returns:**
CoordinateOrigin-Element

### getFont {#getFont--}
```
public Font getFont()
```

Ermittelt die Schriftart des Textes.

**Returns:**
Schrift-Objekt

### getfontSize {#getfontSize--}
```
public float getfontSize()
```

Repräsentiert die getfontSize-Methode.

**Returns:**
float-Wert

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Ermittelt die Schriftgröße des Textes.

**Returns:**
float-Wert

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Setzt den Schriftstil des Textes.

**Returns:**
FontStyles-Element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Ermittelt die Vordergrundfarbe des Textes.

**Returns:**
Farbwert

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Ermittelt die horizontale Ausrichtung des Textes. </p> <hr> <p> HorizontalAlignment.None ist gleichbedeutend mit HorizontalAlignment.Left. Beachten Sie, dass die TextState.HorizontalAlignment-Eigenschaft nur in Szenarien der Neuerstellung von Dokumenten funktioniert. </p>

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Ermittelt die horizontale Skalierung des Textes.

**Returns:**
float-Wert

### getLineSpacing {#getLineSpacing--}
```
public float getLineSpacing()
```

<p> Ermittelt den Zeilenabstand des Textes. </p>

**Returns:**
float value <hr> <p> Beachten Sie, dass der Wert nicht als Texteigenschaft im Dokument erhalten bleibt. Der Getter der LineSpacing‑Eigenschaft funktioniert für ein Objekt, falls er zuvor explizit mit dem LineSpacing‑Setter für dieses Objekt gesetzt wurde. Die Eigenschaft wird zur Laufzeit im Kontext des aktuellen Erstellungs‑/Änderungsprozesses verwendet. </p>

### getRenderingMode {#getRenderingMode--}
```
public TextRenderingMode getRenderingMode()
```

Ermittelt oder setzt den Rendermodus des Textes.

**Returns:**
TextRenderingMode-Element @see TextRenderingMode

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Ermittelt oder setzt die Vordergrundfarbe des Textes.

**Returns:**
Color-Instanz

### getTabTag {#getTabTag--}
```
public final String getTabTag()
```

<p> Sie können dieses Tag im Text platzieren, um eine Tabulation zu deklarieren. </p> <hr> <p> Es wirkt nur in Kombination mit {@code TabStops}. </p>

**Returns:**
String-Wert "#$TAB"

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Ermittelt die Texthöhe.

**Returns:**
float-Wert

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Ermittelt den Wortabstand des Textes.

**Returns:**
float-Wert

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Ermittelt die Unsichtbarkeit des Textes. Dies spiegelt im Wesentlichen den {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})-Zustand wider, mit Ausnahme einiger Sonderfälle (wie Clipping).

**Returns:**
boolescher Wert

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Ermittelt den Durchstrich für den Text, dargestellt durch das {@code TextFragment}-Objekt.

**Returns:**
boolescher Wert

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Liest oder setzt die Tiefstellung des Textes.

**Returns:**
boolescher Wert

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Liest die Hochstellung des Textes.

**Returns:**
boolescher Wert

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Liest die Unterstreichung für den Text, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
boolescher Wert

### measureHeight {#measureHeight-char-}
```
public double measureHeight(char character)
```

Misst die Zeichenhöhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeichen |  | Zu messendes Zeichen. |

**Returns:**
Höhe des Zeichens, falls sie aus der Schriftart ermittelt werden kann; sonst 0.

### measureString {#measureString-java.lang.String-}
Misst die Zeichenkette.

### measureString {#measureString-java.lang.String-boolean-}
<p> Misst die Zeichenkette. </p> <hr> <p> insideLine gibt an, dass die Zeichenkette nicht endet. Falls ein Teil der gesamten Zeichenkette gemessen wird – insideLine sollte true sein. Falls die gesamte Zeichenkette gemessen wird, sollte insideLine false sein. Mit anderen Worten: Wenn insideLine = true, werden nur Zeichenbreiten berücksichtigt. Bei insideLine = false werden keine zusätzlichen Transformationen berücksichtigt; das Ende der Zeichenkette wird korrekt behandelt – die kursive Transformation wird berücksichtigt. </p>

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Setzt die Hintergrundfarbe des Textes.

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Setzt den Zeichenabstand des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden.

### setFont {#setFont-com.aspose.pdf.Font-}
Ermittelt die Schriftart des Textes.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Setzt die Schriftgröße des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setFontSizeSuppressedUpdate {#setFontSizeSuppressedUpdate-float-}
```
public void setFontSizeSuppressedUpdate(float value)
```

Setzt die Schriftgröße des Textes mit unterdrücktem Update.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Setzt den Schriftstil des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | FontStyles-Wert @see FontStyles |

### setFontSuppressedUpdate {#setFontSuppressedUpdate-com.aspose.pdf.Font-}
Liest die Schrift des Textes mit unterdrücktem Update.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Setzt die Vordergrundfarbe des Textes.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Setzt die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None ist gleichbedeutend mit HorizontalAlignment.Left. Hinweis: Die Eigenschaft TextState.HorizontalAlignment funktioniert nur in Szenarien der Neuerstellung von Dokumenten. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Setzt die horizontale Skalierung des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Setzt die Unsichtbarkeit des Textes. Dies spiegelt im Wesentlichen den {@code RenderingMode}({@link #getRenderingMode}/{@code #setRenderingMode(TextRenderingMode)})-Zustand wider, außer in einigen Sonderfällen (wie Clipping).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLineSpacing {#setLineSpacing-float-}
```
public void setLineSpacing(float value)
```

<p> Setzt den Zeilenabstand des Textes. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float value <hr> <p> Beachten Sie, dass der Wert nicht als Texteigenschaft im Dokument erhalten bleibt. Der Getter der LineSpacing‑Eigenschaft funktioniert für ein Objekt, falls er zuvor explizit mit dem LineSpacing‑Setter für dieses Objekt gesetzt wurde. Die Eigenschaft wird zur Laufzeit im Kontext des aktuellen Erstellungs‑/Änderungsprozesses verwendet. </p> |

### setRenderingMode {#setRenderingMode-com.aspose.pdf.TextRenderingMode-}
Ermittelt oder setzt den Rendermodus des Textes.

### setStrikeOut {#setStrikeOut-boolean-}
```
public void setStrikeOut(boolean value)
```

Setzt den Durchstrich für den Text, dargestellt durch das {@code TextFragment}-Objekt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setStrokingColor {#setStrokingColor-com.aspose.pdf.Color-}
Ermittelt oder setzt die Vordergrundfarbe des Textes.

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Liest oder setzt die Tiefstellung des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Setzt die Hochstellung des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUnderline {#setUnderline-boolean-}
```
public void setUnderline(boolean value)
```

Setzt die Unterstreichung für den Text, dargestellt durch das {@code TextFragment}-Objekt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setWordSpacing {#setWordSpacing-float-}
```
public void setWordSpacing(float value)
```

Setzt den Wortabstand des Textes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |
