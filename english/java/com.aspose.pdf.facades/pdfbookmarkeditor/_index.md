---
title: PdfBookmarkEditor
linktitle: PdfBookmarkEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.
type: docs
weight: 370
url: /java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Initializes new {@code PdfBookmarkEditor} object. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Initializes new {@code PdfBookmarkEditor} object. |

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Close the instance of PdfBookmarkEditor and release the resources. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Creates bookmarks for the specified pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Creates bookmark for the specified page. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Deletes all bookmarks of the PDF document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Deletes all bookmarks of the PDF document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Exports bookmarks to HTML file. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Exports bookmarks to XML stream. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Exports bookmarks to XML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Extracts bookmarks of all levels from the document. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Exports bookmarks to HTML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Imports bookmarks to the document from XML file. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Imports bookmarks to the document from XML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Modifys bookmark title according to the specified bookmark title. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Initializes new {@code PdfBookmarkEditor} object.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Initializes new {@code PdfBookmarkEditor} object.

### close {#close--}
```
public void close()
```

Close the instance of PdfBookmarkEditor and release the resources.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Creates bookmarks for the specified pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Creates bookmark for the specified page. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Creates bookmarks for all pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Deletes all bookmarks of the PDF document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Deletes all bookmarks of the PDF document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Exports bookmarks to HTML file. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Exports bookmarks to XML stream.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Exports bookmarks to XML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
The bookmarks collection of all bookmarks that exist in the document.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
The bookmarks collection of all bookmarks that exist in the document.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Extracts bookmarks of all levels from the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel |  | If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively. |

**Returns:**
List of extracted bookmarks.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Extracts bookmarks of all levels from the document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
The bookmarks collection of all bookmarks that exist in the document.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Exports bookmarks to HTML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Imports bookmarks to the document from XML file.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Imports bookmarks to the document from XML file. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Modifys bookmark title according to the specified bookmark title. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
