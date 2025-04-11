---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo classe. Questa classe rappresenta un insieme di dati relativi al salvataggio di file immagini esterne durante la conversione PDF in HTML.
type: docs
weight: 5640
url: /it/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Questa classe rappresenta un insieme di dati relativi al salvataggio dei file immagine delle risorse esterne durante la conversione da PDF a HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Il costruttore predefinito. |

## Properties

| Name | Description |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

## Fields

| Name | Description |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Questo flag deve essere impostato su "true" nel codice personalizzato se per qualche motivo il file proposto deve essere elaborato non con il codice personalizzato ma con il codice stesso del convertitore in modo standard per il convertitore. Quindi, impostarlo su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo da solo (in entrambi i sensi - per salvarlo da qualche parte e per nominarlo nel file di riferimento). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Indica al codice personalizzato a quale pagina del set generato di file HTML appartiene l'immagine salvata. Se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata solo una pagina HTML. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere utilizzato nel codice personalizzato per decidere cosa dovrebbe essere fatto. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | L'immagine salvata può appartenere all'HTML stesso o può essere estratta da SVG incorporato nell'HTML. Questa proprietà può indicare al codice personalizzato che tipo di genitore ha l'immagine elaborata. È impostata dal convertitore e può essere utilizzata nel codice personalizzato per decidere cosa fare con quell'immagine (ad esempio, il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Indica al codice personalizzato a quale pagina del documento PDF originale appartiene l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore ci informa sul numero della pagina host nel PDF originale. Se il numero della pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome del file previsto che va dal convertitore al codice del metodo personalizzato. Può essere utilizzato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

### See Also

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)