---
title: "Enum EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.EpubSaveOptionsRecognitionMode. Quando un file PDF che di solito ha layout fisso viene convertito, il motore di conversione tenta di eseguire il raggruppamento e l'analisi multilevel per ripristinare l'intento originale dell'autore del documento e produrre il risultato in layout a flusso. Questa proprietà regola quella conversione per questo o quello metodo desiderabile di riconoscimento del contenuto"
type: docs
weight: 4190
url: /it/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

Quando un file PDF (che di solito ha un layout fisso) viene convertito, il motore di conversione tenta di eseguire il raggruppamento e l'analisi a più livelli per ripristinare l'intento originale dell'autore del documento e produrre il risultato in un layout a flusso. Questa proprietà regola quella conversione per questo o quello metodo desiderabile di riconoscimento del contenuto.

```csharp
public enum RecognitionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Flow | `0` | Modalità di riconoscimento completo, il motore tenta di eseguire il raggruppamento e l'analisi multilevel per ripristinare l'intento originale dell'autore del documento e produrre xhtml in layout a flusso. |
| PdfFlow | `1` | L'idea principale di questa conversione si basa sul salvataggio dell\"naturale\" ordine di rendering del contenuto che si forma durante l'elaborazione dei documenti pdf. Nei casi generali i documenti pdf mantengono l'ordine di rendering dall'alto verso il basso, da sinistra a destra (vedi allegato directions.png). Questa assunzione consente di creare un algoritmo a percorso unico che trasformerà gli elementi Aps con posizioni (layout fisso) in formati a flusso come HTML,EPUB,DOC. Questa modalità sarà particolarmente utile per la conversione da PDF(APS) a EPUB, poiché il formato EPUB è stato sviluppato per e‑reader come Kindle o smartphone. La dimensione dello schermo di questi dispositivi è solitamente inferiore a quella di un PC tradizionale. Pertanto il contenuto dei documenti EPUB è meglio salvarlo in formato a flusso, per un rendering corretto su schermi di dimensioni diverse. In questa modalità ogni colonna verrà aggiunta alla fine della colonna precedente, consentendo di mantenere la struttura logica del documento trasformato durante la \"paginazione\" nei lettori EPUB. Questo risultato permette di rendere correttamente articoli scientifici o di rivista. |
| Fixed | `2` | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale delle pagine, ma sfortunatamente molti lettori EPUB non supportano xhtml con layout fisso |

### Vedi anche

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


