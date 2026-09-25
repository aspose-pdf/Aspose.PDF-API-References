---
title: "PdfFileStamp Class"
linktitle: "PdfFileStamp"
articleTitle: "PdfFileStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileStamp class. Class for adding stamps (watermark or background) to PDF files."
type: docs
weight: 460
url: "/net/aspose.pdf.facades/pdffilestamp/"
keywords: "PdfFileStamp, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfFileStamp class

Class for adding stamps (watermark or background) to PDF files.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileStamp](./pdffilestamp/#constructor) | Constructor of the PdfFileStamp. |
| [PdfFileStamp](./pdffilestamp/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfFileStamp`](../../aspose.pdf.facades/pdffilestamp/) object on base of the *document*. |
| [PdfFileStamp](./pdffilestamp/#constructor_2)(*string, string*) | Constructor for PdfFileStamp. |
| [PdfFileStamp](./pdffilestamp/#constructor_3)(*Stream, Stream*) | Constructor for PdfFileStamp. |
| [PdfFileStamp](./pdffilestamp/#constructor_4)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`PdfFileStamp`](../../aspose.pdf.facades/pdffilestamp/) object on base of the *document*. |
| [PdfFileStamp](./pdffilestamp/#constructor_5)(*[Document](../../aspose.pdf/document/), Stream*) | Initializes new [`PdfFileStamp`](../../aspose.pdf.facades/pdffilestamp/) object on base of the *document*. |
| [PdfFileStamp](./pdffilestamp/#constructor_6)(*string, string, bool*) | Constructor for PdfFileStamp. |
| [PdfFileStamp](./pdffilestamp/#constructor_7)(*Stream, Stream, bool*) | Constructor of PdfFileStamp. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [InputFile](./inputfile/) { get; set; } | Gets or sets name and path of input file. |
| [InputStream](./inputstream/) { get; set; } | Gets or sets input stream. |
| [KeepSecurity](./keepsecurity/) { get; set; } | Keeps security if true. (This feature will be implemented in next versions). |
| [NumberingStyle](./numberingstyle/) { get; set; } | Gets or sets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. |
| [OutputFile](./outputfile/) { get; set; } | Gets or sets name and path of output file. |
| [OutputStream](./outputstream/) { get; set; } | Gets or sets output stream. |
| [PageHeight](./pageheight/) { get; } | Gets height of first page in souorce file. |
| [PageNumberRotation](./pagenumberrotation/) { get; set; } | Gets or sets rotation of page number. Rotation is in degrees. Default is 0. |
| [PageWidth](./pagewidth/) { get; } | Gets width of first page in input file. |
| [StampId](./stampid/) { get; set; } | Stamp ID of next added stamp (incluiding page headers/hooters/page numbers). |
| [StartingNumber](./startingnumber/) { get; set; } | Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. |

## Methods

| Name | Description |
| --- | --- |
| [AddFooter](./addfooter/)(*FormattedText, float*) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(*string, float*) | Adds image as footer to the pages of the document. |
| [AddFooter](./addfooter/)(*Stream, float*) | Adds image as footer of the page. |
| [AddFooter](./addfooter/)(*FormattedText, float, float, float*) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(*string, float, float, float*) | Adds image as footer of the pages. |
| [AddFooter](./addfooter/)(*Stream, float, float, float*) | Adds image as footer of the page. |
| [AddHeader](./addheader/)(*FormattedText, float*) | Adds header to the page. |
| [AddHeader](./addheader/)(*string, float*) | Adds image as header to the pages of the file. |
| [AddHeader](./addheader/)(*Stream, float*) | Adds image as header on the pages. |
| [AddHeader](./addheader/)(*FormattedText, float, float, float*) | Adds header to the pages of file. |
| [AddHeader](./addheader/)(*string, float, float, float*) | Adds image as header on the pages. |
| [AddHeader](./addheader/)(*Stream, float, float, float*) | Adds image at the top of the page. |
| [AddPageNumber](./addpagenumber/)(*string*) | Add page number to file. Page number text may contain # sign which will be replaced with number of the page. |
| [AddPageNumber](./addpagenumber/)(*FormattedText*) | Adds page number to the page. Page number may contain # sign which will be replaced with page number. |
| [AddPageNumber](./addpagenumber/)(*string, int*) | Adds page number to the pages. |
| [AddPageNumber](./addpagenumber/)(*FormattedText, int*) | Adds page number to the pages. |
| [AddPageNumber](./addpagenumber/)(*string, float, float*) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(*FormattedText, float, float*) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(*string, int, float, float, float, float*) | Adds page number to the pages of document. |
| [AddPageNumber](./addpagenumber/)(*FormattedText, int, float, float, float, float*) | Adds page number to the pages of document. |
| [AddStamp](./addstamp/)(*Stamp*) | Adds stamp to the file. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](./close/) | Closes opened files and saves changes. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [Save](./save/)(*string*) | Saves result into specified file. |
| [Save](./save/)(*Stream*) | Saves document into specified stream. |

## Fields

| Name | Description |
| --- | --- |
| const [PosBottomLeft](./posbottomleft/) | Bottom left position. |
| const [PosBottomMiddle](./posbottommiddle/) | Bottom middle position. |
| const [PosBottomRight](./posbottomright/) | Bottom right position. |
| const [PosSidesLeft](./possidesleft/) | Left position. |
| const [PosSidesRight](./possidesright/) | Right position. |
| const [PosUpperLeft](./posupperleft/) | Upper let position. |
| const [PosUpperMiddle](./posuppermiddle/) | Upper middle position. |
| const [PosUpperRight](./posupperright/) | Right upper position. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

