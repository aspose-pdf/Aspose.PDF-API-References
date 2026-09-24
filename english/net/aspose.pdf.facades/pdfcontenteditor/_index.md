---
title: "PdfContentEditor Class"
linktitle: "PdfContentEditor"
articleTitle: "PdfContentEditor"
second_title: "Aspose.PDF for .NET"
description: "Represents a class to edit PDF file's content."
type: docs
weight: 320
url: "/net/aspose.pdf.facades/pdfcontenteditor/"
keywords: "PdfContentEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfContentEditor class

Represents a class to edit PDF file's content.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfContentEditor](./pdfcontenteditor/#constructor) | The constructor of the PdfContentEditor object. |
| [PdfContentEditor](./pdfcontenteditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfContentEditor`](../../aspose.pdf.facades/pdfcontenteditor/) object on base of the . |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [ReplaceTextStrategy](./replacetextstrategy/) { get; set; } | A set of parameters for replace text operation. |
| [TextEditOptions](./texteditoptions/) { get; set; } | Gets or sets text edit options. |
| [TextReplaceOptions](./textreplaceoptions/) { get; set; } | Gets or sets text replace options. |
| [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets text search options. |

## Methods

| Name | Description |
| --- | --- |
| [AddDocumentAdditionalAction](./adddocumentadditionalaction/)(*string, string*) | Adds additional action for document event. |
| [AddDocumentAttachment](./adddocumentattachment/)(*string, string*) | Adds document attachment with no annotation. |
| [AddDocumentAttachment](./adddocumentattachment/)(*Stream, string, string*) | Adds document attachment with no annotation. |
| [AssertDocument](../../aspose.pdf.facades/facade/assertdocument/) | Asserts if the facade is initialized. *(Inherited from Facade)* |
| [BindPdf](./bindpdf/)(*string*) | Binds a PDF file for editing. |
| [BindPdf](./bindpdf/)(*Stream*) | Binds a PDF stream for editing. |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string, ICustomSecurityHandler*) | Initializes the facade. *(Inherited from Facade)* |
| [ChangeViewerPreference](./changeviewerpreference/)(*int*) | Changes the view preference. |
| [Close](./close/) | Closes opened document. |
| [CreateApplicationLink](./createapplicationlink/)(*Rectangle, string, int*) | Creates a link to launch an application in PDF document. |
| [CreateApplicationLink](./createapplicationlink/)(*Rectangle, string, int, Color*) | Creates a link to launch an application in PDF document. |
| [CreateApplicationLink](./createapplicationlink/)(*Rectangle, string, int, Color, Enum[]*) | Creates a link to launch an application in PDF document. |
| [CreateBookmarksAction](./createbookmarksaction/)(*string, Color, bool, bool, string, string, string*) | Creates a bookmark with the specified action. |
| [CreateCaret](./createcaret/)(*int, Rectangle, Rectangle, string, string, Color*) | Creates caret annotation. |
| [CreateCustomActionLink](./createcustomactionlink/)(*Rectangle, int, Color, Enum[]*) | Creates a link to custom actions in PDF document. |
| [CreateFileAttachment](./createfileattachment/)(*Rectangle, string, string, int, string*) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(*Rectangle, string, string, int, string, double*) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(*Rectangle, string, Stream, string, int, string*) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(*Rectangle, string, Stream, string, int, string, double*) | Creates file attachment annotation. |
| [CreateFreeText](./createfreetext/)(*Rectangle, string, int*) | Creates free text annotation in PDF document. |
| [CreateJavaScriptLink](./createjavascriptlink/)(*string, Rectangle, int, Color*) | Creates a link to JavaScript in PDF document. |
| [CreateLine](./createline/)(*Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]*) | Creates line annotation. |
| [CreateLocalLink](./createlocallink/)(*Rectangle, int, int*) | Creates a local link in PDF document. |
| [CreateLocalLink](./createlocallink/)(*Rectangle, int, int, Color*) | Creates a local link in PDF document. |
| [CreateLocalLink](./createlocallink/)(*Rectangle, int, int, Color, Enum[]*) | Creates a local link in PDF document. |
| [CreateMarkup](./createmarkup/)(*Rectangle, string, int, int, Color*) | Creates markup annotation it PDF document. |
| [CreateMovie](./createmovie/)(*Rectangle, string, int*) | Creates Movie Annotations. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(*Rectangle, string, int, int*) | Creates a link to another PDF document page. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(*Rectangle, string, int, int, Color*) | Creates a link to another PDF document page. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(*Rectangle, string, int, int, Color, Enum[]*) | Creates a link to another PDF document page. |
| [CreatePolyLine](./createpolyline/)(*LineInfo, int, Rectangle, string*) | Creates polyline annotation. |
| [CreatePolygon](./createpolygon/)(*LineInfo, int, Rectangle, string*) | Creates polygon annotation. |
| [CreatePopup](./createpopup/)(*Rectangle, string, bool, int*) | Creates popup annotation in PDF document. |
| [CreateRubberStamp](./createrubberstamp/)(*int, Rectangle, string, string, Color*) | Creates a rubber stamp annotation. |
| [CreateRubberStamp](./createrubberstamp/)(*int, Rectangle, string, Color, string*) | Creates a rubber stamp annotation. |
| [CreateRubberStamp](./createrubberstamp/)(*int, Rectangle, string, Color, Stream*) | Creates a rubber stamp annotation. |
| [CreateSound](./createsound/)(*Rectangle, string, string, int, string*) | Creates Sound Annotations. |
| [CreateSquareCircle](./createsquarecircle/)(*Rectangle, string, Color, bool, int, int*) | Creates square-circle annotation. |
| [CreateText](./createtext/)(*Rectangle, string, string, bool, string, int*) | Creates text annotation in PDF document. |
| [CreateWebLink](./createweblink/)(*Rectangle, string, int*) | Creates a web link in PDF document. |
| [CreateWebLink](./createweblink/)(*Rectangle, string, int, Color*) | Creates a web link in PDF document. |
| [CreateWebLink](./createweblink/)(*Rectangle, string, int, Color, Enum[]*) | Creates a web link in PDF document. |
| [DeleteAttachments](./deleteattachments/) | Deletes all attachments in PDF document. |
| [DeleteImage](./deleteimage/) | Deletes all images from PDF document. |
| [DeleteImage](./deleteimage/)(*int, int[]*) | Deletes the specified images on the specified page. |
| [DeleteStamp](./deletestamp/)(*int, int[]*) | Deletes multiple stamps on the specified page by stamp indexes. |
| [DeleteStampById](./deletestampbyid/)(*int*) | Delete stamp by ID from all pages of the document. |
| [DeleteStampById](./deletestampbyid/)(*int, int*) | Deletes stamp on the specified page by stamp ID. |
| [DeleteStampByIds](./deletestampbyids/)(*int[]*) | Deletes stamps with specified IDs from all pages of the document. |
| [DeleteStampByIds](./deletestampbyids/)(*int, int[]*) | Deletes stamps on the specified page by multiple stamp IDs. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [DrawCurve](./drawcurve/)(*LineInfo, int, Rectangle, string*) | Creates curve annotation. |
| [ExtractLink](./extractlink/) | Extracts the collection of Link instances contained in PDF document. |
| [GetStamps](./getstamps/)(*int*) | Returns array of stamps on the page. |
| [GetViewerPreference](./getviewerpreference/) | Returns the view preference. |
| [HideStampById](./hidestampbyid/)(*int, int*) | Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method. |
| [MoveStamp](./movestamp/)(*int, int, double, double*) | Changes position of the stamp on page. |
| [MoveStampById](./movestampbyid/)(*int, int, double, double*) | Changes position of the stamp on page. |
| [RemoveDocumentOpenAction](./removedocumentopenaction/) | Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup. |
| [ReplaceImage](./replaceimage/)(*int, int, string*) | Replaces the specified image on the specified page of PDF document with another image. |
| [ReplaceText](./replacetext/)(*string, string*) | Replaces text in the PDF file. |
| [ReplaceText](./replacetext/)(*string, int, string*) | Replaces text in the PDF file on the specified page. |
| [ReplaceText](./replacetext/)(*string, string, TextState*) | Replaces text in the PDF file using specified [`TextState`](../../aspose.pdf.text/textstate/) object. |
| [ReplaceText](./replacetext/)(*string, string, int*) | Replaces text in the PDF file and sets font size. |
| [ReplaceText](./replacetext/)(*string, int, string, TextState*) | Replaces text in the PDF file on the specified page. [`TextState`](../../aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text. |
| [Save](../../aspose.pdf.facades/saveablefacade/save/)(*string*) | Saves the PDF document to the specified file. *(Inherited from SaveableFacade)* |
| [ShowStampById](./showstampbyid/)(*int, int*) | Shows stamp which was hidden by HiddenStampById. |

## Fields

| Name | Description |
| --- | --- |
| const [DocumentClose](./documentclose/) | A document event type. Closes a document. |
| const [DocumentOpen](./documentopen/) | A document event type. Opens a document. |
| const [DocumentPrinted](./documentprinted/) | A document event type. Excute a action after printing. |
| const [DocumentSaved](./documentsaved/) | A document event type. Excute a action after saving. |
| const [DocumentWillPrint](./documentwillprint/) | A document event type. Excute a action before printing. |
| const [DocumentWillSave](./documentwillsave/) | A document event type. Excute a action before saving. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

