---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode enum. When PDF file that usually has fixed layout is being converted the conversion engine tries to perform grouping and multilevel analysis to restore the original document authors intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content
type: docs
weight: 4070
url: /it/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## Enumerazione EpubSaveOptions.RecognitionMode

Quando un file PDF (che di solito ha un layout fisso) viene convertito, il motore di conversione cerca di eseguire raggruppamenti e analisi multilevel per ripristinare l'intento originale dell'autore del documento e produrre un risultato in layout fluido. Questa proprietà regola quella conversione per questo o quel metodo desiderabile di riconoscimento del contenuto.

```csharp
public enum RecognitionMode
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Flow | `0` | Modalità di riconoscimento completo, il motore cerca di eseguire raggruppamenti e analisi multilevel per ripristinare l'intento originale dell'autore del documento e produrre xhtml in layout fluido. |
| PdfFlow | `1` | L'idea principale di questa conversione si basa sul salvataggio dell'ordine "naturale" di rendering del contenuto che si forma durante l'elaborazione dei documenti pdf. Nei casi generali, i documenti pdf mantengono un ordine di rendering dall'alto verso il basso e da sinistra a destra (vedi le direzioni dell'allegato directions.png). Questa assunzione consente di creare un algoritmo a percorso singolo che trasformerà gli elementi Aps che hanno posizioni (layout fisso) in formati fluido come HTML, EPUB, DOC. Questa modalità sarà particolarmente utile per la conversione da PDF(APS) a EPUB, poiché il formato EPUB è stato sviluppato per e-reader come il Kindle o smartphone. La dimensione dello schermo di questi dispositivi è solitamente inferiore alla dimensione dello schermo di un normale PC. Pertanto, è meglio salvare il contenuto dei documenti EPUB in formato fluido, per una corretta visualizzazione su schermi di diverse dimensioni. In questa modalità, ogni colonna verrà aggiunta alla fine della colonna precedente, consentendo di mantenere la struttura logica del documento trasformato durante la "paginazione" nei lettori EPUB. Questo risultato consente di visualizzare correttamente articoli scientifici o di riviste. |
| Fixed | `2` | Questa modalità è veloce e buona per preservare al massimo l'aspetto originale delle pagine, ma sfortunatamente molti lettori EPUB non supportano xhtml con layout fisso |

### Vedi Anche

* classe [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)