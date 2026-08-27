---
title: "HtmlSaveOptions.AntialiasingProcessingType"
linktitle: "HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questo enum descrive le possibili misure di antialiasing durante la conversione"
type: docs
weight: 2000
url: /it/java/com.aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.AntialiasingProcessingType

```
public static final class HtmlSaveOptions.AntialiasingProcessingType extends com.aspose.ms.System.Enum
```

Questo enum descrive le possibili misure di antialiasing durante la conversione

## Campi

| Campo | Descrizione |
| --- | --- |
| [NoAdditionalProcessing](#NoAdditionalProcessing) | Nessuna elaborazione antialiasing speciale in uso. Questa è un'opzione ottimale per la stragrande maggioranza dei documenti e non richiede tempo aggiuntivo durante la conversione. |
| [TryCorrectResultHtml](#TryCorrectResultHtml) | In tal caso il convertitore tenta di individuare le aree con elementi grafici di sfondo adiacenti e correggere l'HTML risultante in modo appropriato. Questa opzione consente di migliorare il risultato dell'esportazione per i documenti che contengono sfondi composti da diversi elementi grafici adiacenti (per questo tipo di documenti i renderer PDF, ad es. Acrobat Reader, solitamente cercano di smussare i confini degli elementi durante il rendering). Con questa opzione il convertitore imita quel comportamento dei renderer PDF. L'opzione permette di migliorare il layout del risultato dell'esportazione per alcuni documenti specifici (che utilizzano sfondi composti), ma richiede tempo aggiuntivo per l'elaborazione (di solito circa il 10‑15 % di tempo in più). Pertanto l'uso di questa modalità nei casi generali non è consigliato. |

### NoAdditionalProcessing {#NoAdditionalProcessing}
```
public static final int NoAdditionalProcessing
```

Nessuna elaborazione antialiasing speciale in uso. Questa è un'opzione ottimale per la stragrande maggioranza dei documenti e non richiede tempo aggiuntivo durante la conversione.

### TryCorrectResultHtml {#TryCorrectResultHtml}
```
public static final int TryCorrectResultHtml
```

In tal caso il convertitore tenta di individuare le aree con elementi grafici di sfondo adiacenti e correggere l'HTML risultante in modo appropriato. Questa opzione consente di migliorare il risultato dell'esportazione per i documenti che contengono sfondi composti da diversi elementi grafici adiacenti (per questo tipo di documenti i renderer PDF, ad es. Acrobat Reader, solitamente cercano di smussare i confini degli elementi durante il rendering). Con questa opzione il convertitore imita quel comportamento dei renderer PDF. L'opzione permette di migliorare il layout del risultato dell'esportazione per alcuni documenti specifici (che utilizzano sfondi composti), ma richiede tempo aggiuntivo per l'elaborazione (di solito circa il 10‑15 % di tempo in più). Pertanto l'uso di questa modalità nei casi generali non è consigliato.
