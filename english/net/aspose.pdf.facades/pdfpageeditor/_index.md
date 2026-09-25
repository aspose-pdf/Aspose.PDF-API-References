---
title: "PdfPageEditor Class"
linktitle: "PdfPageEditor"
articleTitle: "PdfPageEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfPageEditor class. Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing p..."
type: docs
weight: 480
url: "/net/aspose.pdf.facades/pdfpageeditor/"
keywords: "PdfPageEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfPageEditor class

Represents a class to edit the PDF file's page, including rotating page, zooming page, moving position and changing page size.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageEditor](./pdfpageeditor/#constructor) | Constructor for PdfPageEditor class. |
| [PdfPageEditor](./pdfpageeditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Constructor for PdfPageEditor class. |

## Properties

| Name | Description |
| --- | --- |
| [Alignment](./alignment/) { get; set; } | Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [DisplayDuration](./displayduration/) { get; set; } | Gets or sets display duration for pages. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets the horizontal alignment of the original PDF content on the result page, default is AlignmentType.Left. |
| [PageRotations](./pagerotations/) { get; set; } | A hashtable contains the page number and rotation degree,. |
| [PageSize](./pagesize/) { get; set; } | Gets or sets the output file's page size. |
| [ProcessPages](./processpages/) { get; set; } | Gets or sets the page numbers to be edited. By default, each page would be edited. |
| [Rotation](./rotation/) { get; set; } | Gets or sets the rotation of the pages, the rotation must be 0, 90, 180 or 270. |
| [TransitionDuration](./transitionduration/) { get; set; } | Gets or sets duration of the transition effect. |
| [TransitionType](./transitiontype/) { get; set; } | Gets or sets transition style to use when moving to this page from another during a presentation. |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [VerticalAlignmentType](./verticalalignmenttype/) { get; set; } | Gets or Sets the vertical alignment of the original PDF content on the result page, default is VerticalAlignmentType.Bottom. |
| [Zoom](./zoom/) { get; set; } | Get or sets zoom coefficient. Value 1.0 corresponds to 100%. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChanges](./applychanges/) | Apply changes made to the document pages. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](../../aspose.pdf.facades/facade/close/) | Disposes Aspose.Pdf.Document bound with a facade. *(Inherited from Facade)* |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [GetPageBoxSize](./getpageboxsize/)(*int, string*) | Returns size of specified box in document. |
| [GetPageRotation](./getpagerotation/)(*int*) | Returns the rotation of specified page. |
| [GetPageSize](./getpagesize/)(*int*) | Returns the page size of the specified page. |
| [GetPages](./getpages/) | Returns total number of pages. |
| [MovePosition](./moveposition/)(*float, float*) | Moves the origin from (0, 0) to the point that appointted. |
| [Save](./save/)(*string*) | Saves changed document into file. |
| [Save](./save/)(*Stream*) | Saves changed document into stream. |

## Fields

| Name | Description |
| --- | --- |
| const [BLINDH](./blindh/) | Vertical Blinds. |
| const [BLINDV](./blindv/) | Vertical Blinds. |
| const [BTWIPE](./btwipe/) | Bottom-Top Wipe. |
| const [DGLITTER](./dglitter/) | Diagonal Glitter. |
| const [DISSOLVE](./dissolve/) | The old page dissolves. |
| const [INBOX](./inbox/) | Inward Box. |
| const [LRGLITTER](./lrglitter/) | Left-Right Glitter. |
| const [LRWIPE](./lrwipe/) | Left-Right Wipe. |
| const [OUTBOX](./outbox/) | Outward Box. |
| const [RLWIPE](./rlwipe/) | Right-Left Wipe. |
| const [SPLITHIN](./splithin/) | IN Horizontal Split. |
| const [SPLITHOUT](./splithout/) | Out Horizontal Split. |
| const [SPLITVIN](./splitvin/) | In Vertical Split. |
| const [SPLITVOUT](./splitvout/) | Out Vertical Split. |
| const [TBGLITTER](./tbglitter/) | Top-Bottom Glitter. |
| const [TBWIPE](./tbwipe/) | Top-Bottom Wipe. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

