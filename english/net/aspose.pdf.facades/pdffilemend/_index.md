---
title: "PdfFileMend Class"
linktitle: "PdfFileMend"
articleTitle: "PdfFileMend"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileMend class. Represents a class for adding texts and images on the pages of existing PDF document."
type: docs
weight: 410
url: "/net/aspose.pdf.facades/pdffilemend/"
keywords: "PdfFileMend, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileMend class

Represents a class for adding texts and images on the pages of existing PDF document.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileMend](./pdffilemend/#constructor)() | Constructor. |
| [PdfFileMend](./pdffilemend/#constructor_1)(Document) | Initializes new [`PdfFileMend`](../../aspose.pdf.facades/pdffilemend/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [IsWordWrap](./iswordwrap/) { set; } | Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false. |
| [TextPositioningMode](./textpositioningmode/) { get; set; } | Sets or gets text positioning strategy. [`PositioningMode`](../../aspose.pdf.facades/positioningmode/) Default mode is Legacy. |
| [WrapMode](./wrapmode/) { get; set; } | Sets or gets word wrapping algorithm. See WordWrapMode and IsWordWrap. |

## Methods

| Name | Description |
| --- | --- |
| [AddImage](./addimage/)(Stream, int, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(Stream, int[], float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(string, int, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(string, int[], float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(Stream, int, float, float, float, float, CompositingParameters) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(Stream, int[], float, float, float, float, CompositingParameters) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(string, int, float, float, float, float, CompositingParameters) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(string, int[], float, float, float, float, CompositingParameters) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddText](./addtext/)(FormattedText, int, float, float) | Not implemented. |
| [AddText](./addtext/)(FormattedText, int, float, float, float, float) | Not implemented. |
| [AddText](./addtext/)(FormattedText, int[], float, float, float, float) | Not implemented. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](./close/)() | Closes PdfFileMend object. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| override [Save](./save/)(Stream) | Saves the PDF document to the specified stream. |
| override [Save](./save/)(string) | Saves the PDF document to the specified file. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

