---
title: HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF per .NET API Reference
description: Se la proprietà SplitToPages di HtmlSaveOptions vengono creati diversi file HTML un file HTML per pagina convertita durante la conversione di PDF in HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione di PDF in HTML
type: docs
weight: 3540
url: /it/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Se la proprietà SplitToPages di HtmlSaveOptions, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione di PDF in HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione di PDF in HTML

```csharp
public class HtmlPageMarkupSavingInfo
```

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlpagemarkupsavinginfo/contentstream) | Impostato dal convertitore. Rappresenta l'HTML salvato come stream |
| [CustomProcessingCancelled](../../aspose.pdf/htmlpagemarkupsavinginfo/customprocessingcancelled) | Dovrebbe essere impostato nel codice personalizzato quando necessario. Questo flag deve essere impostato su "true" nel codice personalizzato se per alcuni motivi il markup html fornito deve essere elaborato non con il codice personalizzato ma con il codice del convertitore stesso in modalità standard per il convertitore. Quindi, impostando se questo flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo da solo |
| [HtmlHostPageNumber](../../aspose.pdf/htmlpagemarkupsavinginfo/htmlhostpagenumber) | Impostato dal convertitore. Se si imposta la proprietà SplitToPages, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione creata. Questa proprietà contiene l'ordinale del file della pagina HTML salvata. La proprietà può essere utilizzata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e Se la divisione sulle pagine è disattivata questo valore contiene sempre '1' poiché in in tal caso viene generata solo una grande pagina HTML per l'intero documento sorgente. |
| [PdfHostPageNumber](../../aspose.pdf/htmlpagemarkupsavinginfo/pdfhostpagenumber) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione creata . Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stata creata markup HTML salvato . Se il numero di pagina originale per qualche motivo è sconosciuto o SplitOnPages=false, allora questa proprietà contiene sempre '0' che segnala che il convertitore non può fornire il numero esatto di pagina del PDF originale per il file di markup HTML fornito. |
| [SupposedFileName](../../aspose.pdf/htmlpagemarkupsavinginfo/supposedfilename) | Impostato dal convertitore. Nome file presunto che va dal convertitore al codice del metodo personalizzato Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto |

### Guarda anche

* class [HtmlSaveOptions](../htmlsaveoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
