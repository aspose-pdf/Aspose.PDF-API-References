---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar alternativ för textutdragning"
type: docs
weight: 5060
url: /sv/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Representerar alternativ för textutdragning

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Initierar en ny instans av {@code TextExtractionOptions}-objektet för det angivna textformateringsläget. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Hämtar formateringsläge. |
| [getScaleFactor](#getScaleFactor--) | Hämtar faktorn som kommer att tillämpas för att skala teckenstorlek vid extraktion i rent läge. En lägre inställning ger fler mellanslag i den extraherade texten. Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. |
| [setFormattingMode](#setFormattingMode-int-) | Ställer in formateringsläge. |
| [setScaleFactor](#setScaleFactor-double-) | Ställer in faktorn som kommer att tillämpas för att skala teckenstorlek vid extraktion i rent läge. En lägre inställning ger fler mellanslag i den extraherade texten (från 1 till 10). Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Initierar en ny instans av {@code TextExtractionOptions}-objektet för det angivna textformateringsläget.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattingMode |  | Värde för textformateringsläge. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Hämtar formateringsläge.

**Returns:**
TextFormattingMode‑värde @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Hämtar faktorn som kommer att tillämpas för att skala teckenstorlek vid extraktion i rent läge. En lägre inställning ger fler mellanslag i den extraherade texten. Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt.

**Returns:**
double-värde

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Ställer in formateringsläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TextFormattingMode‑värde @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Ställer in faktorn som kommer att tillämpas för att skala teckenstorlek vid extraktion i rent läge. En lägre inställning ger fler mellanslag i den extraherade texten (från 1 till 10). Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |
