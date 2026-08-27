---
title: "TextFragmentState"
linktitle: "TextFragmentState"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt einen Textzustand eines Textfragmentes dar. </p> <hr> <pre> Das Beispiel demonstriert, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt ändert. // Open."
type: docs
weight: 5150
url: /de/java/com.aspose.pdf/textfragmentstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextState com.aspose.pdf.TextFragmentState, com.aspose.pdf.TextState, com.aspose.pdf.TextFragmentState

```
public final class TextFragmentState extends TextState
```

<p> Stellt einen Textzustand eines Textfragmentes dar. </p> <hr> <pre> Das Beispiel zeigt, wie man die Textfarbe und Schriftgröße des Textes mit dem {@code TextState}-Objekt ändert. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> Bietet eine Möglichkeit, die folgenden Eigenschaften des Textes zu ändern: Schriftart ({@code TextFragmentState.Font} property) Schriftgröße ({@code TextFragmentState.FontSize} property) Schriftstil ({@code TextFragmentState.FontStyle} property) Vordergrundfarbe ({@code TextFragmentState.ForegroundColor} property) Hintergrundfarbe ({@code TextFragmentState.BackgroundColor} property) </p> <p> Hinweis: Das Ändern von {@code TextFragmentState}-Eigenschaften kann die innere {@code TextFragment.Segments}-Sammlung verändern, da TextFragment ein Aggregatobjekt ist und interne Segmente neu anordnen oder zu einem einzigen Segment zusammenführen kann. Wenn Sie die {@code TextFragment.Segments}-Sammlung unverändert lassen möchten, ändern Sie bitte die inneren Segmente einzeln. </p> @see TextFragmentAbsorber @see IDocument

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFragmentState](#TextFragmentState-com.aspose.pdf.TextFragment-) | Initialisiert eine neue Instanz des {@code TextFragmentState}-Objekts mit dem angegebenen {@code TextFragment}-Objekt. Diese {@code TextFragmentState}-Initialisierung wird nicht unterstützt. TextFragmentState ist nur über die {@code TextFragment.TextState}-Eigenschaft verfügbar. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-) | <p> Übernimmt Einstellungen von einem anderen textState </p> |
| [applyChangesFrom](#applyChangesFrom-com.aspose.pdf.TextState-boolean-) | Übernimmt Einstellungen von einem anderen textState |
| [getBackgroundColor](#getBackgroundColor--) | Setzt die Hintergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [getCharacterSpacing](#getCharacterSpacing--) | Liefert den Zeichenabstand des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [getCoordinateOrigin](#getCoordinateOrigin--) | Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| [getDrawTextRectangleBorder](#getDrawTextRectangleBorder--) | Liefert das Flag, ob der Textrechteckrahmen gezeichnet wird. |
| [getFont](#getFont--) | Liefert die Schriftart des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [getFontSize](#getFontSize--) | Liefert die Schriftgröße des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [getFontStyle](#getFontStyle--) | Setzt den Schriftstil des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [getForegroundColor](#getForegroundColor--) | Liefert die Vordergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [getFormattingOptions](#getFormattingOptions--) | Liefert oder setzt Formatierungsoptionen. Das Setzen der Optionen ist nur in Generatorszenarien wirksam. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | <p> Liefert die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None entspricht HorizontalAlignment.Left. Hinweis: Die Eigenschaft TextFragmentState.VerticalAlignment funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. </p> |
| [getHorizontalScaling](#getHorizontalScaling--) | Liefert die horizontale Skalierung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [getLineSpacing](#getLineSpacing--) | <p> Ermittelt den Zeilenabstand des Textes. </p> |
| [getRenderingMode](#getRenderingMode--) | Liefert oder setzt den Rendermodus des Textes. |
| [getRotation](#getRotation--) | Ermittelt oder legt den Rotationswinkel in Grad fest. |
| [getStrokingColor](#getStrokingColor--) | Liefert oder setzt Farb-Strich-Operationen beim Rendern von {@code TextFragment} (Textstrich, Rechteckrahmen). |
| [getTabStops](#getTabStops--) | <p> Erhält Tabstopps für den Text. </p> <hr> <p> Hinweis: Die Tabstopps‑Eigenschaft funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. Tabstopps können während der {@code TextFragment}-Initialisierung hinzugefügt werden. Tabstopps müssen vor dem Text erstellt werden. </p> |
| [getTextHeight](#getTextHeight--) | Ermittelt die Texthöhe, dargestellt durch das {@code TextFragment}-Objekt |
| [getWordSpacing](#getWordSpacing--) | Ermittelt den Wortabstand des Textes. |
| [isFitRectangle](#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-) | Überprüft, ob die Eingabezeichenfolge innerhalb des definierten Rechtecks platziert werden kann. |
| [isInvisible](#isInvisible--) | Ermittelt die Unsichtbarkeit des Textes. |
| [isStrikeOut](#isStrikeOut--) | Liest oder setzt Durchstreichung für den Text, dargestellt durch das {@link TextFragment}-Objekt |
| [isSubscript](#isSubscript--) | Liest oder setzt Tiefstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [isSuperscript](#isSuperscript--) | Liest oder setzt Hochstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [isUnderline](#isUnderline--) | Liest oder setzt Unterstreichung für den Text, dargestellt durch das {@link TextFragment}-Objekt |
| [measureHeight](#measureHeight-char-) | Misst die Zeichenhöhe. |
| [measureString](#measureString-java.lang.String-) | Misst die Zeichenkette. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Setzt die Hintergrundfarbe des Textes, dargestellt durch das TextFragment-Objekt |
| [setCharacterSpacing](#setCharacterSpacing-float-) | Setzt den Zeichenabstand des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [setCoordinateOrigin](#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-) | Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden. |
| [setDrawTextRectangleBorder](#setDrawTextRectangleBorder-boolean-) | Setzt das Flag, ob der Rahmen des Textrechtecks gezeichnet wird. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Setzt die Schriftart des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [setFontSize](#setFontSize-float-) | Setzt die Schriftgröße des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [setFontStyle](#setFontStyle-int-) | Setzt den Schriftstil des Textes, dargestellt durch das {@link TextFragment}-Objekt |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Setzt die Vordergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt |
| [setFormattingOptions](#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-) | Liefert oder setzt Formatierungsoptionen. Das Setzen der Optionen ist nur in Generatorszenarien wirksam. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | <p> Setzt die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None entspricht HorizontalAlignment.Left. Hinweis: Die TextFragmentState.VerticalAlignment‑Eigenschaft funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. </p> |
| [setHorizontalScaling](#setHorizontalScaling-float-) | Setzt die horizontale Skalierung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [setInvisible](#setInvisible-boolean-) | Setzt die Unsichtbarkeit des Textes. |
| [setLineSpacing](#setLineSpacing-float-) | <p> Setzt den Zeilenabstand des Textes. </p> |
| [setRenderingMode](#setRenderingMode-com.aspose.pdf.TextRenderingMode-) | Liefert oder setzt den Rendermodus des Textes. |
| [setRotation](#setRotation-double-) | Ermittelt oder legt den Rotationswinkel in Grad fest. |
| [setStrikeOut](#setStrikeOut-boolean-) | Setzt den Durchstrich für den Text, dargestellt durch das {@code TextFragment}-Objekt |
| [setStrokingColor](#setStrokingColor-com.aspose.pdf.Color-) | Liefert oder setzt Farb-Strich-Operationen beim Rendern von {@code TextFragment} (Textstrich, Rechteckrahmen). |
| [setSubscript](#setSubscript-boolean-) | Liest oder setzt Tiefstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [setSuperscript](#setSuperscript-boolean-) | Liest oder setzt Hochstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt. |
| [setUnderline](#setUnderline-boolean-) | Setzt die Unterstreichung für den Text, dargestellt durch das {@code TextFragment}-Objekt |
| [setWordSpacing](#setWordSpacing-float-) | Setzt den Wortabstand des Textes. |

### TextFragmentState {#TextFragmentState-com.aspose.pdf.TextFragment-}
Initialisiert eine neue Instanz des {@code TextFragmentState}-Objekts mit dem angegebenen {@code TextFragment}-Objekt. Diese {@code TextFragmentState}-Initialisierung wird nicht unterstützt. TextFragmentState ist nur über die {@code TextFragment.TextState}-Eigenschaft verfügbar.

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-}
<p> Übernimmt Einstellungen von einem anderen textState </p>

### applyChangesFrom {#applyChangesFrom-com.aspose.pdf.TextState-boolean-}
Übernimmt Einstellungen von einem anderen textState

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Setzt die Hintergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
Wert Color-Objekt

### getCharacterSpacing {#getCharacterSpacing--}
```
public float getCharacterSpacing()
```

Liefert den Zeichenabstand des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Returns:**
float-Wert

### getCoordinateOrigin {#getCoordinateOrigin--}
```
public CoordinateOrigin getCoordinateOrigin()
```

Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden.

**Returns:**
CoordinateOrigin-Element

### getDrawTextRectangleBorder {#getDrawTextRectangleBorder--}
```
public boolean getDrawTextRectangleBorder()
```

Liefert das Flag, ob der Textrechteckrahmen gezeichnet wird.

**Returns:**
boolescher Wert

### getFont {#getFont--}
```
public Font getFont()
```

Liefert die Schriftart des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
Schriftwert

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Liefert die Schriftgröße des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
float-Wert

### getFontStyle {#getFontStyle--}
```
public int getFontStyle()
```

Setzt den Schriftstil des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
FontStyles-Element @see FontStyles

### getForegroundColor {#getForegroundColor--}
```
public Color getForegroundColor()
```

Liefert die Vordergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
Color-Objekt

### getFormattingOptions {#getFormattingOptions--}
```
public TextFormattingOptions getFormattingOptions()
```

Liefert oder setzt Formatierungsoptionen. Das Setzen der Optionen ist nur in Generatorszenarien wirksam.

**Returns:**
Instanz von TextFormattingOptions

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

<p> Liefert die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None entspricht HorizontalAlignment.Left. Hinweis: Die Eigenschaft TextFragmentState.VerticalAlignment funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. </p>

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public float getHorizontalScaling()
```

Liefert die horizontale Skalierung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

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

Liefert oder setzt den Rendermodus des Textes.

**Returns:**
Element TextRenderingMode

### getRotation {#getRotation--}
```
public double getRotation()
```

Ermittelt oder legt den Rotationswinkel in Grad fest.

**Returns:**
double-Wert

### getStrokingColor {#getStrokingColor--}
```
public Color getStrokingColor()
```

Liefert oder setzt Farb-Strich-Operationen beim Rendern von {@code TextFragment} (Textstrich, Rechteckrahmen).

**Returns:**
Color-Instanz

### getTabStops {#getTabStops--}
```
public TabStops getTabStops()
```

<p> Erhält Tabstopps für den Text. </p> <hr> <p> Hinweis: Die Tabstopps‑Eigenschaft funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. Tabstopps können während der {@code TextFragment}-Initialisierung hinzugefügt werden. Tabstopps müssen vor dem Text erstellt werden. </p>

**Returns:**
TabStops-Objekt

### getTextHeight {#getTextHeight--}
```
public float getTextHeight()
```

Ermittelt die Texthöhe, dargestellt durch das {@code TextFragment}-Objekt

**Returns:**
float-Wert

### getWordSpacing {#getWordSpacing--}
```
public float getWordSpacing()
```

Ermittelt den Wortabstand des Textes.

**Returns:**
float-Wert

### isFitRectangle {#isFitRectangle-java.lang.String-com.aspose.pdf.Rectangle-}
Überprüft, ob die Eingabezeichenfolge innerhalb des definierten Rechtecks platziert werden kann.

### isInvisible {#isInvisible--}
```
public boolean isInvisible()
```

Ermittelt die Unsichtbarkeit des Textes.

**Returns:**
boolescher Wert

### isStrikeOut {#isStrikeOut--}
```
public boolean isStrikeOut()
```

Liest oder setzt Durchstreichung für den Text, dargestellt durch das {@link TextFragment}-Objekt

**Returns:**
boolescher Wert

### isSubscript {#isSubscript--}
```
public boolean isSubscript()
```

Liest oder setzt Tiefstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Returns:**
boolescher Wert

### isSuperscript {#isSuperscript--}
```
public boolean isSuperscript()
```

Liest oder setzt Hochstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Returns:**
Wert boolescher Wert

### isUnderline {#isUnderline--}
```
public boolean isUnderline()
```

Liest oder setzt Unterstreichung für den Text, dargestellt durch das {@link TextFragment}-Objekt

**Returns:**
boolescher Wert

### measureHeight {#measureHeight-char-}
```
public final double measureHeight(char character)
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

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Setzt die Hintergrundfarbe des Textes, dargestellt durch das TextFragment-Objekt

### setCharacterSpacing {#setCharacterSpacing-float-}
```
public void setCharacterSpacing(float value)
```

Setzt den Zeichenabstand des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setCoordinateOrigin {#setCoordinateOrigin-com.aspose.pdf.CoordinateOrigin-}
Ermittelt oder setzt den Text-CoordinateOrigin. Wenn CoordinateOrigin Descender ist, entspricht die Y-Koordinate des Textes dem tiefsten Punkt der Schrift. Wenn CoordinateOrigin BaseLine ist, entspricht die Y-Koordinate des Textes der Grundlinie der Schrift. Der Standardwert ist Descender. Wenn der Descent-Wert der Schrift zu groß ist, kann der Text höher als andere Schriften gerendert werden. In diesem Fall kann CoordinateOrigin BaseLine für eine bessere Textdarstellung ausgewählt werden.

### setDrawTextRectangleBorder {#setDrawTextRectangleBorder-boolean-}
```
public void setDrawTextRectangleBorder(boolean value)
```

Setzt das Flag, ob der Rahmen des Textrechtecks gezeichnet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setFont {#setFont-com.aspose.pdf.Font-}
Setzt die Schriftart des Textes, dargestellt durch das {@code TextFragment}-Objekt

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Setzt die Schriftgröße des Textes, dargestellt durch das {@code TextFragment}-Objekt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setFontStyle {#setFontStyle-int-}
```
public void setFontStyle(int value)
```

Setzt den Schriftstil des Textes, dargestellt durch das {@link TextFragment}-Objekt

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see FontStyles |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Setzt die Vordergrundfarbe des Textes, dargestellt durch das {@code TextFragment}-Objekt

### setFormattingOptions {#setFormattingOptions-com.aspose.pdf.TextFormattingOptions-}
Liefert oder setzt Formatierungsoptionen. Das Setzen der Optionen ist nur in Generatorszenarien wirksam.

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
<p> Setzt die horizontale Ausrichtung für den Text. </p> <hr> <p> HorizontalAlignment.None entspricht HorizontalAlignment.Left. Hinweis: Die TextFragmentState.VerticalAlignment‑Eigenschaft funktioniert nur in Szenarien zur Neuerstellung von Dokumenten. </p>

### setHorizontalScaling {#setHorizontalScaling-float-}
```
public void setHorizontalScaling(float value)
```

Setzt die horizontale Skalierung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setInvisible {#setInvisible-boolean-}
```
public void setInvisible(boolean value)
```

Setzt die Unsichtbarkeit des Textes.

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
Liefert oder setzt den Rendermodus des Textes.

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Ermittelt oder legt den Rotationswinkel in Grad fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

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
Liefert oder setzt Farb-Strich-Operationen beim Rendern von {@code TextFragment} (Textstrich, Rechteckrahmen).

### setSubscript {#setSubscript-boolean-}
```
public void setSubscript(boolean value)
```

Liest oder setzt Tiefstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSuperscript {#setSuperscript-boolean-}
```
public void setSuperscript(boolean value)
```

Liest oder setzt Hochstellung des Textes, dargestellt durch das {@code TextFragment}-Objekt.

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
