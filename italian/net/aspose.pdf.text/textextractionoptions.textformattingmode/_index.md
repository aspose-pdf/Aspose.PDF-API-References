---
title: Enum TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode enum. Defines different modes which can be used while converting pdf document into text. See TextDevice class
type: docs
weight: 10900
url: /it/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## Enumerazione TextExtractionOptions.TextFormattingMode

Definisce diversi modi che possono essere utilizzati durante la conversione di un documento pdf in testo. Vedi !:classe TextDevice.

```csharp
public enum TextFormattingMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Pure | `0` | Rappresenta il contenuto pdf con un po' di routine di formattazione. |
| Raw | `1` | Rappresenta il contenuto pdf così com'è, cioè senza formattazione. |
| Flatten | `2` | Rappresenta il contenuto pdf posizionando i frammenti di testo in base alle loro coordinate. È fondamentalmente simile alla modalità "Raw". Ma mentre "Raw" si concentra sulla conservazione della struttura dei frammenti di testo (operatori) in un documento, "Flatten" si concentra sul mantenere il testo nell'ordine in cui viene letto. |
| MemorySaving | `3` | Estrazione con risparmio di memoria. È quasi identica alla modalità 'Raw' ma funziona leggermente più veloce e utilizza meno memoria. |

### Vedi Anche

* classe [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)