---
title: "Klass PdfFileMend"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfFileMend-klass. Representerar en klass för att lägga till texter och bilder på sidorna i ett befintligt PDF-dokument"
type: docs
weight: 4650
url: /sv/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Representerar en klass för att lägga till texter och bilder på sidorna i befintlig PDF document.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Konstruktor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Initierar ett nytt `PdfFileMend`-objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Ställer in ett booleskt värde som indikerar radbrytning i AddText-metoder. Om värdet är true, kommer texten i FormattedText att radbrytas. Som standard är värdet false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Ställer in eller hämtar textpositioneringsstrategi. [`PositioningMode`](../positioningmode/) Standardläge är Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Ställer in eller hämtar radbrytningsalgoritm. Se WordWrapMode och IsWordWrap. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Lägger till en bild på den angivna sidan i PDF-dokumentet på angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Lägger till en bild på de angivna sidorna i PDF-dokumentet på angivna koordinater. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Ej implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Ej implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Ej implementerad. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Stänger PdfFileMend-objektet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


