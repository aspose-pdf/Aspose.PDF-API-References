---
title: "PdfExtractor Class"
linktitle: "PdfExtractor"
articleTitle: "PdfExtractor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfExtractor class. Class for extracting images and text from PDF document."
type: docs
weight: 330
url: "/net/aspose.pdf.facades/pdfextractor/"
keywords: "PdfExtractor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfExtractor class

Class for extracting images and text from PDF document.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfExtractor](./pdfextractor/#constructor)() | Initializes new [`PdfExtractor`](../../aspose.pdf.lowcode/pdfextractor/) object. |
| [PdfExtractor](./pdfextractor/#constructor_1)(Document) | Initializes new [`PdfExtractor`](../../aspose.pdf.lowcode/pdfextractor/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [EndPage](./endpage/) { get; set; } | Gets or sets end page in the page range where extracting operation will be performed. |
| [ExtractImageMode](./extractimagemode/) { get; set; } | Sets the mode for extract images process. |
| [ExtractTextMode](./extracttextmode/) { get; set; } | Sets the mode for extract text's result. |
| [IsBidi](./isbidi/) { get; } | Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars). |
| [Password](./password/) { get; set; } | Gets or sets input file's password. |
| [Resolution](./resolution/) { get; set; } | Set or gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [StartPage](./startpage/) { get; set; } | Gets or sets start page in the page range where extracting operation will be performed. |
| [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets text search options. |

## Methods

| Name | Description |
| --- | --- |
| override [BindPdf](./bindpdf/)(Stream) | Binds PDF document from stream. |
| override [BindPdf](./bindpdf/)(string) | Bind input PDF file. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExtractAttachment](./extractattachment/)() | Extracts attachments from a Pdf document. |
| [ExtractAttachment](./extractattachment/)(string) | Extracts attachment to PDF file by attachment name. |
| [ExtractImage](./extractimage/)() | Extract images from PDF file. |
| [ExtractText](./extracttext/)() | Extracts text from a Pdf document using Unicode encoding. |
| [ExtractText](./extracttext/)(Encoding) | Extracts text from a Pdf document using specified encoding. |
| [GetAttachNames](./getattachnames/)() | Returns list of attachments in PDF file. Note: ExtractAttachments must be called before using this method. |
| [GetAttachment](./getattachment/)() | Saves all the attachment file to streams. |
| [GetAttachment](./getattachment/)(string) | Stores attachment into file. |
| [GetAttachmentInfo](./getattachmentinfo/)() | Gets the list of attachments. |
| [GetNextImage](./getnextimage/)(Stream) | Retrieve next image from PDF file and stores it into stream. |
| [GetNextImage](./getnextimage/)(string) | Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method. |
| [GetNextImage](./getnextimage/)(Stream, ImageFormat) | Retrieve next image from PDF file and stores it into stream with given image format. |
| [GetNextImage](./getnextimage/)(string, ImageFormat) | Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method. |
| [GetNextPageText](./getnextpagetext/)(Stream) | Saves one page's text to stream. |
| [GetNextPageText](./getnextpagetext/)(string) | Saves one page's text to file. |
| [GetText](./gettext/)(Stream) | Saves text to stream. see also:`ExtractText` |
| [GetText](./gettext/)(string) | Saves text to file. see also:`ExtractText` |
| [GetText](./gettext/)(Stream, bool) | Saves text to stream. see also:`ExtractText` |
| [HasNextImage](./hasnextimage/)() | Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method. |
| [HasNextPageText](./hasnextpagetext/)() | Indicates that whether can get more texts or not. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

