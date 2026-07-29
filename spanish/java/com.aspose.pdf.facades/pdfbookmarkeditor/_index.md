---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar."
type: docs
weight: 370
url: /es/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Representa una clase para trabajar con los marcadores de archivos PDF, incluyendo crear, modificar, exportar, importar y eliminar.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Inicializa un nuevo objeto {@code PdfBookmarkEditor}. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Inicializa un nuevo objeto {@code PdfBookmarkEditor}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Cierra la instancia de PdfBookmarkEditor y libera los recursos. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Crea marcadores para las páginas especificadas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Crea un marcador para la página especificada. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Elimina todos los marcadores del documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Elimina todos los marcadores del documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Exporta marcadores a un archivo HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Exporta marcadores a un flujo XML. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Exporta marcadores a un archivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Extrae los marcadores de todos los niveles del documento. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Exporta marcadores a un archivo HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Importa marcadores al documento desde un archivo XML. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Importa marcadores al documento desde un archivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Modifica el título del marcador según el título especificado del marcador. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Inicializa un nuevo objeto {@code PdfBookmarkEditor}.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Inicializa un nuevo objeto {@code PdfBookmarkEditor}.

### close {#close--}
```
public void close()
```

Cierra la instancia de PdfBookmarkEditor y libera los recursos.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Crea marcadores para las páginas especificadas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Crea un marcador para la página especificada. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Crea marcadores para todas las páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Elimina todos los marcadores del documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Elimina todos los marcadores del documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Exporta marcadores a un archivo HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Exporta marcadores a un flujo XML.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Exporta marcadores a un archivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La colección de marcadores de todos los marcadores que existen en el documento.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La colección de marcadores de todos los marcadores que existen en el documento.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Extrae los marcadores de todos los niveles del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| upperLevel |  | Si es verdadero, extrae solo los marcadores de nivel superior. De lo contrario, extrae todos los marcadores recursivamente. |

**Returns:**
Lista de marcadores extraídos.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Extrae los marcadores de todos los niveles del documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La colección de marcadores de todos los marcadores que existen en el documento.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Exporta marcadores a un archivo HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Importa marcadores al documento desde un archivo XML.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Importa marcadores al documento desde un archivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Modifica el título del marcador según el título especificado del marcador. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre>
