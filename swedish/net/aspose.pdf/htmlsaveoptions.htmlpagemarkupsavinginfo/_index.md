---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo klass. Om SplitToPages-egenskapen för HtmlSaveOptions är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen av PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparande av en HTML-sidas markup under konverteringen av PDF till HTML.
type: docs
weight: 5670
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo klass

Om SplitToPages-egenskapen för HtmlSaveOptions är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen av PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparande av en HTML-sidas markup under konverteringen av PDF till HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Satt av konverteraren. Representerar sparad HTML som ström |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Bör sättas i anpassad kod när det är nödvändigt. Denna flagga måste sättas till "true" i anpassad kod om den angivna HTML-markupen av någon anledning ska behandlas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så, att sätta denna flagga i anpassad kod betyder att den anpassade koden inte har behandlat den refererade filen och konverteraren måste hantera den själv. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Satt av konverteraren. Om SplitToPages-egenskapen är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningen av den sparade HTML-sidans fil. Egenskapen kan användas i logiken för den anpassade koden för att avgöra hur man ska behandla eller var man ska spara HTML-sidan, och om uppdelning på sidor är avstängd innehåller detta värde alltid '1' eftersom det i sådana fall endast genereras en stor HTML-sida för hela källdokumentet. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Satt av konverteraren. Om SplitToPages-egenskapen är aktiverad, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap berättar för den anpassade koden från vilken sida av den ursprungliga PDF som den sparade HTML-markupen skapades. Om det ursprungliga sidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan tillhandahålla det exakta ursprungliga PDF-sidnumret för den angivna HTML-markupfilen. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Satt av konverteraren. Antaget filnamn som går från konverteraren till koden för den anpassade metoden. Kan användas i anpassad kod för att avgöra hur man ska behandla eller var man ska spara innehållet. |

### Se Även

* klass [HtmlSaveOptions](../htmlsaveoptions/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)