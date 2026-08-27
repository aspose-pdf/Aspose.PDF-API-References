---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Texteigenschaftseinstellungen für Textstruktur-Elemente und TaggedContent (ITextElement, ITaggedContent) dar."
type: docs
weight: 120
url: /de/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Stellt die Texteigenschaftseinstellungen für Textstruktur-Elemente und TaggedContent (ITextElement, ITaggedContent) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Standardkonstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createTextState](#createTextState--) | Textzustand erstellen |
| [getBackgroundColor](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code BackgroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getCharacterSpacing](#getCharacterSpacing--) | Liest oder setzt den Zeichenabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code CharacterSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getFont](#getFont--) | Liest oder setzt die Schriftart des Textes. Kann null sein. Verwenden Sie null, um die {@code Font}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getFontSize](#getFontSize--) | Liest oder setzt die Schriftgröße des Textes. Kann null sein. Verwenden Sie null, um die {@code FontSize}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getFontStyle](#getFontStyle--) | Liest oder setzt den Schriftstil des Textes. Kann null sein. Verwenden Sie null, um die {@code FontStyle}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getForegroundColor](#getForegroundColor--) | Liest oder setzt die Vordergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code ForegroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Liest oder setzt die horizontale Ausrichtung eines Absatzes |
| [getHorizontalScaling](#getHorizontalScaling--) | Liest oder setzt die horizontale Skalierung des Textes. Kann null sein. Verwenden Sie null, um die {@code HorizontalScaling}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getLineSpacing](#getLineSpacing--) | Liest oder setzt den Zeilenabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code LineSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getMarginInfo](#getMarginInfo--) | Liest oder setzt den Rand für das Block-Strukturelement. |
| [getStrikeOut](#getStrikeOut--) | Liest oder setzt Durchstreichen für den Text. Kann null sein. Verwenden Sie null, um die {@code StrikeOut}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getSubscript](#getSubscript--) | Liest oder setzt Tiefstellung des Textes. Kann null sein. Verwenden Sie null, um die {@code Subscript}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getSuperscript](#getSuperscript--) | Liest oder setzt Hochstellung des Textes. Kann null sein. Verwenden Sie null, um die {@code Superscript}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getUnderline](#getUnderline--) | Liest oder setzt Unterstreichung für den Text. Kann null sein. Verwenden Sie null, um die {@code Underline}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [getVerticalAlignment](#getVerticalAlignment--) | Liest oder setzt die vertikale Ausrichtung eines Absatzes |
| [getWordSpacing](#getWordSpacing--) | Liest oder setzt den Wortabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code WordSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte erscheint. Standard ist false. |
| [isInLineParagraph](#isInLineParagraph--) | Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false. |
| [isInNewPage](#isInNewPage--) | Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false. |
| [isKeptWithNext](#isKeptWithNext--) | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Liest oder setzt die Hintergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code BackgroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Liest oder setzt den Zeichenabstand des Textes. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Liest oder setzt die Schriftart des Textes. Kann null sein. Verwenden Sie null, um die {@code Font}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Liest oder setzt die Schriftgröße des Textes. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Liest oder setzt den Schriftstil des Textes. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Liest oder setzt die Vordergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code ForegroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Liest oder setzt die horizontale Skalierung des Textes. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Liest oder setzt den Zeilenabstand des Textes. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Liest oder setzt den Rand für das Block-Strukturelement. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Liest oder setzt Durchstreichung für den Text. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Liest oder setzt die Tiefstellung des Textes. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Liest oder setzt Hochstellung des Textes. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Liest oder setzt Unterstreichung für den Text. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Liest oder setzt den Wortabstand des Textes. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Elemente aktualisieren |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Standardkonstruktor

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Textzustand erstellen

**Returns:**
TextState-Instanz

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Liest oder setzt die Hintergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code BackgroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Color-Instanz

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Liest oder setzt den Zeichenabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code CharacterSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Float-Array

### getFont {#getFont--}
```
public final Font getFont()
```

Liest oder setzt die Schriftart des Textes. Kann null sein. Verwenden Sie null, um die {@code Font}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Font Instanz

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Liest oder setzt die Schriftgröße des Textes. Kann null sein. Verwenden Sie null, um die {@code FontSize}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Float-Array

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Liest oder setzt den Schriftstil des Textes. Kann null sein. Verwenden Sie null, um die {@code FontStyle}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Integer-Array

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Liest oder setzt die Vordergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code ForegroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Color-Instanz

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Liest oder setzt die horizontale Ausrichtung eines Absatzes

**Returns:**
HorizontalAlignment-Element

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Liest oder setzt die horizontale Skalierung des Textes. Kann null sein. Verwenden Sie null, um die {@code HorizontalScaling}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Float-Array

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Liest oder setzt den Zeilenabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code LineSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Float-Array

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Liest oder setzt den Rand für das Block-Strukturelement.

**Returns:**
MarginInfo-Instanz @deprecated Verwenden Sie die Methode IAdjustPosition.AdjustPosition(PositionSettings positionSettings), um Positionseinstellungen festzulegen.

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Liest oder setzt Durchstreichen für den Text. Kann null sein. Verwenden Sie null, um die {@code StrikeOut}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Boolean-Array

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Liest oder setzt Tiefstellung des Textes. Kann null sein. Verwenden Sie null, um die {@code Subscript}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Boolean-Array

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Liest oder setzt Hochstellung des Textes. Kann null sein. Verwenden Sie null, um die {@code Superscript}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Boolean-Array

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Liest oder setzt Unterstreichung für den Text. Kann null sein. Verwenden Sie null, um die {@code Underline}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Boolean-Array

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Liest oder setzt die vertikale Ausrichtung eines Absatzes

**Returns:**
VerticalAlignment-Element

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Liest oder setzt den Wortabstand des Textes. Kann null sein. Verwenden Sie null, um die {@code WordSpacing}-Eigenschaft vom übergeordneten Strukturelement zu erben.

**Returns:**
Float-Array

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob dieser Absatz in der nächsten Spalte erscheint. Standard ist false.

**Returns:**
Boolescher Wert

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Ruft ab oder legt fest, ob ein Absatz inline ist. Standard ist false.

**Returns:**
Boolescher Wert

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Ruft einen booleschen Wert ab oder legt ihn fest, der erzwingt, dass dieser Absatz auf einer neuen Seite erzeugt wird. Standard ist false.

**Returns:**
Boolescher Wert

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob der aktuelle Absatz zusammen mit dem nächsten Absatz auf derselben Seite bleibt. Standard ist false.

**Returns:**
Boolescher Wert

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Liest oder setzt die Hintergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code BackgroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Liest oder setzt den Zeichenabstand des Textes.

### setFont {#setFont-com.aspose.pdf.Font-}
Liest oder setzt die Schriftart des Textes. Kann null sein. Verwenden Sie null, um die {@code Font}-Eigenschaft vom übergeordneten Strukturelement zu erben.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Liest oder setzt die Schriftgröße des Textes.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Liest oder setzt den Schriftstil des Textes.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Liest oder setzt die Vordergrundfarbe des Textes. Kann null sein. Verwenden Sie null, um die {@code ForegroundColor}-Eigenschaft vom übergeordneten Strukturelement zu erben.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Liest oder setzt die horizontale Skalierung des Textes.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Liest oder setzt den Zeilenabstand des Textes.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Liest oder setzt den Rand für das Block-Strukturelement.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Liest oder setzt Durchstreichung für den Text.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Liest oder setzt die Tiefstellung des Textes.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Liest oder setzt Hochstellung des Textes.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Liest oder setzt Unterstreichung für den Text.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Liest oder setzt den Wortabstand des Textes.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Elemente aktualisieren
