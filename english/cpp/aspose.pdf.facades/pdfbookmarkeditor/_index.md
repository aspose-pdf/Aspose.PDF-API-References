---
title: Aspose::Pdf::Facades::PdfBookmarkEditor class
linktitle: PdfBookmarkEditor
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfBookmarkEditor class. Represents a class to work with PDF file''s bookmarks including create, modify, export, import and delete in C++.'
type: docs
weight: 1600
url: /cpp/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor class


Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.

```cpp
class PdfBookmarkEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Methods

| Method | Description |
| --- | --- |
| [BindPdf](../facade/bindpdf/)(System::String) override | Initializes the facade. |
| [BindPdf](../facade/bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Initializes the facade. |
| [BindPdf](../facade/bindpdf/)(System::SharedPtr\<Aspose::Pdf::Document\>) override | Initializes the facade. |
| virtual [BindPdf](../ifacade/bindpdf/)(System::SharedPtr\<Document\>) | Binds PDF document for editing. |
| [Close](../facade/close/)() override | Disposes [Aspose.Pdf.Document](../../aspose.pdf/document/) bound with a facade. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(System::String, int32_t) | Creates bookmark for the specified page. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(System::ArrayPtr\<System::String\>, System::ArrayPtr\<int32_t\>) | Creates bookmarks for the specified pages. |
| [CreateBookmarks](./createbookmarks/)() | Creates bookmarks for all pages. |
| [CreateBookmarks](./createbookmarks/)(System::SharedPtr\<Bookmark\>) | Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy. |
| [CreateBookmarks](./createbookmarks/)(System::Drawing::Color, bool, bool) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [DeleteBookmarks](./deletebookmarks/)() | Deletes all bookmarks of the PDF document. |
| [DeleteBookmarks](./deletebookmarks/)(System::String) | Deletes the bookmark of the PDF document. |
| [Dispose](../facade/dispose/)() override | Disposes the facade. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(System::String, System::String) | Exports bookmarks to HTML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(System::String) | Exports bookmarks to XML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(System::SharedPtr\<System::IO::Stream\>) | Exports bookmarks to XML stream. |
| [ExtractBookmarks](./extractbookmarks/)() | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(System::String) | Extracts the bookmarks with the specified title. |
| [ExtractBookmarks](./extractbookmarks/)(System::SharedPtr\<Bookmark\>) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(System::String, System::String) | Exports bookmarks to HTML file. |
| [get_Document](../facade/get_document/)() const | Gets the document facade is working on. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(System::String) | Imports bookmarks to the document from XML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(System::SharedPtr\<System::IO::Stream\>) | Imports bookmarks to the document from XML file. |
| [ModifyBookmarks](./modifybookmarks/)(System::String, System::String) | Modifys bookmark title according to the specified bookmark title. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)() | Initializes new [PdfBookmarkEditor](./) object. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [PdfBookmarkEditor](./) object on base of the *document* . |
| [Save](../saveablefacade/save/)(System::String) override | Saves the PDF document to the specified file. |
| [Save](../saveablefacade/save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves the PDF document to the specified stream. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
