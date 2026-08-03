---
title: "Klassen PdfExtractor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfExtractor class. Klass för att extrahera bilder och text från PDF-dokument"
type: docs
weight: 4570
url: /sv/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Klass för att extrahera bilder och text från PDF document.

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
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Hämtar eller anger sista sidan i sidintervallet där extraheringsoperationen kommer att utföras. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Ställer in läget för bildextraktionsprocessen. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Ställer in läget för resultatet av textutdragning. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Är sann när texten har hebreiska eller arabiska tecken. Detta fall måste särskilt beaktas eftersom strängfunktioner ändrar sitt beteende och startar textprocessen från höger till vänster (förutom siffror och andra icke‑texttecken). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Hämtar eller anger lösenordet för indatafilen. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Ställer in eller hämtar upplösningen för extraherade bilder. Standardvärdet är 150. Bilder med högre upplösning är tydligare. Att öka upplösningsvärdet leder dock till längre tid och mer minne som behövs för att extrahera bilder. Vanligtvis räcker det att sätta upplösningen till 150 eller 300 för att få en klar bild. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Hämtar eller anger startsidan i sidintervallet där extraheringsoperationen kommer att utföras. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Hämtar eller anger alternativ för textsökning. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Kopplar PDF document från ström. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Koppla indata-PDF-fil. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rensar Aspose.Pdf.Document som är bunden till en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extraherar bilagor från ett Pdf document. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrahera bilaga till PDF-fil efter bilagnamn. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrahera bilder från PDF-fil. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extraherar text från ett Pdf document med Unicode‑kodning. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extraherar text från ett Pdf document med angiven kodning. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Sparar alla bilagor till strömmar. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Lagrar bilagan i en fil. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Hämtar listan över bilagor. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Returnerar en lista över bilagor i PDF-filen. Obs: ExtractAttachments måste anropas innan denna metod används. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Hämtar nästa bild från PDF-filen och lagrar den i en ström. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Hämtar nästa bild från PDF document. Obs: ExtractImage måste anropas innan denna metod används. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Hämtar nästa bild från PDF-filen och lagrar den i en ström med angivet bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Hämtar nästa bild från PDF document med angivet bildformat. Obs: ExtractImage måste anropas innan denna metod används. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Sparar en sidas text till en ström. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Sparar en sidas text till en fil. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Sparar text till ström. se även:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Sparar text till fil. se även:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Sparar text till ström. se även:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Kontrollerar om fler bilder är tillgängliga i PDF-dokumentet. Obs: ExtractImage måste anropas innan den här metoden används. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indikerar om fler texter kan hämtas eller inte. |

### Se även

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


