---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Der PDF/A-Standard verlangt, dass alle Schriftarten in das Dokument eingebettet werden. Diese Klasse enthält Flags für Fälle, in denen es nicht möglich ist, eine Schriftart einzubetten, weil diese Schriftart nicht vorhanden ist."
type: docs
weight: 1680
url: /de/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

Der PDF/A-Standard verlangt, dass alle Schriften in das Dokument eingebettet werden. Diese Klasse enthält Flags für Fälle, in denen es nicht möglich ist, eine Schrift einzubetten, weil diese Schrift auf dem Ziel-PC fehlt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Initialisiert eine neue Instanz der {@link FontEmbeddingOptions}-Klasse. Dieser Konstruktor setzt den Standardwert für die {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)})-Eigenschaft auf {@code }. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Gibt an, ob nicht eingebettete Schriftarten mit der Standard-Schriftart-Substitutionsstrategie ersetzt werden sollen. Standardmäßig false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Gibt an, ob nicht eingebettete Schriftarten mit der Standard-Schriftart-Substitutionsstrategie ersetzt werden sollen. Standardmäßig false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Initialisiert eine neue Instanz der {@link FontEmbeddingOptions}-Klasse. Dieser Konstruktor setzt den Standardwert für die {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)})-Eigenschaft auf {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Gibt an, ob nicht eingebettete Schriftarten mit der Standard-Schriftart-Substitutionsstrategie ersetzt werden sollen. Standardmäßig false;

**Returns:**
boolescher Wert

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Gibt an, ob nicht eingebettete Schriftarten mit der Standard-Schriftart-Substitutionsstrategie ersetzt werden sollen. Standardmäßig false;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
