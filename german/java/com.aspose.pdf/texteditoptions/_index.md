---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Beschreibt Optionen für Textbearbeitungsoperationen."
type: docs
weight: 4970
url: /de/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Beschreibt Optionen für Textbearbeitungsoperationen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts für den angegebenen Textumordnungsmodus. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Liest den Wert, der die Verwendung von Sprachtransformation beim Hinzufügen oder Bearbeiten von Text erlaubt. true – Sprachtransformation wird bei Bedarf angewendet (Standardwert). false – Sprachtransformation wird NICHT angewendet. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Liest den Modus für die Verarbeitung des Beschneidungspfads des bearbeiteten Textes. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Liest den Modus, der das Verhalten für Szenarien des Schriftartenaustauschs definiert. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Liest den Modus, der das Verhalten für Szenarien der Sprachtransformation definiert. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Liest den Modus, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten. |
| [getReplacementFont](#getReplacementFont--) | Liest oder setzt die Schriftart, die zum Ersetzen verwendet wird, wenn die Benutzerschriftart das erforderliche Zeichen nicht enthält. |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Liest oder setzt den Wert, der die Suche nach Textunterstreichungen auf der Seite des Quelldokuments erlaubt. <p> (Veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Setzt den Wert, der die Verwendung von Sprachtransformation beim Hinzufügen oder Bearbeiten von Text erlaubt. true – Sprachtransformation wird bei Bedarf angewendet (Standardwert). false – Sprachtransformation wird NICHT angewendet. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Liest den Modus für die Verarbeitung des Beschneidungspfads des bearbeiteten Textes. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Setzt den Modus, der das Verhalten für Szenarien des Schriftartenaustauschs definiert. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Setzt den Modus, der das Verhalten für Szenarien der Sprachtransformation definiert. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Setzt den Modus, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Liest oder setzt die Schriftart, die zum Ersetzen verwendet wird, wenn die Benutzerschriftart das erforderliche Zeichen nicht enthält. |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Liest oder setzt den Wert, der die Suche nach Textunterstreichungen auf der Seite des Quelldokuments erlaubt. <p> (Veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts für den angegebenen Textumordnungsmodus. / * / *

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Initialisiert eine neue Instanz des {@code TextEditOptions} Objekts mit Standardoptionen. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Liest den Wert, der die Verwendung von Sprachtransformation beim Hinzufügen oder Bearbeiten von Text erlaubt. true – Sprachtransformation wird bei Bedarf angewendet (Standardwert). false – Sprachtransformation wird NICHT angewendet.

**Returns:**
boolescher Wert

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Liest den Modus für die Verarbeitung des Beschneidungspfads des bearbeiteten Textes.

**Returns:**
ClippingPathsProcessingMode Element

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Liest den Modus, der das Verhalten für Szenarien des Schriftartenaustauschs definiert.

**Returns:**
FontReplace Wert @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Liest den Modus, der das Verhalten für Szenarien der Sprachtransformation definiert.

**Returns:**
LanguageTransformation Wert @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Liest den Modus, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten.

**Returns:**
NoCharacterAction Wert @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Liest oder setzt die Schriftart, die zum Ersetzen verwendet wird, wenn die Benutzerschriftart das erforderliche Zeichen nicht enthält.

**Returns:**
Font Instanz

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Liest oder setzt den Wert, der die Suche nach Textunterstreichungen auf der Seite des Quelldokuments erlaubt. <p> (Veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. </p>

**Returns:**
boolescher Wert

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Setzt den Wert, der die Verwendung von Sprachtransformation beim Hinzufügen oder Bearbeiten von Text erlaubt. true – Sprachtransformation wird bei Bedarf angewendet (Standardwert). false – Sprachtransformation wird NICHT angewendet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Liest den Modus für die Verarbeitung des Beschneidungspfads des bearbeiteten Textes.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Setzt den Modus, der das Verhalten für Szenarien des Schriftartenaustauschs definiert.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Setzt den Modus, der das Verhalten für Szenarien der Sprachtransformation definiert.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Setzt den Modus, der das Verhalten definiert, falls Schriftarten die angeforderten Zeichen nicht enthalten.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Liest oder setzt die Schriftart, die zum Ersetzen verwendet wird, wenn die Benutzerschriftart das erforderliche Zeichen nicht enthält.

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Liest oder setzt den Wert, der die Suche nach Textunterstreichungen auf der Seite des Quelldokuments erlaubt. <p> (Veraltet) Bitte verwenden Sie stattdessen TextSearchOptions.SearchForTextRelatedGraphics. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
