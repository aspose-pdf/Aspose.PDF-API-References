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
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::String\&, int32_t) | Creates bookmark for the specified page. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<int32_t\>\&) | Creates bookmarks for the specified pages. |
| [CreateBookmarks](./createbookmarks/)() | Creates bookmarks for all pages. |
| [CreateBookmarks](./createbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy. |
| [CreateBookmarks](./createbookmarks/)(System::Drawing::Color, bool, bool) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [DeleteBookmarks](./deletebookmarks/)() | Deletes all bookmarks of the PDF document. |
| [DeleteBookmarks](./deletebookmarks/)(const System::String\&) | Deletes the bookmark of the PDF document. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(const System::String\&, const System::String\&) | Exports bookmarks to HTML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::String\&) | Exports bookmarks to XML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exports bookmarks to XML stream. |
| [ExtractBookmarks](./extractbookmarks/)() | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(const System::String\&) | Extracts the bookmarks with the specified title. |
| [ExtractBookmarks](./extractbookmarks/)(const System::SharedPtr\<Bookmark\>\&) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(const System::String\&, const System::String\&) | Exports bookmarks to HTML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::String\&) | Imports bookmarks to the document from XML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(const System::SharedPtr\<System::IO::Stream\>\&) | Imports bookmarks to the document from XML file. |
| [ModifyBookmarks](./modifybookmarks/)(const System::String\&, const System::String\&) | Modifys bookmark title according to the specified bookmark title. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)() | Initializes new [PdfBookmarkEditor](./) object. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Initializes new [PdfBookmarkEditor](./) object on base of the *document* . |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
