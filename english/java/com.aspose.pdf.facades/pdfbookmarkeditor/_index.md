---
title: PdfBookmarkEditor
second_title: Aspose.PDF for Java API Reference
description: Represents a class to work with PDF files bookmarks including create modify export import and delete.
type: docs
weight: 35
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
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Close the instance of PdfBookmarkEditor and release the resources. |
| [createBookmarkOfPage(String bookmarkName, int pageNumber)](#createBookmarkOfPage-java.lang.String-int-) | Creates bookmark for the specified page. |
| [createBookmarkOfPage(String[] bookmarkName, int[] pageNumber)](#createBookmarkOfPage-java.lang.String---int---) | Creates bookmarks for the specified pages. |
| [createBookmarks()](#createBookmarks--) | Creates bookmarks for all pages. |
| [createBookmarks(Bookmark bookmark)](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | Creates the specified bookmark in the document. |
| [createBookmarks(Color color, boolean boldFlag, boolean italicFlag)](#createBookmarks-java.awt.Color-boolean-boolean-) | Create bookmarks for all pages with specified color and style (bold, italic). |
| [deleteBookmarks()](#deleteBookmarks--) | Deletes all bookmarks of the PDF document. |
| [deleteBookmarks(String title)](#deleteBookmarks-java.lang.String-) | Deletes the bookmark of the PDF document. |
| [dispose()](#dispose--) | Disposes the facade. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [exportBookmarksToHtml(String inPdfFile, String outHtmlFile)](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | Exports bookmarks to HTML file. |
| [exportBookmarksToXML(OutputStream output)](#exportBookmarksToXML-java.io.OutputStream-) | Exports bookmarks to XML stream. |
| [exportBookmarksToXML(String xmlFile)](#exportBookmarksToXML-java.lang.String-) | Exports bookmarks to XML file. |
| [extractBookmarks()](#extractBookmarks--) | Extracts bookmarks of all levels from the document. |
| [extractBookmarks(boolean upperLevel)](#extractBookmarks-boolean-) | Extracts bookmarks of all levels from the document. |
| [extractBookmarks(Bookmark bookmark)](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | Extracts the children of a bookmark with a title like in specified bookamrk. |
| [extractBookmarks(String title)](#extractBookmarks-java.lang.String-) | Extracts the bookmarks with the specified title. |
| [extractBookmarksToHTML(String pdfFile, String cssFile)](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | Exports bookmarks to HTML file. |
| [getClass()](#getClass--) |  |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [hashCode()](#hashCode--) |  |
| [importBookmarksWithXML(InputStream stream)](#importBookmarksWithXML-java.io.InputStream-) | Imports bookmarks to the document from XML file. |
| [importBookmarksWithXML(String xmlFile)](#importBookmarksWithXML-java.lang.String-) | Imports bookmarks to the document from XML file. |
| [modifyBookmarks(String sTitle, String dTitle)](#modifyBookmarks-java.lang.String-java.lang.String-) | Modifys bookmark title according to the specified bookmark title. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves the PDF document to the specified stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves the PDF document to the specified file. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
public void close()
```


Close the instance of PdfBookmarkEditor and release the resources.

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

### dispose() {#dispose--}
```
public void dispose()
```


Disposes the facade.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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

### exportBookmarksToXML(OutputStream output) {#exportBookmarksToXML-java.io.OutputStream-}
```
public void exportBookmarksToXML(OutputStream output)
```


Exports bookmarks to XML stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| output | java.io.OutputStream | Output stream where data will be stored. |

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

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### importBookmarksWithXML(InputStream stream) {#importBookmarksWithXML-java.io.InputStream-}
```
public void importBookmarksWithXML(InputStream stream)
```


Imports bookmarks to the document from XML file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream with bookmarks data. |

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

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves the PDF document to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | The destination stream. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves the PDF document to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | The destination file. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

