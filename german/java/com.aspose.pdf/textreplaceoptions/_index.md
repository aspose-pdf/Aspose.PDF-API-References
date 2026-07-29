---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen zum Ersetzen von Text dar"
type: docs
weight: 5250
url: /de/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Stellt Optionen zum Ersetzen von Text dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die angegebene Aktion nach dem Ersetzen. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Liest oder legt den Wert des Zeilenabstands fest, der verwendet wird, wenn die Ersetzungsanpassung erzwungen wird, um eine neue Textzeile zu erzeugen. Der erwartete Wert ist ein Multiplikator der Schriftgröße des ersetzten Textes. Standard ist 1,2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Liest oder setzt die Richtlinie zum Anpassen der Schriftgröße, damit sie innerhalb der durch {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}) definierten Grenzen passt. |
| [getLeftAdjustment](#getLeftAdjustment--) | Liest die Anpassung der linken Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Liest oder setzt das Rechteck, um den Text nach dem Ersetzen anzupassen. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Liest eine Aktion, die nach dem Ersetzen eines Textfragments zu einer kürzeren Form ausgeführt wird. |
| [getReplaceScope](#getReplaceScope--) | Liest den Geltungsbereich, in dem die Ersetzungsoperation angewendet wird |
| [getRightAdjustment](#getRightAdjustment--) | Setzt oder liest die Anpassung der rechten Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Liest oder setzt einen Wert, der angibt, ob unterschiedliche Absätze beim Anpassen des Textes auf der Seite nach einer Text-Ersetzung ignoriert werden sollen. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Liest oder legt den Wert des Zeilenabstands fest, der verwendet wird, wenn die Ersetzungsanpassung erzwungen wird, um eine neue Textzeile zu erzeugen. Der erwartete Wert ist ein Multiplikator der Schriftgröße des ersetzten Textes. Standard ist 1,2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Liest oder setzt die Richtlinie zum Anpassen der Schriftgröße, damit sie innerhalb der durch TextReplaceOptions.Rectangle definierten Grenzen passt ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Liest oder setzt einen Wert, der angibt, ob unterschiedliche Absätze beim Anpassen des Textes auf der Seite nach einer Text-Ersetzung ignoriert werden sollen. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Setzt oder liest die Anpassung der linken Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Liest oder setzt das Rechteck, um den Text nach dem Ersetzen anzupassen. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Setzt eine Aktion, die nach dem Ersetzen eines Textfragments zu einer kürzeren Form ausgeführt wird. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Setzt den Geltungsbereich, in dem die Ersetzungsoperation angewendet wird |
| [setRightAdjustment](#setRightAdjustment-double-) | Setzt die Anpassung der rechten Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die angegebene Aktion nach dem Ersetzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Anpassung |  | ReplaceAdjustment-Objekt. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Initialisiert eine neue Instanz des {@code TextReplaceOptions}-Objekts für die Standardanpassung und den Standardbereich: ReplaceAdjustment.None und Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Liest oder legt den Wert des Zeilenabstands fest, der verwendet wird, wenn die Ersetzungsanpassung erzwungen wird, um eine neue Textzeile zu erzeugen. Der erwartete Wert ist ein Multiplikator der Schriftgröße des ersetzten Textes. Standard ist 1,2.

**Returns:**
double-Wert

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Liest oder setzt die Richtlinie zum Anpassen der Schriftgröße, damit sie innerhalb der durch {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}) definierten Grenzen passt.

**Returns:**
FontSizeAdjustment-Element

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Liest die Anpassung der linken Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double-Wert

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Liest oder setzt das Rechteck, um den Text nach dem Ersetzen anzupassen.

**Returns:**
Rechteck-Instanz

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Liest eine Aktion, die nach dem Ersetzen eines Textfragments zu einer kürzeren Form ausgeführt wird.

**Returns:**
ReplaceAdjustment-Element @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Liest den Geltungsbereich, in dem die Ersetzungsoperation angewendet wird

**Returns:**
int-Wert @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Setzt oder liest die Anpassung der rechten Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
double-Wert

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Liest oder setzt einen Wert, der angibt, ob unterschiedliche Absätze beim Anpassen des Textes auf der Seite nach einer Text-Ersetzung ignoriert werden sollen.

**Returns:**
boolescher Wert

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Liest oder legt den Wert des Zeilenabstands fest, der verwendet wird, wenn die Ersetzungsanpassung erzwungen wird, um eine neue Textzeile zu erzeugen. Der erwartete Wert ist ein Multiplikator der Schriftgröße des ersetzten Textes. Standard ist 1,2.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Liest oder setzt die Richtlinie zum Anpassen der Schriftgröße, damit sie innerhalb der durch TextReplaceOptions.Rectangle definierten Grenzen passt ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Liest oder setzt einen Wert, der angibt, ob unterschiedliche Absätze beim Anpassen des Textes auf der Seite nach einer Text-Ersetzung ignoriert werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Setzt oder liest die Anpassung der linken Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Liest oder setzt das Rechteck, um den Text nach dem Ersetzen anzupassen.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Setzt eine Aktion, die nach dem Ersetzen eines Textfragments zu einer kürzeren Form ausgeführt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ReplaceAdjustment-Element @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Setzt den Geltungsbereich, in dem die Ersetzungsoperation angewendet wird

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Setzt die Anpassung der rechten Position für ersetzten Text bei Verwendung von TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
