---
title: "Classe HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Questa classe rappresenta un insieme di dati relativi al salvataggio dei file immagine delle risorse esterne durante la conversione da PDF a HTML"
type: docs
weight: 5770
url: /it/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Questa classe rappresenta un insieme di dati relativi al salvataggio del file immagine di risorse esterne durante la conversione da PDF a HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Impostato dal convertitore. Rappresenta il contenuto binario del file salvato. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Questo flag deve essere impostato su "true" nel codice personalizzato se, per qualche motivo, il file proposto deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso secondo il modo standard del convertitore. Quindi, impostare il flag su true significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente (sia per il salvataggio che per la denominazione del file di riferimento). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Indica al codice personalizzato a quale pagina del set generato di file HTML appartiene l'immagine salvata. Se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola pagina HTML. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Rappresenta il tipo di immagine salvata referenziata in HTML. Impostato dal convertitore e può essere usato nel codice personalizzato per decidere cosa fare. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | L'immagine salvata può appartenere a HTML stesso o può essere estratta da SVG incorporato in HTML. Questa proprietà può indicare al codice personalizzato il tipo di genitore dell'immagine elaborata. È impostata dal convertitore e può essere usata nel codice personalizzato per decidere cosa fare con quell'immagine (ad es. il codice personalizzato può decidere dove salvare l'immagine o come deve essere referenziata nel contenuto del genitore). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Indica al codice personalizzato a quale pagina del documento PDF originale appartiene l'immagine salvata. Poiché è possibile che non vengano salvate tutte le pagine del documento originale, questo valore indica il numero della pagina ospite nel PDF originale. Se il numero della pagina originale per qualche motivo è sconosciuto, restituisce sempre '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Impostato dal convertitore. Nome file presunto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare quel file. |

### Vedi anche

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


