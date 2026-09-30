---
title: "PdfBookmarkEditor Class"
linktitle: "PdfBookmarkEditor"
articleTitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfBookmarkEditor class. Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete."
type: docs
weight: 300
url: "/net/aspose.pdf.facades/pdfbookmarkeditor/"
keywords: "PdfBookmarkEditor, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfBookmarkEditor class

Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfBookmarkEditor](./pdfbookmarkeditor/#constructor)() | Initializes new [`PdfBookmarkEditor`](../../aspose.pdf.facades/pdfbookmarkeditor/) object. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/#constructor_1)(Document) | Initializes new [`PdfBookmarkEditor`](../../aspose.pdf.facades/pdfbookmarkeditor/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(string, int) | Creates bookmark for the specified page. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(string[], int[]) | Creates bookmarks for the specified pages. |
| [CreateBookmarks](./createbookmarks/)() | Creates bookmarks for all pages. |
| [CreateBookmarks](./createbookmarks/)(Bookmark) | Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy. |
| [CreateBookmarks](./createbookmarks/)(Color, bool, bool) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [DeleteBookmarks](./deletebookmarks/)() | Deletes all bookmarks of the PDF document. |
| [DeleteBookmarks](./deletebookmarks/)(string) | Deletes the bookmark of the PDF document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| static [ExportBookmarksToHtml](./exportbookmarkstohtml/)(string, string) | Exports bookmarks to HTML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(Stream) | Exports bookmarks to XML stream. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(string) | Exports bookmarks to XML file. |
| [ExtractBookmarks](./extractbookmarks/)() | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(Bookmark) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [ExtractBookmarks](./extractbookmarks/)(bool) | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(string) | Extracts the bookmarks with the specified title. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(Stream) | Imports bookmarks to the document from XML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(string) | Imports bookmarks to the document from XML file. |
| [ModifyBookmarks](./modifybookmarks/)(string, string) | Modifys bookmark title according to the specified bookmark title. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

