---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att arbeta med PDF-fils bokmärken inklusive skapa, ändra, exportera, importera och ta bort."
type: docs
weight: 370
url: /sv/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Representerar en klass för att arbeta med PDF-fils bokmärken inklusive skapa, ändra, exportera, importera och ta bort.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Initierar ett nytt {@code PdfBookmarkEditor} objekt. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Initierar ett nytt {@code PdfBookmarkEditor} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [close](#close--) | Stäng instansen av PdfBookmarkEditor och frigör resurserna. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Skapar bokmärken för de angivna sidorna. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Skapar bokmärke för den angivna sidan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Tar bort alla bokmärken i PDF-dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Tar bort alla bokmärken i PDF-dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Exporterar bokmärken till en HTML-fil. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Exporterar bokmärken till en XML-ström. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Exporterar bokmärken till en XML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Extraherar bokmärken på alla nivåer från dokumentet. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Exporterar bokmärken till en HTML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Importerar bokmärken till dokumentet från en XML-fil. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Importerar bokmärken till dokumentet från en XML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Modifierar bokmärkestitel enligt den angivna bokmärkestiteln. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Initierar ett nytt {@code PdfBookmarkEditor} objekt.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Initierar ett nytt {@code PdfBookmarkEditor} objekt.

### close {#close--}
```
public void close()
```

Stäng instansen av PdfBookmarkEditor och frigör resurserna.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Skapar bokmärken för de angivna sidorna. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Skapar bokmärke för den angivna sidan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Skapar bokmärken för alla sidor. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Tar bort alla bokmärken i PDF-dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Tar bort alla bokmärken i PDF-dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Exporterar bokmärken till en HTML-fil. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Exporterar bokmärken till en XML-ström.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Exporterar bokmärken till en XML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Bokmärkeskollektionen av alla bokmärken som finns i dokumentet.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Bokmärkeskollektionen av alla bokmärken som finns i dokumentet.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Extraherar bokmärken på alla nivåer från dokumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| upperLevel |  | Om true, extraherar endast bokmärken på översta nivån. Annars extraheras alla bokmärken rekursivt. |

**Returns:**
Lista över extraherade bokmärken.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Extraherar bokmärken på alla nivåer från dokumentet. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Bokmärkeskollektionen av alla bokmärken som finns i dokumentet.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Exporterar bokmärken till en HTML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Importerar bokmärken till dokumentet från en XML-fil.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Importerar bokmärken till dokumentet från en XML-fil. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Modifierar bokmärkestitel enligt den angivna bokmärkestiteln. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
