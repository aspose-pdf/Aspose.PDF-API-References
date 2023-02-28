---
title: PdfBookmarkEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to work with PDF files bookmarks including create modify export import and delete.
type: docs
weight: 30
url: /java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade)
```
public final class PdfBookmarkEditor extends SaveableFacade
```

Represents a class to work with PDF file's bookmarks including create, modify, export, import and delete.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfBookmarkEditor()](#PdfBookmarkEditor--) | Initializes new  PdfBookmarkEditor  object. |
| [PdfBookmarkEditor(IDocument document)](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Initializes new  PdfBookmarkEditor  object on base of the  document . |
## Methods

| Method | Description |
| --- | --- |
| [createBookmarks()](#createBookmarks--) | Creates bookmarks for all pages. |
| [createBookmarkOfPage(String bookmarkName, int pageNumber)](#createBookmarkOfPage-java.lang.String-int-) | Creates bookmark for the specified page. |
| [createBookmarks(Bookmark bookmark)](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | Creates the specified bookmark in the document. |
| [createBookmarks(Color color, boolean boldFlag, boolean italicFlag)](#createBookmarks-java.awt.Color-boolean-boolean-) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)](#createBookmarkOfPage-java.lang.String---int---) | Creates bookmarks for the specified pages. |
| [deleteBookmarks()](#deleteBookmarks--) | Deletes all bookmarks of the PDF document. |
| [deleteBookmarks(String title)](#deleteBookmarks-java.lang.String-) | Deletes the bookmark of the PDF document. |
| [modifyBookmarks(String sTitle, String dTitle)](#modifyBookmarks-java.lang.String-java.lang.String-) | Modifys bookmark title according to the specified bookmark title. |
| [extractBookmarks()](#extractBookmarks--) | Extracts bookmarks of all levels from the document. |
| [extractBookmarks(boolean upperLevel)](#extractBookmarks-boolean-) | Extracts bookmarks of all levels from the document. |
| [extractBookmarks(String title)](#extractBookmarks-java.lang.String-) | Extracts the bookmarks with the specified title. |
| [extractBookmarks(Bookmark bookmark)](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [extractBookmarksToHTML(String pdfFile, String cssFile)](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | Exports bookmarks to HTML file. |
| [exportBookmarksToXML(String xmlFile)](#exportBookmarksToXML-java.lang.String-) | Exports bookmarks to XML file. |
| [exportBookmarksToXML(OutputStream output)](#exportBookmarksToXML-java.io.OutputStream-) | Exports bookmarks to XML stream. |
| [importBookmarksWithXML(String xmlFile)](#importBookmarksWithXML-java.lang.String-) | Imports bookmarks to the document from XML file. |
| [importBookmarksWithXML(InputStream stream)](#importBookmarksWithXML-java.io.InputStream-) | Imports bookmarks to the document from XML file. |
| [exportBookmarksToHtml(String inPdfFile, String outHtmlFile)](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | Exports bookmarks to HTML file. |
| [close()](#close--) | Close the instance of PdfBookmarkEditor and release the resources. |
### PdfBookmarkEditor() {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```


Initializes new  PdfBookmarkEditor  object.

### PdfBookmarkEditor(IDocument document) {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
```
public PdfBookmarkEditor(IDocument document)
```


Initializes new  PdfBookmarkEditor  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### createBookmarks() {#createBookmarks--}
```
public void createBookmarks()
```


Creates bookmarks for all pages.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks();
 editor.save("example_out.pdf");
```

### createBookmarkOfPage(String bookmarkName, int pageNumber) {#createBookmarkOfPage-java.lang.String-int-}
```
public void createBookmarkOfPage(String bookmarkName, int pageNumber)
```


Creates bookmark for the specified page.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | java.lang.String | The specified bookmark name. |
| pageNumber | int | The specified desination page. |

### createBookmarks(Bookmark bookmark) {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public void createBookmarks(Bookmark bookmark)
```


Creates the specified bookmark in the document. The method can be used for forming nested bookmarks hierarchy.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
  Bookmark bm1=new Bookmark();
  bm1.setPageNumber(1);
  bm1.setTitle("First child");
 	Bookmark bm2=new Bookmark();
 	bm2.setPageNumber(2);
  bm2.setTitle("Second child");
  Bookmark bm=new Bookmark();
  bm.setAction=(GoTo");
  bm.setPageNumber(1);
  bm.setTitle("Parent");
  Bookmarks bms=new Bookmarks();
  bms.add(bm1);
  bms.add(bm2);
  bm.setChildItem(bms);
  editor.setCreateBookmarks(bm);
  editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | The bookmark will be added to the document. |

### createBookmarks(Color color, boolean boldFlag, boolean italicFlag) {#createBookmarks-java.awt.Color-boolean-boolean-}
```
public void createBookmarks(Color color, boolean boldFlag, boolean italicFlag)
```


Create bookmarks for all pages with specified color and style (bold, italic).

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarks(System.Drawing.Color.Red, true, true);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | java.awt.Color | The color of title. |
| boldFlag | boolean | The flag of bold attribution. |
| italicFlag | boolean | The flag of italic attribution. |

### createBookmarkOfPage(String[] bookmarkName, int[] pageNumber) {#createBookmarkOfPage-java.lang.String---int---}
```
public void createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)
```


Creates bookmarks for the specified pages.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.createBookmarkOfPage("bookmark for page 1", 1);
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bookmarkName | java.lang.String[] | Bookmarks title array. |
| pageNumber | int[] | Bookmarks desination page array. |

### deleteBookmarks() {#deleteBookmarks--}
```
public void deleteBookmarks()
```


Deletes all bookmarks of the PDF document.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks();
 editor.save("example_out.pdf");
```

### deleteBookmarks(String title) {#deleteBookmarks-java.lang.String-}
```
public void deleteBookmarks(String title)
```


Deletes the bookmark of the PDF document.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.deleteBookmarks("existing bookmark title");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | The title of bookmark deleted. |

### modifyBookmarks(String sTitle, String dTitle) {#modifyBookmarks-java.lang.String-java.lang.String-}
```
public void modifyBookmarks(String sTitle, String dTitle)
```


Modifys bookmark title according to the specified bookmark title.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.modifyBookmarks("existing bookmark title", "new bookmark title");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sTitle | java.lang.String | Source bookmark title. |
| dTitle | java.lang.String | Modified bookmark title. |

### extractBookmarks() {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```


Extracts bookmarks of all levels from the document.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmarks bms = editor.ExtractBookmarks();
 for(Bookmark bm : bms)
     System.out.println(bm.Title);
```

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - The bookmarks collection of all bookmarks that exist in the document.
### extractBookmarks(boolean upperLevel) {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```


Extracts bookmarks of all levels from the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| upperLevel | boolean | If true, extracts only upper level bookmarks. Else, extracts all bookmarks recursively. |

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - List of extracted bookmarks.
### extractBookmarks(String title) {#extractBookmarks-java.lang.String-}
```
public Bookmarks extractBookmarks(String title)
```


Extracts the bookmarks with the specified title.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
  editor.bindPdf("example.pdf");
 	Bookmarks bms = editor.ExtractBookmarks("Title");
  for(Bookmark bm : ```
(Iterable)
```bms)
      System.out.println(bm.Title);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| title | java.lang.String | Extracted item title. |

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Bookmark object collection has items with the same title.
### extractBookmarks(Bookmark bookmark) {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
```
public Bookmarks extractBookmarks(Bookmark bookmark)
```


Extracts the children of a bookmark with a title like in specified bookamrk.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 Bookmark bookmark = new Bookmark();
 bookmark.setTitle ( "Title");
 Bookmarks bms = editor.ExtractBookmarks(bookmark);
 for(Bookmark bm : ```
(Iterable)
```bms)
     System.out.println(bm.Title);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bookmark | [Bookmark](../../com.aspose.pdf.facades/bookmark) | The specified bookamrk. |

**Returns:**
[Bookmarks](../../com.aspose.pdf.facades/bookmarks) - Bookmark collection with child bookmarks.
### extractBookmarksToHTML(String pdfFile, String cssFile) {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
```
public void extractBookmarksToHTML(String pdfFile, String cssFile)
```


Exports bookmarks to HTML file.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.extractBookmarksToHTML("example.pdf", null);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfFile | java.lang.String | The PDF file which bookmarks will be exported. |
| cssFile | java.lang.String | The CSS file to display HTML file, can be null. |

### exportBookmarksToXML(String xmlFile) {#exportBookmarksToXML-java.lang.String-}
```
public void exportBookmarksToXML(String xmlFile)
```


Exports bookmarks to XML file.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.exportBookmarksToXML("bookmarks.xml");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The output XML file. |

### exportBookmarksToXML(OutputStream output) {#exportBookmarksToXML-java.io.OutputStream-}
```
public void exportBookmarksToXML(OutputStream output)
```


Exports bookmarks to XML stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Output stream where data will be stored. |

### importBookmarksWithXML(String xmlFile) {#importBookmarksWithXML-java.lang.String-}
```
public void importBookmarksWithXML(String xmlFile)
```


Imports bookmarks to the document from XML file.

--------------------

```
PdfBookmarkEditor editor = new PdfBookmarkEditor();
 editor.bindPdf("example.pdf");
 editor.importBookmarksWithXML("bookmarks.xml");
 editor.save("example_out.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlFile | java.lang.String | The XML file containing bookmarks list. |

### importBookmarksWithXML(InputStream stream) {#importBookmarksWithXML-java.io.InputStream-}
```
public void importBookmarksWithXML(InputStream stream)
```


Imports bookmarks to the document from XML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream with bookmarks data. |

### exportBookmarksToHtml(String inPdfFile, String outHtmlFile) {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
```
public static void exportBookmarksToHtml(String inPdfFile, String outHtmlFile)
```


Exports bookmarks to HTML file.

--------------------

```
PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inPdfFile | java.lang.String | Input PDF file which bookmarks will be exported. |
| outHtmlFile | java.lang.String | Output HTML file |

### close() {#close--}
```
public void close()
```


Close the instance of PdfBookmarkEditor and release the resources.

