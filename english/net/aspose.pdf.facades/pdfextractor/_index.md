---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfExtractor class. Class for extracting images and text from PDF document
type: docs
weight: 2520
url: /net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

Class for extracting images and text from PDF document.

```csharp
public sealed class PdfExtractor : Facade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Initializes new `PdfExtractor` object. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Initializes new `PdfExtractor` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Gets or sets end page in the page range where extracting operation will be performed. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Sets the mode for extract images process. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Sets the mode for extract text's result. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | Is true when text has hebriew or arabic symbols. This case must be specially considered because string functions change their behaviour and start process text from right to left (except numbers and other non text chars). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Gets or sets input file's password. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Set or gets resolution for extracted images. Default value is 150. Images which have greater resolution value are more clear. However increasing resolution value results in increasing time and memory needed to extract images. Usually to get clear image it's enough to set resolution to 150 or 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Gets or sets start page in the page range where extracting operation will be performed. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Gets or sets text search options. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Binds PDF document from stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Bind input PDF file. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extracts attachments from a Pdf document. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extracts attachment to PDF file by attachment name. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extract images from PDF file. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extracts text from a Pdf document using Unicode encoding. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extracts text from a Pdf document using specified encoding. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Saves all the attachment file to streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Stores attachment into file. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Gets the list of attachments. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Returns list of attachments in PDF file. Note: ExtractAttachments must be called befor using this method. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Retreive next image from PDF file and stores it into stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Retreives next image from PDF document. Note: ExtractImage must be called before using of this method. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Retreive next image from PDF file and stores it into stream with given image format. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Retreives next image from PDF document with given image format. Note: ExtractImage must be called before using of this method. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Saves one page's text to stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Saves one page's text to file. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Saves text to stream. see also:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Saves text to file. see also:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Saves text to stream. see also:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Checks if more images are accessible in PDF document. Note: ExtractImage must be called before using of this method. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indicates that whether can get more texts or not. |

### See Also

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


