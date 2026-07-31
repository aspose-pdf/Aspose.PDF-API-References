---
title: "Enum TextExtractionOptions.TextFormattingMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.Text.TextExtractionOptionsTextFormattingMode. Definisce diversi modi che possono essere usati durante la conversione di un documento pdf in testo. Vedi la classe TextDevice"
type: docs
weight: 11080
url: /it/net/aspose.pdf.text/textextractionoptions.textformattingmode/
---
## TextExtractionOptions.TextFormattingMode enumeration

Definisce diversi modi che possono essere usati durante la conversione di un documento pdf in testo. Vedi la classe !:TextDevice.

```csharp
public enum TextFormattingMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Pure | `0` | Rappresenta il contenuto pdf con una piccola serie di routine di formattazione. |
| Raw | `1` | Rappresenta il contenuto pdf così com'è, cioè senza formattazione. |
| Flatten | `2` | Rappresenta il contenuto pdf posizionando i frammenti di testo secondo le loro coordinate. È fondamentalmente simile alla modalità "Raw". Tuttavia, mentre "Raw" si concentra sul preservare la struttura dei frammenti di testo (operatori) in un documento, "Flatten" si concentra sul mantenere il testo nell'ordine in cui viene letto. |
| MemorySaving | `3` | Estrazione con risparmio di memoria. È quasi identica alla modalità 'Raw' ma funziona leggermente più veloce e utilizza meno memoria. |

### Vedi anche

* class [TextExtractionOptions](../textextractionoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


