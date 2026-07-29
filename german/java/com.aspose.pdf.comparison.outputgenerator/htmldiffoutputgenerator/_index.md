---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse zur Erzeugung einer HTML-Darstellung von Textunterschieden dar. Gelöschte Zeilenumbrüche werden durch das Absatzzeichen - angezeigt."
type: docs
weight: 10
url: /de/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Stellt eine Klasse zur Erzeugung einer HTML-Darstellung von Textunterschieden dar. Gelöschte Zeilenumbrüche werden durch das Absatzzeichen - angezeigt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Erstellt eine Instanz der {@link HtmlDiffOutputGenerator}-Klasse. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Erstellt eine Instanz der {@link HtmlDiffOutputGenerator}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [generateOutput1](#generateOutput1-java.util.List-) | Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Interne Methode |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Delete‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Equal‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Insert‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Lese oder setze den text-decoration: line-through‑Stil für die Delete‑Operation. Der Standardwert ist {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Delete‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Equal‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Liest und setzt die CSS‑Stil‑Zeichenkette für die Insert‑Operation. Beispiel: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Lese oder setze den text-decoration: line-through‑Stil für die Delete‑Operation. Der Standardwert ist {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Erstellt eine Instanz der {@link HtmlDiffOutputGenerator}-Klasse.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Erstellt eine Instanz der {@link HtmlDiffOutputGenerator}-Klasse.

### generateOutput {#generateOutput-java.util.List-}
Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei.

### generateOutput1 {#generateOutput1-java.util.List-}
Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Erzeugt die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Interne Methode

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Liest und setzt die CSS‑Stil‑Zeichenkette für die Delete‑Operation. Beispiel: color: #003300; background-color: #ccff66;

**Returns:**
String Wert

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Liest und setzt die CSS‑Stil‑Zeichenkette für die Equal‑Operation. Beispiel: color: #003300; background-color: #ccff66;

**Returns:**
String Wert

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Liest und setzt die CSS‑Stil‑Zeichenkette für die Insert‑Operation. Beispiel: color: #003300; background-color: #ccff66;

**Returns:**
String Wert

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Lese oder setze den text-decoration: line-through‑Stil für die Delete‑Operation. Der Standardwert ist {@code False}.

**Returns:**
boolescher Wert

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Liest und setzt die CSS‑Stil‑Zeichenkette für die Delete‑Operation. Beispiel: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Liest und setzt die CSS‑Stil‑Zeichenkette für die Equal‑Operation. Beispiel: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Liest und setzt die CSS‑Stil‑Zeichenkette für die Insert‑Operation. Beispiel: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Lese oder setze den text-decoration: line-through‑Stil für die Delete‑Operation. Der Standardwert ist {@code False}.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
