---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce diverse modalità che possono essere utilizzate durante la conversione di un documento pdf in testo. Vedi la classe {@code TextDevice}."
type: docs
weight: 5070
url: /it/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Definisce diverse modalità che possono essere utilizzate durante la conversione di un documento pdf in testo. Vedi la classe {@code TextDevice}.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Flatten](#Flatten) | Rappresenta il contenuto PDF con frammenti di testo posizionati secondo le loro coordinate. È fondamentalmente simile alla modalità "Raw". Ma mentre "Raw" si concentra sul preservare la struttura dei frammenti di testo (operatori) in un documento, "Flatten" si concentra sul mantenere il testo nell'ordine in cui viene letto. |
| [MemorySaving](#MemorySaving) | Estrazione con risparmio di memoria. È quasi identica alla modalità 'Raw' ma funziona leggermente più veloce e utilizza meno memoria. |
| [Pure](#Pure) | Rappresenta il contenuto PDF con un po' di routine di formattazione. |
| [Raw](#Raw) | Rappresenta il contenuto PDF così com'è, cioè senza formattazione. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Rappresenta il contenuto PDF con frammenti di testo posizionati secondo le loro coordinate. È fondamentalmente simile alla modalità "Raw". Ma mentre "Raw" si concentra sul preservare la struttura dei frammenti di testo (operatori) in un documento, "Flatten" si concentra sul mantenere il testo nell'ordine in cui viene letto.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Estrazione con risparmio di memoria. È quasi identica alla modalità 'Raw' ma funziona leggermente più veloce e utilizza meno memoria.

### Pure {#Pure}
```
public static final int Pure
```

Rappresenta il contenuto PDF con un po' di routine di formattazione.

### Raw {#Raw}
```
public static final int Raw
```

Rappresenta il contenuto PDF così com'è, cioè senza formattazione.
