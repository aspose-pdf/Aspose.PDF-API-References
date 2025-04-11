---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor klass. Klass för att extrahera bilder och text från PDF-dokument
type: docs
weight: 4450
url: /sv/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor klass

Klass för att extrahera bilder och text från PDF-dokument.

```csharp
public sealed class PdfExtractor : Facade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initierar ett nytt `PdfExtractor`-objekt. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initierar ett nytt `PdfExtractor`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentet som fasaden arbetar med. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Hämtar eller ställer in slutbladet i sidintervallet där extraktionsoperationen kommer att utföras. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Ställer in läget för extrahering av bilder. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Ställer in läget för resultatet av textutvinning. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Är sant när texten har hebreiska eller arabiska symboler. Detta fall måste beaktas särskilt eftersom strängfunktioner ändrar sitt beteende och börjar bearbeta text från höger till vänster (utom siffror och andra icke-texttecken). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Hämtar eller ställer in inmatningsfilens lösenord. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Ställer in eller hämtar upplösningen för extraherade bilder. Standardvärdet är 150. Bilder med högre upplösningsvärde är tydligare. Att öka upplösningsvärdet resulterar dock i ökad tid och minne som behövs för att extrahera bilder. Vanligtvis är det tillräckligt att ställa in upplösningen på 150 eller 300 för att få en tydlig bild. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Hämtar eller ställer in startbladet i sidintervallet där extraktionsoperationen kommer att utföras. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Hämtar eller ställer in alternativ för textsökning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Binder PDF-dokument från ström. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Binder inmatnings-PDF-filen. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Avsätter Aspose.Pdf.Document som är bunden till en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter fasaden. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extraherar bilagor från ett PDF-dokument. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extraherar bilaga till PDF-fil efter bilagans namn. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extraherar bilder från PDF-fil. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extraherar text från ett PDF-dokument med Unicode-kodning. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extraherar text från ett PDF-dokument med angiven kodning. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Sparar alla bilagor till strömmar. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Lagrar bilaga i fil. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Hämtar listan över bilagor. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Returnerar lista över bilagor i PDF-fil. Obs: ExtractAttachments måste anropas innan denna metod används. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Hämtar nästa bild från PDF-fil och lagrar den i ström. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Hämtar nästa bild från PDF-dokument. Obs: ExtractImage måste anropas innan denna metod används. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Hämtar nästa bild från PDF-fil och lagrar den i ström med angiven bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Hämtar nästa bild från PDF-dokument med angiven bildformat. Obs: ExtractImage måste anropas innan denna metod används. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Sparar texten från en sida till ström. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Sparar texten från en sida till fil. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Sparar text till ström. se även:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Sparar text till fil. se även:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Sparar text till ström. se även:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Kontrollerar om fler bilder är tillgängliga i PDF-dokument. Obs: ExtractImage måste anropas innan denna metod används. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indikerar om fler texter kan hämtas eller inte. |

### Se Även

* klass [Facade](../facade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../)