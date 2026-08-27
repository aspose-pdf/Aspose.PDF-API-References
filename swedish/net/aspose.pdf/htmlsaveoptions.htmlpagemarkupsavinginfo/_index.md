---
title: "Klass HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo-klass. Om egenskapen SplitToPages i HtmlSaveOptions är aktiv skapas flera HTML-filer, en HTML-fil per konverterad sida, under konverteringen från PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparning av en HTML-sides markup under konverteringen från PDF till HTML."
type: docs
weight: 5800
url: /sv/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Om egenskapen SplitToPages i HtmlSaveOptions är aktiv, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen från PDF till HTML. Denna klass representerar en uppsättning data som är relaterade till anpassad sparning av en HTML-sidas markup under konverteringen från PDF till HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fält

| Namn | Beskrivning |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Sätts av konverteraren. Representerar sparad HTML som en ström. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Bör sättas i anpassad kod när det behövs. Detta flagg måste sättas till "true" i anpassad kod om den levererade HTML-markupen av någon anledning ska bearbetas inte med anpassad kod utan med konverterarens kod själv på standard sätt för konverteraren. Så att sätta detta flagg i anpassad kod betyder att den anpassade koden inte bearbetade den refererade filen och konverteraren måste hantera den själv. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap innehåller ordningsnumret för den sparade HTML-sidans fil. Egenskapen kan användas i anpassad kods logik för att avgöra hur man ska bearbeta eller var man ska spara HTML-sidan, och om siduppdelning är avstängd innehåller detta värde alltid '1' eftersom i så fall genereras endast en stor HTML-sida för hela källdokumentet. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Sätts av konverteraren. Om egenskapen SplitToPages är satt, skapas flera HTML-filer (en HTML-fil per konverterad sida) under konverteringen. Denna egenskap talar till anpassad kod om från vilken sida i original-PDF:n den sparade HTML-markupen skapades. Om originalsidnumret av någon anledning är okänt eller SplitOnPages=false, innehåller denna egenskap alltid '0' vilket signalerar att konverteraren inte kan leverera exakt original-PDF:s sidnummer för den levererade HTML-markup-filen. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Sätts av konverteraren. Antaget filnamn som går från konverteraren till koden för anpassad metod. Kan användas i anpassad kod för att avgöra hur man ska bearbeta eller var man ska spara innehållet. |

### Se även

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


