---
title: PdfFileMend
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för att lägga till texter och bilder på sidorna i befintliga PDF-dokument.
type: docs
weight: 2540
url: /sv/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Representerar en klass för att lägga till texter och bilder på sidorna i befintliga PDF-dokument.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfFileMend](pdffilemend#constructor)() | Konstruktör. |
| [PdfFileMend](pdffilemend#constructor_1)(Document) | Initierar ny[`PdfFileMend`](../pdffilemend) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap) { set; } | Ställer in ett boolvärde som indikerar radbrytning i AddText-metoder. Om värdet är sant kommer texten i Formaterad text att radbrytas. Som defalt är värdet false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode) { get; set; } | Ställer in eller hämtar textpositioneringsstrategi.[`PositioningMode`](../positioningmode) Standardläget är Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode) { get; set; } | Ställer in eller hämtar ordbrytningsalgoritm. Se WordWrapMode och IsWordWrap. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage)(Stream, int, float, float, float, float) | Lägger till bild på den angivna sidan i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_2)(Stream, int[], float, float, float, float) | Lägger till bild till de angivna sidorna i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_4)(string, int, float, float, float, float) | Lägger till bild på den angivna sidan i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_6)(string, int[], float, float, float, float) | Lägger till bild till de angivna sidorna i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Lägger till bild på den angivna sidan i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Lägger till bild till de angivna sidorna i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Lägger till bild på den angivna sidan i PDF-dokumentet vid angivna koordinater. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Lägger till bild till de angivna sidorna i PDF-dokumentet vid angivna koordinater. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext)(FormattedText, int, float, float) | Inte implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext_1)(FormattedText, int, float, float, float, float) | Inte implementerad. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext#addtext_2)(FormattedText, int[], float, float, float, float) | Inte implementerad. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close)() | Stänger PdfFileMend-objekt. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save#save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save#save_1)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->