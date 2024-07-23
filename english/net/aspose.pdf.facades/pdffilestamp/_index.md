---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileStamp class. Class for adding stamps watermark or background to PDF files
type: docs
weight: 3030
url: /net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

Class for adding stamps (watermark or background) to PDF files.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Constructor of the PdfFileStamp. Input file and output file may be specified via corresponding properties. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Initializes new `PdfFileStamp` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffilestamp/attachmentname/) { get; set; } | Gets or sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [ContentDisposition](../../aspose.pdf.facades/pdffilestamp/contentdisposition/) { get; set; } | Gets or sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Keeps security if true. (This feature will be implemented in next versions). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Gets or sets pabge numbering style. Possible values: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Gets or sets optimization flag. Equal resource streams in resultant file are merged into one PDF object if this flag set. This allows to decrease resultant file size but may cause slower execution and larger memory requirements. Default value: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Gets height of first page in souorce file. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Gets or sets rotation of page number. Rotation is in degrees. Default is 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Gets width of first page in input file. |
| [Response](../../aspose.pdf.facades/pdffilestamp/response/) { get; set; } | Gets or sets Response object where result of operation will be stored. |
| [SaveOptions](../../aspose.pdf.facades/pdffilestamp/saveoptions/) { get; set; } | Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | Stamp ID of next added stamp (incluiding page headers/hooters/page numbers). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Gets or sets starting number for first page in input file. Next pages will be numbered starting from this value. For example if StartingNumber is set to 100, document pages will have numbers 100, 101, 102... |

## Methods

| Name | Description |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Adds footer to the pages of the document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Adds image as footer of the page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Adds image as footer to the pages of the document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Adds footer to the pages of the document. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Adds image as footer of the page. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Adds image as footer of the pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Adds header to the page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Adds image as header on the pages. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Adds image as header to the pages of the file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Adds header to the pages of file. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Adds image at the top of the page. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Adds image as header on the pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Adds page number to the page. Page number may contain # sign which will be replaced with page number. Page number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Add page number to file. Page number text may contain # sign which will be replaced with number of the page. Page number is placed in the bottom of the page centered horizontally. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Adds page number to the pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Adds page number to the pages. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Adds page number at the specified position on the page. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Adds page number to the pages of document. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Adds page number to the pages of document. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Adds stamp to the file. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Closes opened files and saves changes. Warning. If input or output streams are specified they are not closed by Close() method. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Saves document into specified stream. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Saves result into specified file. |

## Fields

| Name | Description |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Bottom left position. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Bottom middle position. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Bottom right position. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Left position. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Right position. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Upper let position. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Upper middle position. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Right upper position. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


