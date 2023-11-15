---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend class. Represents a class for adding texts and images on the pages of existing PDF document
type: docs
weight: 2590
url: /net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class

Represents a class for adding texts and images on the pages of existing PDF document.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | Constructor. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | Initializes new `PdfFileMend` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | Sets a bool value that indicates word wrap in AddText methods. If the value is true, the text in FormattedText will word wrap. By defalt, the value is false. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | Sets or gets text positioning strategy. [`PositioningMode`](../positioningmode/) Default mode is Legacy. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | Sets or gets word wrapping algorithm. See WordWrapMode and IsWordWrap. |

## Methods

| Name | Description |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | Not implemented. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | Not implemented. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | Not implemented. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | Closes PdfFileMend object. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | Saves the PDF document to the specified stream. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | Saves the PDF document to the specified file. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


