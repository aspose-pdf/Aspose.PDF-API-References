---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer class. Represents a class to view or print a pdf
type: docs
weight: 3090
url: /net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Represents a class to view or print a pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Initializes new `PdfViewer` object. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Initializes new `PdfViewer` object. |

## Properties

| Name | Description |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Gets or sets a bool value that indicates whether the file be printed with optimized size.  If false print page without page scaling. If true print page with scaling to fit to printable area. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Gets or sets a bool value that indicates whether the file be printed with auto rotation |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Gets or sets a AutoRotateMode value that indicates direction of rotation |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Gets or sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Gets or sets form presentation mode. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Gets or sets a value that indicates horizontal alignment |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Gets page count of the current Pdf file. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Gets or sets input document password. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Gets or sets a bool value that indicates whether the page is being printed as grayscale. By default is false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Sets or gets a mode for PdfViewer to print as image. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Gets or sets name of document in printer queue when document is printed. Default value is file name. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Gets or sets a bool value that indicates whether produce the page number dialog when printing. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Gets the result of printing job. If success than null; otherwise, exception object. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Gets or sets rendering options. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Gets or sets resolution during viewing and printing. The higher resolution, the slower speed. The default value is 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Gets or sets a floating point value that indicates scale factor. The default value is 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Gets/sets the using of conversion of pdf page into intermidiate png file during printing in file mode. Use it when the size of output file is important. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Gets or sets a value that indicates vertical alignment |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Initializes the facade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Initializes the facade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Initializes the facade. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Closes the facade. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Get pages of current pdf file. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Decodes a page of one Pdf file. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Disposes the facade resources. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Gets the default page settings. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Gets the default printer settings. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Prints the Pdf document using default printer. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Prints the Pdf document with printer settings. The output page size will fit the the document first page size. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Prints the Pdf document with settings. If the document size does not correspond to page size, it will be extended to fit page size. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Prints the Pdf document with a setup dialog. Choose a printer using the dialog. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Opens and prints a large Pdf stream. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Opens and prints a large Pdf file. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Opens and prints a large Pdf stream with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Opens and prints a large Pdf file with specified printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Opens and prints a large Pdf stream with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Opens and prints a large Pdf file with specified page settings and printer settings. If your Pdf file has hundreds of pages or more or its size is more than 3 MB, this method is recommended to get better performance. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Saves the result PDF document to stream. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Saves the result PDF document to file. |

## Events

| Name | Description |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Occurs before printing starts and allows to provide custom print handlers instead of the default one. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Adds/removes subscription on the last page printing event. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Adds/removes subscription on the last page printing event. |

### See Also

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


