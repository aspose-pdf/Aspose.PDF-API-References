---
title: "Classe HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Se la proprietà SplitToPages di HtmlSaveOptions è impostata, vengono creati diversi file HTML, un file HTML per pagina convertita, durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML."
type: docs
weight: 5800
url: /it/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Se la proprietà SplitToPages di HtmlSaveOptions è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Impostato dal convertitore. Rappresenta l'HTML salvato come stream. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Deve essere impostato nel codice personalizzato quando necessario. Questa flag deve essere impostata su "true" nel codice personalizzato se, per qualche motivo, il markup HTML fornito deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostare questa flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà contiene l'ordine del file HTML salvato. La proprietà può essere usata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e, se la divisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola grande pagina HTML per l'intero documento di origine. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero della pagina originale è per qualche motivo sconosciuto o SplitOnPages=false, questa proprietà contiene sempre '0', segnalando che il convertitore non può fornire il numero esatto della pagina PDF originale per il file di markup HTML fornito. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Impostato dal convertitore. Nome file previsto che viene passato dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto. |

### Vedi anche

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


