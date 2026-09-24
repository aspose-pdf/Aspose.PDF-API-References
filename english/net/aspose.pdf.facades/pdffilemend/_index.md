---
title: "PdfFileMend Class"
linktitle: "PdfFileMend"
articleTitle: "PdfFileMend"
second_title: "Aspose.PDF for .NET"
description: "Represents a class for adding texts and images on the pages of existing PDF document."
type: docs
weight: 420
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
| [PdfFileMend](./pdffilemend/#constructor) | Constructor. |
| [PdfFileMend](./pdffilemend/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfFileMend`](../../aspose.pdf.facades/pdffilemend/) object on base of the . |
| [PdfFileMend](./pdffilemend/#constructor_2)(*string, string*) | Constructor. |
| [PdfFileMend](./pdffilemend/#constructor_3)(*Stream, Stream*) | Constructor. |
| [PdfFileMend](./pdffilemend/#constructor_4)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`PdfFileMend`](../../aspose.pdf.facades/pdffilemend/) object on base of the . |
| [PdfFileMend](./pdffilemend/#constructor_5)(*[Document](../../aspose.pdf/document/), Stream*) | Initializes new [`PdfFileMend`](../../aspose.pdf.facades/pdffilemend/) object on base of the . |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [InputFile](./inputfile/) { get; set; } | Sets the input file. |
| [InputStream](./inputstream/) { get; set; } | Sets the input stream. |
| [IsWordWrap](./iswordwrap/) { set; } | Sets a bool value that indicates word wrap in AddText methods. |
| [OutputFile](./outputfile/) { get; set; } | Sets the output file. |
| [OutputStream](./outputstream/) { get; set; } | Sets the output stream. |
| [TextPositioningMode](./textpositioningmode/) { get; set; } | Sets or gets text positioning strategy. [`PositioningMode`](../../aspose.pdf.facades/positioningmode/). |
| [WrapMode](./wrapmode/) { get; set; } | Sets or gets word wrapping algorithm. See WordWrapMode and IsWordWrap. |

## Methods

| Name | Description |
| --- | --- |
| [AddImage](./addimage/)(*Stream, int, float, float, float, float*) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*Stream, int[], float, float, float, float*) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*string, int, float, float, float, float*) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*string, int[], float, float, float, float*) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*Stream, int, float, float, float, float, CompositingParameters*) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*Stream, int[], float, float, float, float, CompositingParameters*) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*string, int, float, float, float, float, CompositingParameters*) | Adds image to the specified page of PDF document at specified coordinates. |
| [AddImage](./addimage/)(*string, int[], float, float, float, float, CompositingParameters*) | Adds image to the specified pages of PDF document at specified coordinates. |
| [AddText](./addtext/)(*FormattedText, int, float, float*) | Not implemented. |
| [AddText](./addtext/)(*FormattedText, int, float, float, float, float*) | Not implemented. |
| [AddText](./addtext/)(*FormattedText, int[], float, float, float, float*) | Not implemented. |
| [AssertDocument](../../aspose.pdf.facades/facade/assertdocument/) | Asserts if the facade is initialized. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string, ICustomSecurityHandler*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](./close/) | Closes PdfFileMend object. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [Save](./save/)(*string*) | Saves the PDF document to the specified file. |
| [Save](./save/)(*Stream*) | Saves the PDF document to the specified stream. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

