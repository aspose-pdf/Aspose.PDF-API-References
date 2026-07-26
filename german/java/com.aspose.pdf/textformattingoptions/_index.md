---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen für die Textformatierung dar"
type: docs
weight: 5080
url: /de/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Stellt Optionen für die Textformatierung dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Initialisiert eine neue Instanz des {@code TextFormattingOptions}-Objekts mit undefiniertem Zeilenumbruchmodus. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Initialisiert eine neue Instanz des {@code TextFormattingOptions}-Objekts für den angegebenen Zeilenumbruchmodus. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Ermittelt oder legt den Einzug der ersten Zeile fest. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Ermittelt oder legt das Trennzeichen fest, das im Silbentrennungsprozess verwendet wird. </p><hr> Um das Zeichnen von Trennstrichen zu entfernen (während das Umbruchverfahren weiterhin aktiv ist), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty. |
| [getLineSpacing](#getLineSpacing--) | Ermittelt den Zeilenabstandsmodus. Standardwert ist LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Ermittelt oder legt den Einzug der nachfolgenden Zeilen fest. |
| [getWrapMode](#getWrapMode--) | Ermittelt den Zeilenumbruchmodus. Standardwert ist WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Ermittelt oder legt den Einzug der ersten Zeile fest. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Ermittelt oder legt das Trennzeichen fest, das im Silbentrennungsprozess verwendet wird. </p><hr> Um das Zeichnen von Trennstrichen zu entfernen (während das Umbruchverfahren weiterhin aktiv ist), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty. |
| [setLineSpacing](#setLineSpacing-int-) | Legt den Zeilenabstandsmodus fest. Standardwert ist LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Ermittelt oder legt den Einzug der nachfolgenden Zeilen fest. |
| [setWrapMode](#setWrapMode-int-) | Legt den Zeilenumbruchmodus fest. Standardwert ist WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Initialisiert eine neue Instanz des {@code TextFormattingOptions}-Objekts mit undefiniertem Zeilenumbruchmodus.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Initialisiert eine neue Instanz des {@code TextFormattingOptions}-Objekts für den angegebenen Zeilenumbruchmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| wrapMode |  | Wortumbruchmodus. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Ermittelt oder legt den Einzug der ersten Zeile fest.

**Returns:**
float-Wert

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Ermittelt oder legt das Trennzeichen fest, das im Silbentrennungsprozess verwendet wird. </p><hr> Um das Zeichnen von Trennstrichen zu entfernen (während das Umbruchverfahren weiterhin aktiv ist), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty.

**Returns:**
String Wert

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Ermittelt den Zeilenabstandsmodus. Standardwert ist LineSpacingMode.FontSize

**Returns:**
int-Wert @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Ermittelt oder legt den Einzug der nachfolgenden Zeilen fest.

**Returns:**
float-Wert

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Ermittelt den Zeilenumbruchmodus. Standardwert ist WordWrapMode.NoWrap

**Returns:**
WordWrapMode-Wert @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Ermittelt oder legt den Einzug der ersten Zeile fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Ermittelt oder legt das Trennzeichen fest, das im Silbentrennungsprozess verwendet wird. </p><hr> Um das Zeichnen von Trennstrichen zu entfernen (während das Umbruchverfahren weiterhin aktiv ist), setzen Sie für HyphenSymbol eine leere Zeichenfolge string.Empty.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Legt den Zeilenabstandsmodus fest. Standardwert ist LineSpacingMode.FontSize

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Ermittelt oder legt den Einzug der nachfolgenden Zeilen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Legt den Zeilenumbruchmodus fest. Standardwert ist WordWrapMode.NoWrap

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | WordWrapMode-Wert @see WordWrapMode |
