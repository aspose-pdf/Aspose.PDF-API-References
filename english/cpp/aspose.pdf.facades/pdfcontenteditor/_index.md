---
title: Aspose::Pdf::Facades::PdfContentEditor class
linktitle: PdfContentEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfContentEditor class. Represents a class to edit PDF file''s content in C++.'
type: docs
weight: 1700
url: /cpp/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class


Represents a class to edit PDF file's content.

```cpp
class PdfContentEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [AddDocumentAdditionalAction](./adddocumentadditionalaction/)(System::String, System::String) | Adds additional action for document event. |
| [AddDocumentAttachment](./adddocumentattachment/)(System::String, System::String) | Adds document attachment with no annotation. |
| [AddDocumentAttachment](./adddocumentattachment/)(System::SharedPtr\<System::IO::Stream\>, System::String, System::String) | Adds document attachment with no annotation. |
| [BindPdf](./bindpdf/)(System::String) override | Binds a PDF file for editing. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Binds a PDF stream for editing. |
| [ChangeViewerPreference](./changeviewerpreference/)(int32_t) | Changes the view preference. |
| [Close](./close/)() override | Closes opened document. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) | Creates a link to launch an application in PDF document. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color) | Creates a link to launch an application in PDF document. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, System::String, int32_t) | Creates a link to launch an application in PDF document. |
| [CreateBookmarksAction](./createbookmarksaction/)(System::String, System::Drawing::Color, bool, bool, System::String, System::String, System::String) | Creates a bookmark with the specified action. |
| [CreateCaret](./createcaret/)(int32_t, System::Drawing::Rectangle, System::Drawing::Rectangle, System::String, System::String, System::Drawing::Color) | Creates caret annotation. |
| [CreateCustomActionLink](./createcustomactionlink/)(System::Drawing::Rectangle, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) | Creates a link to custom actions in PDF document. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, System::String, System::String, int32_t, System::String) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, System::String, System::String, int32_t, System::String, double) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, System::String, System::SharedPtr\<System::IO::Stream\>, System::String, int32_t, System::String) | Creates file attachment annotation. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, System::String, System::SharedPtr\<System::IO::Stream\>, System::String, int32_t, System::String, double) | Creates file attachment annotation. |
| [CreateFreeText](./createfreetext/)(System::Drawing::Rectangle, System::String, int32_t) | Creates free text annotation in PDF document. |
| [CreateJavaScriptLink](./createjavascriptlink/)(System::String, System::Drawing::Rectangle, int32_t, System::Drawing::Color) | Creates a link to JavaScript in PDF document. |
| [CreateLine](./createline/)(System::Drawing::Rectangle, System::String, float, float, float, float, int32_t, int32_t, System::Drawing::Color, System::String, System::ArrayPtr\<int32_t\>, System::ArrayPtr\<System::String\>) | Creates line annotation. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) | Creates a local link in PDF document. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) | Creates a local link in PDF document. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t) | Creates a local link in PDF document. |
| [CreateMarkup](./createmarkup/)(System::Drawing::Rectangle, System::String, int32_t, int32_t, System::Drawing::Color) | Creates markup annotation it PDF document. |
| [CreateMovie](./createmovie/)(System::Drawing::Rectangle, System::String, int32_t) | Creates Movie [Annotations](../../aspose.pdf.annotations/). |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, System::String, int32_t, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) | Creates a link to another PDF document page. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, System::String, int32_t, int32_t, System::Drawing::Color) | Creates a link to another PDF document page. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, System::String, int32_t, int32_t) | Creates a link to another PDF document page. |
| [CreatePolygon](./createpolygon/)(System::SharedPtr\<LineInfo\>, int32_t, System::Drawing::Rectangle, System::String) | Creates polygon annotation. |
| [CreatePolyLine](./createpolyline/)(System::SharedPtr\<LineInfo\>, int32_t, System::Drawing::Rectangle, System::String) | Creates polyline annotation. |
| [CreatePopup](./createpopup/)(System::Drawing::Rectangle, System::String, bool, int32_t) | Creates popup annotation in PDF document. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, System::String, System::String, System::Drawing::Color) | Creates a rubber stamp annotation. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::String) | Creates a rubber stamp annotation. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, System::String, System::Drawing::Color, System::SharedPtr\<System::IO::Stream\>) | Creates a rubber stamp annotation. |
| [CreateSound](./createsound/)(System::Drawing::Rectangle, System::String, System::String, int32_t, System::String) | Creates Sound [Annotations](../../aspose.pdf.annotations/). |
| [CreateSquareCircle](./createsquarecircle/)(System::Drawing::Rectangle, System::String, System::Drawing::Color, bool, int32_t, int32_t) | Creates square-circle annotation. |
| [CreateText](./createtext/)(System::Drawing::Rectangle, System::String, System::String, bool, System::String, int32_t) | Creates text annotation in PDF document. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color, System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>) | Creates a web link in PDF document. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, System::String, int32_t, System::Drawing::Color) | Creates a web link in PDF document. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, System::String, int32_t) | Creates a web link in PDF document. |
| [DeleteAttachments](./deleteattachments/)() | Deletes all attachments in PDF document. |
| [DeleteImage](./deleteimage/)(int32_t, System::ArrayPtr\<int32_t\>) | Deletes the specified images on the specified page. |
| [DeleteImage](./deleteimage/)() | Deletes all images from PDF document. |
| [DeleteStamp](./deletestamp/)(int32_t, System::ArrayPtr\<int32_t\>) | Deletes multiple stamps on the specified page by stamp indexes. |
| [DeleteStampById](./deletestampbyid/)(int32_t, int32_t) | Deletes stamp on the specified page by stamp ID. |
| [DeleteStampById](./deletestampbyid/)(int32_t) | Delete stamp by ID from all pages of the document. |
| [DeleteStampByIds](./deletestampbyids/)(System::ArrayPtr\<int32_t\>) | Deletes stamps with specified IDs from all pages of the document. |
| [DeleteStampByIds](./deletestampbyids/)(int32_t, System::ArrayPtr\<int32_t\>) | Deletes stamps on the specified page by multiple stamp IDs. |
| [DrawCurve](./drawcurve/)(System::SharedPtr\<LineInfo\>, int32_t, System::Drawing::Rectangle, System::String) | Creates curve annotation. |
| [ExtractLink](./extractlink/)() | Extracts the collection of Link instances contained in PDF document. |
| [get_ReplaceTextStrategy](./get_replacetextstrategy/)() const | A set of parameters for replace text operation. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Gets text edit options. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Gets text replace options. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Gets text search options. |
| [GetStamps](./getstamps/)(int32_t) | Returns array of stamps on the page. |
| [GetViewerPreference](./getviewerpreference/)() | Returns the view preference. |
| [HideStampById](./hidestampbyid/)(int32_t, int32_t) | Hides the stamp. After hiding, stamp visibility may be restored with ShowStampById method. |
| [MoveStamp](./movestamp/)(int32_t, int32_t, double, double) | Changes position of the stamp on page. |
| [MoveStampById](./movestampbyid/)(int32_t, int32_t, double, double) | Changes position of the stamp on page. |
| [PdfContentEditor](./pdfcontenteditor/)() | The constructor of the [PdfContentEditor](./) object. |
| [PdfContentEditor](./pdfcontenteditor/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfContentEditor](./) object on base of the *document* . |
| [RemoveDocumentOpenAction](./removedocumentopenaction/)() | Removes open action from the document. This operation is useful when concatenating multiple documents that use explicit 'GoTo' action on startup. |
| [ReplaceImage](./replaceimage/)(int32_t, int32_t, System::String) | Replaces the specified image on the specified page of PDF document with another image. |
| [ReplaceText](./replacetext/)(System::String, int32_t, System::String, System::SharedPtr\<Text::TextState\>) | Replaces text in the PDF file on the specified page. [TextState](../) object (font family, color) can be specified to replaced text. |
| [ReplaceText](./replacetext/)(System::String, System::String) | Replaces text in the PDF file. |
| [ReplaceText](./replacetext/)(System::String, int32_t, System::String) | Replaces text in the PDF file on the specified page. |
| [ReplaceText](./replacetext/)(System::String, System::String, System::SharedPtr\<Text::TextState\>) | Replaces text in the PDF file using specified [TextState](../) object. |
| [ReplaceText](./replacetext/)(System::String, System::String, int32_t) | Replaces text in the PDF file and sets font size. |
| [set_ReplaceTextStrategy](./set_replacetextstrategy/)(System::SharedPtr\<Aspose::Pdf::Facades::ReplaceTextStrategy\>) | A set of parameters for replace text operation. |
| [set_TextEditOptions](./set_texteditoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>) | Sets text edit options. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>) | Sets text replace options. |
| [set_TextSearchOptions](./set_textsearchoptions/)(System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>) | Sets text search options. |
| [ShowStampById](./showstampbyid/)(int32_t, int32_t) | Shows stamp which was hidden by HiddenStampById. |
## Fields

| Field | Description |
| --- | --- |
| static [DocumentClose](./documentclose/) | A document event type. Closes a document. |
| static [DocumentOpen](./documentopen/) | A document event type. Opens a document. |
| static [DocumentPrinted](./documentprinted/) | A document event type. Excute a action after printing. |
| static [DocumentSaved](./documentsaved/) | A document event type. Excute a action after saving. |
| static [DocumentWillPrint](./documentwillprint/) | A document event type. Excute a action before printing. |
| static [DocumentWillSave](./documentwillsave/) | A document event type. Excute a action before saving. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
