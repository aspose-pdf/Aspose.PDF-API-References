---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo klass. Denna klass representerar en uppsättning data som relaterar till sparande av externa resursbildfiler under PDF till HTML-konvertering
type: docs
weight: 5640
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo klass

Denna klass representerar en uppsättning data som relaterar till sparande av externa resursbildfiler under PDF till HTML-konvertering.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Standardkonstruktorn. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur filen ska behandlas eller var den ska sparas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Satt av konverteraren. Representerar binärt innehåll av den sparade filen. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Denna flagga måste sättas till "true" i anpassad kod om filen av någon anledning bör behandlas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, att den sätts till true betyder att den anpassade koden inte har behandlat den refererade filen och konverteraren måste hantera den själv (i båda avseenden - för att spara någonstans och för namngivning i den refererande filen). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Berättar för den anpassade koden vilken sida av den genererade uppsättningen av HTML-sidfiler den sparade bilden hör till. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i sådana fall endast en HTML-sida genereras. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Representerar typen av den sparade bilden som refereras i HTML. Satt av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Den sparade bilden kan tillhöra HTML själv eller kan extraheras från SVG inbäddad i HTML. Denna egenskap kan berätta för den anpassade koden vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med den bilden (t.ex. kan den anpassade koden avgöra var bilden ska sparas eller hur den måste refereras i förälderns innehåll). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Berättar för den anpassade koden vilken sida av det ursprungliga PDF-dokumentet den sparade bilden hör till. Eftersom det är möjligt att inte alla sidor av det ursprungliga dokumentet kommer att sparas, berättar detta värde för oss om värd sidnummer i den ursprungliga PDF:en. Om det ursprungliga sidnumret av någon anledning är okänt, returnerar det alltid '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Satt av konverteraren. Antagen filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur filen ska behandlas eller var den ska sparas. |

### Se Även

* klass [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* samling [Aspose.PDF](../../)