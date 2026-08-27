---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Optionen für die Textextraktion dar"
type: docs
weight: 5060
url: /de/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Stellt Optionen für die Textextraktion dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Initialisiert eine neue Instanz des {@code TextExtractionOptions}-Objekts für den angegebenen Textformatierungsmodus. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Liefert den Formatierungsmodus. |
| [getScaleFactor](#getScaleFactor--) | Liefert den Faktor, der zur Skalierung der Schriftgröße während der Extraktion im reinen Modus angewendet wird. Ein niedrigerer Wert führt zu mehr Leerzeichen im extrahierten Text. Der Standardwert ist 1 – keine Skalierung; Wird der Wert auf Null gesetzt, wählt der Algorithmus die Skalierung automatisch. |
| [setFormattingMode](#setFormattingMode-int-) | Setzt den Formatierungsmodus. |
| [setScaleFactor](#setScaleFactor-double-) | Setzt den Faktor, der zur Skalierung der Schriftgröße während der Extraktion im reinen Modus angewendet wird. Ein niedrigerer Wert führt zu mehr Leerzeichen im extrahierten Text (von 1 bis 10). Der Standardwert ist 1 – keine Skalierung; Wird der Wert auf Null gesetzt, wählt der Algorithmus die Skalierung automatisch. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Initialisiert eine neue Instanz des {@code TextExtractionOptions}-Objekts für den angegebenen Textformatierungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattingMode |  | Wert des Textformatierungsmodus. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Liefert den Formatierungsmodus.

**Returns:**
TextFormattingMode‑Wert @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Liefert den Faktor, der zur Skalierung der Schriftgröße während der Extraktion im reinen Modus angewendet wird. Ein niedrigerer Wert führt zu mehr Leerzeichen im extrahierten Text. Der Standardwert ist 1 – keine Skalierung; Wird der Wert auf Null gesetzt, wählt der Algorithmus die Skalierung automatisch.

**Returns:**
double-Wert

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Setzt den Formatierungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TextFormattingMode‑Wert @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Setzt den Faktor, der zur Skalierung der Schriftgröße während der Extraktion im reinen Modus angewendet wird. Ein niedrigerer Wert führt zu mehr Leerzeichen im extrahierten Text (von 1 bis 10). Der Standardwert ist 1 – keine Skalierung; Wird der Wert auf Null gesetzt, wählt der Algorithmus die Skalierung automatisch.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |
