---
title: "PdfFileStamp Class"
linktitle: "PdfFileStamp"
articleTitle: "PdfFileStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfFileStamp class. Class for adding stamps (watermark or background) to PDF files."
type: docs
weight: 450
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
| [PdfFileStamp](./pdffilestamp/#constructor)() | Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. |
| [PdfFileStamp](./pdffilestamp/#constructor_1)(Document) | Initializes new [`PdfFileStamp`](../../aspose.pdf.facades/pdffilestamp/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [KeepSecurity](./keepsecurity/) { get; set; } | Keeps security if true. (This feature will be implemented in next versions). |
| [NumberingStyle](./numberingstyle/) { get; set; } | Gets or sets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](./optimizesize/) { get; set; } | Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [PageHeight](./pageheight/) { get; } | Gets height of first page in souorce file. |
| [PageNumberRotation](./pagenumberrotation/) { get; set; } | Gets or sets rotation of page number. Rotation is in degrees. Default is 0. |
| [PageWidth](./pagewidth/) { get; } | Gets width of first page in input file. |
| [StampId](./stampid/) { get; set; } | Stamp ID of next added stamp (incluiding page headers/hooters/page numbers). |
| [StartingNumber](./startingnumber/) { get; set; } | Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... |

## Methods

| Name | Description |
| --- | --- |
| [AddFooter](./addfooter/)(FormattedText, float) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(Stream, float) | Adds image as footer of the page. |
| [AddFooter](./addfooter/)(string, float) | Adds image as footer to the pages of the document. |
| [AddFooter](./addfooter/)(FormattedText, float, float, float) | Adds footer to the pages of the document. |
| [AddFooter](./addfooter/)(Stream, float, float, float) | Adds image as footer of the page. |
| [AddFooter](./addfooter/)(string, float, float, float) | Adds image as footer of the pages. |
| [AddHeader](./addheader/)(FormattedText, float) | Adds header to the page. |
| [AddHeader](./addheader/)(Stream, float) | Adds image as header on the pages. |
| [AddHeader](./addheader/)(string, float) | Adds image as header to the pages of the file. |
| [AddHeader](./addheader/)(FormattedText, float, float, float) | Adds header to the pages of file. |
| [AddHeader](./addheader/)(Stream, float, float, float) | Adds image at the top of the page. |
| [AddHeader](./addheader/)(string, float, float, float) | Adds image as header on the pages. |
| [AddPageNumber](./addpagenumber/)(FormattedText) | Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](./addpagenumber/)(string) | Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](./addpagenumber/)(FormattedText, int) | Adds page number to the pages. |
| [AddPageNumber](./addpagenumber/)(string, int) | Adds page number to the pages. |
| [AddPageNumber](./addpagenumber/)(FormattedText, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(string, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](./addpagenumber/)(FormattedText, int, float, float, float, float) | Adds page number to the pages of document. |
| [AddPageNumber](./addpagenumber/)(string, int, float, float, float, float) | Adds page number to the pages of document. |
| [AddStamp](./addstamp/)(Stamp) | Adds stamp to the file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](./close/)() | Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| override [Save](./save/)(Stream) | Saves document into specified stream. |
| override [Save](./save/)(string) | Saves result into specified file. |

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

