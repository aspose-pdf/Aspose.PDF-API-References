---
title: "PdfViewer Class"
linktitle: "PdfViewer"
articleTitle: "PdfViewer"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfViewer class. Represents a class to view or print a pdf."
type: docs
weight: 510
url: "/net/aspose.pdf.facades/pdfviewer/"
keywords: "PdfViewer, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfViewer class

Represents a class to view or print a pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfViewer](./pdfviewer/#constructor)() | Initializes new [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/) object. |
| [PdfViewer](./pdfviewer/#constructor_1)(Document) | Initializes new [`PdfViewer`](../../aspose.pdf.facades/pdfviewer/) object. |

## Properties

| Name | Description |
| --- | --- |
| [AutoResize](./autoresize/) { get; set; } | Gets or sets a bool value that indicates whether the file be printed with optimized size. |
| [AutoRotate](./autorotate/) { get; set; } | Gets or sets a bool value that indicates whether the file be printed with auto rotation |
| [AutoRotateMode](./autorotatemode/) { get; set; } | Gets or sets a AutoRotateMode value that indicates direction of rotation |
| [CoordinateType](./coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](./formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets a value that indicates horizontal alignment |
| [PageCount](./pagecount/) { get; } | Gets page count of the current Pdf file. |
| [Password](./password/) { get; set; } | Gets or sets input document password. |
| [PrintAsGrayscale](./printasgrayscale/) { get; set; } | Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. |
| [PrintAsImage](./printasimage/) { get; set; } | Sets or gets a mode for PdfViewer to print as image. |
| [PrintPageDialog](./printpagedialog/) { get; set; } | Gets or sets a bool value that indicates whether produce the page number dialog when printing. |
| [PrintStatus](./printstatus/) { get; } | Gets the result of printing job. If success than null; otherwise, exception object. |
| [PrinterJobName](./printerjobname/) { get; set; } | Gets or sets name of document in printer queue when document is printed. Default value is file name. |
| [RenderingOptions](./renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](./resolution/) { get; set; } | Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. |
| [ScaleFactor](./scalefactor/) { get; set; } | Gets or sets a floating point value that indicates scale factor. The default value is 1.0. |
| [UseIntermidiateImage](./useintermidiateimage/) { get; set; } | Gets/sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important. |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets a value that indicates vertical alignment |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](./bindpdf/)(Document) | Initializes the facade. |
| [BindPdf](./bindpdf/)(Stream) | Initializes the facade. |
| [BindPdf](./bindpdf/)(string) | Initializes the facade. |
| [Close](./close/)() | Closes the facade. |
| [DecodeAllPages](./decodeallpages/)() | Get pages of current pdf file. |
| [DecodePage](./decodepage/)(int) | Decodes a page of one Pdf file. |
| [Dispose](./dispose/)() | Disposes the facade resources. |
| [GetDefaultPageSettings](./getdefaultpagesettings/)() | Gets the default page settings. |
| [GetDefaultPrinterSettings](./getdefaultprintersettings/)() | Gets the default printer settings. |
| [PrintDocument](./printdocument/)() | Prints the Pdf document using default printer. |
| [PrintDocumentWithSettings](./printdocumentwithsettings/)(PrinterSettings) | Prints the Pdf document with printer settings. Printer page settings (paper size, margins, and so on) will be set to default values for the selected printer. |
| [PrintDocumentWithSettings](./printdocumentwithsettings/)(PageSettings, PrinterSettings) | Prints the Pdf document with settings. If the document page size does not correspond to the printer paper size, set the `AutoResize` property to determine whether a page will be extended/shrunk to fit the paper size. |
| [PrintDocumentWithSetup](./printdocumentwithsetup/)() | Prints the Pdf document with a setup dialog. Choose a printer using the dialog. |
| static [PrintDocuments](./printdocuments/)(params Document[]) | Prints multiple PDF documents using default printer and page settings. |
| static [PrintDocuments](./printdocuments/)(params Stream[]) | Prints multiple PDF documents from the provided streams using default printer and page settings. |
| static [PrintDocuments](./printdocuments/)(params string[]) | Prints multiple PDF documents using default printer and page settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, params Document[]) | Prints multiple PDF documents using the specified printer settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, params Stream[]) | Prints multiple PDF documents from the provided streams using the specified printer settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, params string[]) | Prints multiple PDF documents using the specified printer settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, PageSettings, params Document[]) | Prints multiple PDF documents using the specified printer and page settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, PageSettings, params Stream[]) | Prints multiple PDF documents from the provided streams using the specified printer and page settings. |
| static [PrintDocuments](./printdocuments/)(PrinterSettings, PageSettings, params string[]) | Prints multiple PDF documents using the specified printer and page settings. |
| [PrintLargePdf](./printlargepdf/)(Stream) | Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](./printlargepdf/)(string) | Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](./printlargepdf/)(Stream, PrinterSettings) | Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](./printlargepdf/)(string, PrinterSettings) | Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](./printlargepdf/)(Stream, PageSettings, PrinterSettings) | Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](./printlargepdf/)(string, PageSettings, PrinterSettings) | Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [Save](./save/)(Stream) | Saves the result PDF document to stream. |
| [Save](./save/)(string) | Saves the result PDF document to file. |

## Events

| Name | Description |
| --- | --- |
| event [CustomPrint](./customprint/) | Occurs before printing starts and allows to provide custom print handlers instead of the default one. |
| event [EndPage](./endpage/) | Occurs when the printing of a page ends in the PdfViewer. |
| event [EndPrint](./endprint/) | Adds/removes subscription on the last page printing event. |
| event [PdfQueryPageSettings](./pdfquerypagesettings/) | Adds/removes subscription on the last page printing event. |
| event [StartPage](./startpage/) | Occurs before a page starts to print. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

