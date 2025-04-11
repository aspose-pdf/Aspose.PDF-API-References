---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Se la proprietà SplitToPages di HtmlSaveOptions è attivata, vengono creati diversi file HTML (un file HTML per ogni pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML.
type: docs
weight: 5670
url: /it/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Classe HtmlSaveOptions.HtmlPageMarkupSavingInfo

Se la proprietà SplitToPages di HtmlSaveOptions è attivata, vengono creati diversi file HTML (un file HTML per ogni pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Impostato dal convertitore. Rappresenta l'HTML salvato come stream |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Deve essere impostato nel codice personalizzato quando necessario. Questo flag deve essere impostato su "true" nel codice personalizzato se per qualche motivo il markup HTML fornito deve essere elaborato non con codice personalizzato ma con il codice del convertitore stesso in modo standard per il convertitore. Quindi, impostare questo flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo da solo. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Impostato dal convertitore. Se è impostata la proprietà SplitToPages, vengono creati diversi file HTML (un file HTML per ogni pagina convertita) durante la conversione. Questa proprietà contiene l'ordinalità del file della pagina HTML salvata. La proprietà può essere utilizzata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata solo una grande pagina HTML per l'intero documento sorgente. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Impostato dal convertitore. Se la proprietà SplitToPages è attivata, vengono creati diversi file HTML (un file HTML per ogni pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero di pagina originale per qualche motivo è sconosciuto o SplitOnPages=false, allora questa proprietà contiene sempre '0', il che segnala che il convertitore non può fornire il numero esatto della pagina originale del PDF per il file di markup HTML fornito. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto. |

### Vedi Anche

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)