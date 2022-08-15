---
title: PdfExtractor
second_title: Aspose.PDF för .NET API Referens
description: Klass för att extrahera bilder och text från PDF-dokument.
type: docs
weight: 2460
url: /sv/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Klass för att extrahera bilder och text från PDF-dokument.

```csharp
public sealed class PdfExtractor : Facade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfExtractor](pdfextractor#constructor)() | Initierar ny[`PdfExtractor`](../pdfextractor) objekt. |
| [PdfExtractor](pdfextractor#constructor_1)(Document) | Initierar ny[`PdfExtractor`](../pdfextractor) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage) { get; set; } | Hämtar eller ställer in slutsidan i sidintervallet där extrahering kommer att utföras. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode) { get; set; } | Ställer in läget för extrahering av bilder. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode) { get; set; } | Ställer in läget för extrahering av textresultat. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi) { get; } | Är sant när text har hebriska eller arabiska symboler. Detta fall måste särskilt beaktas eftersom strängfunktioner ändrar sitt beteende och startar processtext från höger till vänster (förutom siffror och andra tecken som inte är text). |
| [Password](../../aspose.pdf.facades/pdfextractor/password) { get; set; } | Hämtar eller ställer in indatafilens lösenord. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution) { get; set; } | Ställ in eller hämta upplösning för extraherade bilder. Standardvärdet är 150. Bilder som har högre upplösningsvärde är mer tydliga. Men ett ökat upplösningsvärde resulterar i ökad tid och minne som behövs för att extrahera bilder. Vanligtvis räcker det för att få en tydlig bild för att ställa in upplösningen till 150 eller 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage) { get; set; } | Hämtar eller ställer in startsidan i sidintervallet där extraheringsoperationen kommer att utföras. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions) { get; set; } | Hämtar eller ställer in alternativ för textsökning. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_1)(Stream) | Binder PDF-dokument från stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf#bindpdf_2)(string) | Bind in PDF-fil. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Kastar Aspose.Pdf.Dokument bunden med en fasad. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment)() | Extraherar bilagor från ett pdf-dokument. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment#extractattachment_1)(string) | Extraherar bilaga till PDF-fil efter bilagans namn. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage)() | Extrahera bilder från PDF-fil. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext)() | Extraherar text från ett pdf-dokument med Unicode-kodning. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext#extracttext_1)(Encoding) | Extraherar text från ett pdf-dokument med angiven kodning. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment)() | Sparar alla bifogade filer till streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment#getattachment_1)(string) | Lagrar bilaga i fil. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo)() | Hämtar listan med bilagor. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames)() | Returnerar en lista över bilagor i PDF-fil. Obs! ExtractAttachments måste anropas innan du använder den här metoden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage)(Stream) | Hämta nästa bild från PDF-fil och lagra den i stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_2)(string) | Hämtar nästa bild från PDF-dokument. Obs: ExtractImage måste anropas innan du använder den här metoden. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_1)(Stream, ImageFormat) | Hämta nästa bild från PDF-fil och lagra den i ström med givet bildformat. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage#getnextimage_3)(string, ImageFormat) | Hämtar nästa bild från PDF-dokument med givet bildformat. Obs: ExtractImage måste anropas innan du använder den här metoden. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext)(Stream) | Sparar en sidas text för att streama. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext#getnextpagetext_1)(string) | Sparar en sidas text till fil. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext)(Stream) | Sparar text för att streama. se även:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_2)(string) | Sparar text till fil. se även:[`ExtractText`](./extracttext) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext#gettext_1)(Stream, bool) | Sparar text för att streama. se även:[`ExtractText`](./extracttext) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage)() | Kontrollerar om fler bilder är tillgängliga i PDF-dokument. Obs: ExtractImage måste anropas innan du använder den här metoden. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext)() | Indikerar att om kan få fler texter eller inte. |

### Se även

* class [Facade](../facade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
