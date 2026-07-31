---
title: "Enum DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.DocSaveOptionsRecognitionMode. Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi."
type: docs
weight: 3890
url: /it/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

Consente di controllare come un documento PDF viene convertito in un documento di elaborazione testi.

```csharp
public enum RecognitionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Textbox | `0` | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale del file PDF, ma l'editabilità del documento risultante potrebbe essere limitata. |
| Flow | `1` | Modalità di riconoscimento completo, il motore esegue il raggruppamento e l'analisi multi-livello per ripristinare l'intento dell'autore del documento originale e produrre un documento massimamente modificabile. Lo svantaggio è che il documento di output potrebbe apparire diverso dal file PDF originale. |
| EnhancedFlow | `2` | Una modalità Flow alternativa che supporta il riconoscimento delle tabelle. |

## Osservazioni

Usa la modalità Textbox quando il documento risultante non sarà modificato intensamente. Le caselle di testo sono facili da modificare quando non c'è molto da fare.

Usa la modalità Flow quando il documento di output necessita di ulteriori modifiche. I paragrafi e le linee di testo nella modalità flow consentono una facile modifica del testo, ma gli oggetti di formattazione non supportati appariranno peggio rispetto alla modalità Textbox.

### Vedi anche

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


