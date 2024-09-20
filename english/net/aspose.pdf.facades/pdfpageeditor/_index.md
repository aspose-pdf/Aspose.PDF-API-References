---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfPageEditor class. Represents a class to edit the PDF files page including rotating page zooming page moving position and changing page size
type: docs
weight: 3100
url: /net/aspose.pdf.facades/pdfpageeditor/
---
## PdfPageEditor class

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Constructor for PdfPageEditor class. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Constructor for PdfPageEditor class. |

## Properties

| Name | Description |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Gets or sets display duration for pages. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | A hashtable contains the page number and rotation degree, the key represents the page number, the value of key represents the rotation in degrees. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Gets or sets the output file's page size. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Gets or sets the page numbers to be edited. By default, each page would be edited. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Gets or sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. Default value is 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Gets or sets duration of the transition effect. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Gets or sets transition style to use when moving to this page from another during a presentation. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Get or sets zoom coefficient. Value 1.0 corresponds to 100%. Default value is 1.0.  The following example demonstrates how to change zoom of the document pages. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Apply changes made to the document pages. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Returns size of specified box in document. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Returns the rotation of specified page. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Returns total number of pages. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Returns the page size of the specified page. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Moves the origin from (0, 0) to the point that appointted. The origin is left-bottom and the unit is point(1 inch = 72 points). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Saves changed document into stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Saves changed document into file. |

## Fields

| Name | Description |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Vertical Blinds |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Vertical Blinds |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Bottom-Top Wipe |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Diagonal Glitter |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | The old page dissolves |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Inward Box |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Left-Right Glitter |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Left-Right Wipe |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Outward Box |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Right-Left Wipe |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | IN Horizontal Split |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Out Horizontal Split |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | In Vertical Split |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Out Vertical Split |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Top-Bottom Glitter |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Top-Bottom Wipe |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


