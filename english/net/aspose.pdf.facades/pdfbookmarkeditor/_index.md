---
title: "PdfBookmarkEditor Class"
linktitle: "PdfBookmarkEditor"
articleTitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF for .NET"
description: "Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete."
type: docs
weight: 310
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
| [PdfBookmarkEditor](./pdfbookmarkeditor/#constructor) | Initializes new [`PdfBookmarkEditor`](../../aspose.pdf.facades/pdfbookmarkeditor/) object. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/#constructor_1)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`PdfBookmarkEditor`](../../aspose.pdf.facades/pdfbookmarkeditor/) object on base of the . |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |

## Methods

| Name | Description |
| --- | --- |
| [AssertDocument](../../aspose.pdf.facades/facade/assertdocument/) | Asserts if the facade is initialized. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string*) | Initializes the facade. *(Inherited from Facade)* |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string, string, ICustomSecurityHandler*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](../../aspose.pdf.facades/facade/close/) | Disposes Aspose.Pdf.Document bound with a facade. *(Inherited from Facade)* |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(*string, int*) | Creates bookmark for the specified page. |
| [CreateBookmarkOfPage](./createbookmarkofpage/)(*string[], int[]*) | Creates bookmarks for the specified pages. |
| [CreateBookmarks](./createbookmarks/) | Creates bookmarks for all pages. |
| [CreateBookmarks](./createbookmarks/)(*Bookmark*) | Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy. |
| [CreateBookmarks](./createbookmarks/)(*Color, bool, bool*) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [DeleteBookmarks](./deletebookmarks/) | Deletes all bookmarks of the PDF document. |
| [DeleteBookmarks](./deletebookmarks/)(*string*) | Deletes the bookmark of the PDF document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [ExportBookmarksToHtml](./exportbookmarkstohtml/)(*string, string*) | Exports bookmarks to HTML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(*string*) | Exports bookmarks to XML file. |
| [ExportBookmarksToXML](./exportbookmarkstoxml/)(*Stream*) | Exports bookmarks to XML stream. |
| [ExtractBookmarks](./extractbookmarks/) | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(*bool*) | Extracts bookmarks of all levels from the document. |
| [ExtractBookmarks](./extractbookmarks/)(*string*) | Extracts the bookmarks with the specified title. |
| [ExtractBookmarks](./extractbookmarks/)(*Bookmark*) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [ExtractBookmarksToHTML](./extractbookmarkstohtml/)(*string, string*) | Exports bookmarks to HTML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(*string*) | Imports bookmarks to the document from XML file. |
| [ImportBookmarksWithXML](./importbookmarkswithxml/)(*Stream*) | Imports bookmarks to the document from XML file. |
| [ModifyBookmarks](./modifybookmarks/)(*string, string*) | Modifys bookmark title according to the specified bookmark title. |
| [Save](../../aspose.pdf.facades/saveablefacade/save/)(*string*) | Saves the PDF document to the specified file. *(Inherited from SaveableFacade)* |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

