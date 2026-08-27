---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour gérer les signets d'un fichier PDF, y compris la création, la modification, l'exportation, l'importation et la suppression."
type: docs
weight: 370
url: /fr/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Représente une classe pour gérer les signets d'un fichier PDF, y compris la création, la modification, l'exportation, l'importation et la suppression.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Initialise un nouvel objet {@code PdfBookmarkEditor}. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Initialise un nouvel objet {@code PdfBookmarkEditor}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Ferme l'instance de PdfBookmarkEditor et libère les ressources. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Crée des signets pour les pages spécifiées. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Crée un signet pour la page spécifiée. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Supprime tous les signets du document PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Supprime tous les signets du document PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Exporte les signets vers un fichier HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Exporte les signets vers un flux XML. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Exporte les signets vers un fichier XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Extrait les signets de tous les niveaux du document. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Exporte les signets vers un fichier HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Importe les signets dans le document à partir d'un fichier XML. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Importe les signets dans le document à partir d'un fichier XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Modifie le titre du signet selon le titre de signet spécifié. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Initialise un nouvel objet {@code PdfBookmarkEditor}.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Initialise un nouvel objet {@code PdfBookmarkEditor}.

### close {#close--}
```
public void close()
```

Ferme l'instance de PdfBookmarkEditor et libère les ressources.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Crée des signets pour les pages spécifiées. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Crée un signet pour la page spécifiée. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Crée des signets pour toutes les pages. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Supprime tous les signets du document PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Supprime tous les signets du document PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Exporte les signets vers un fichier HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Exporte les signets vers un flux XML.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Exporte les signets vers un fichier XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La collection de signets contenant tous les signets présents dans le document.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La collection de signets contenant tous les signets présents dans le document.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Extrait les signets de tous les niveaux du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| upperLevel |  | Si vrai, extrait uniquement les signets de niveau supérieur. Sinon, extrait tous les signets de manière récursive. |

**Returns:**
Liste des signets extraits.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Extrait les signets de tous les niveaux du document. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
La collection de signets contenant tous les signets présents dans le document.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Exporte les signets vers un fichier HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Importe les signets dans le document à partir d'un fichier XML.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Importe les signets dans le document à partir d'un fichier XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Modifie le titre du signet selon le titre de signet spécifié. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre>
