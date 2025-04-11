---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend klass. Representerar en klass för att lägga till texter och bilder på sidorna av ett befintligt PDF-dokument
type: docs
weight: 4530
url: /sv/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend klass

Representerar en klass för att lägga till texter och bilder på sidorna av ett befintligt PDF-dokument.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Konstruktör. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Initierar ett nytt `PdfFileMend`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetar med. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Sätter ett bool-värde som indikerar radbrytning i AddText-metoder. Om värdet är sant kommer texten i FormattedText att radbrytas. Som standard är värdet falskt. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Sätter eller hämtar textpositioneringsstrategi. [`PositioningMode`](../positioningmode/) Standardläge är Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Sätter eller hämtar algoritm för radbrytning. Se WordWrapMode och IsWordWrap. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Lägger till bild på den angivna sidan av PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Lägger till bild på de angivna sidorna av PDF-dokumentet vid angivna koordinater. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Inte implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Inte implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Inte implementerad. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Stänger PdfFileMend-objektet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avsätter facaden. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)