---
title: "Klass HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo-klass. Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursbildfiler under PDF till HTML-konvertering"
type: docs
weight: 5770
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Denna klass representerar en uppsättning data som är relaterade till sparande av externa resursbildfiler under PDF till HTML-konvertering.

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur filen ska bearbetas eller var den ska sparas. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Sätts av konverteraren. Representerar binärt innehåll i den sparade filen. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Denna flagga måste sättas till "true" i anpassad kod om den föreslagna filen av någon anledning ska bearbetas av konverterarens kod istället för av anpassad kod på standardiserat sätt för konverteraren. Så, om flaggan är satt till true betyder det att anpassad kod inte har bearbetat den refererade filen och konverteraren måste hantera den själv (både för att spara den någonstans och för att namnge den i referensfilen). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Anger för anpassad kod vilken page i den genererade uppsättningen av HTML-sidfiler den sparade bilden tillhör. Om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom i så fall endast en HTML-page genereras. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Representerar typen av sparad bild som refereras i HTML. Ställs in av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Den sparade bilden kan hänvisa till HTML själv eller kan extraheras från SVG som är inbäddad i HTML. Denna egenskap kan berätta för anpassad kod vilken typ av förälder den bearbetade bilden har. Den sätts av konverteraren och kan användas i anpassad kod för att avgöra vad som ska göras med bilden (t.ex. kan anpassad kod bestämma var bilden ska sparas eller hur den ska refereras i förälderns innehåll). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Berättar för anpassad kod på vilken sida i det ursprungliga PDF-dokumentet den sparade bilden hör. Eftersom det är möjligt att inte alla sidor i det ursprungliga dokumentet sparas, anger detta värde sidnumret i original-PDF:en. Om originalsidnumret av någon anledning är okänt, returneras alltid '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Sätts av konverteraren. Antaget filnamn som går från konverteraren till kod för anpassad metod. Kan användas i anpassad kod för att avgöra hur filen ska bearbetas eller var den ska sparas. |

### Se även

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


