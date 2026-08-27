---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir."
type: docs
weight: 370
url: /pt/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Inicializa um novo objeto {@code PdfBookmarkEditor}. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Inicializa um novo objeto {@code PdfBookmarkEditor}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [close](#close--) | Fecha a instância de PdfBookmarkEditor e libera os recursos. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Cria marcadores para as páginas especificadas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Cria marcador para a página especificada. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Exclui todos os marcadores do documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Exclui todos os marcadores do documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Exporta marcadores para um arquivo HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Exporta marcadores para um fluxo XML. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Exporta marcadores para um arquivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Extrai marcadores de todos os níveis do documento. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Exporta marcadores para um arquivo HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Importa marcadores para o documento a partir de um arquivo XML. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Importa marcadores para o documento a partir de um arquivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Modifica o título do marcador de acordo com o título de marcador especificado. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Inicializa um novo objeto {@code PdfBookmarkEditor}.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Inicializa um novo objeto {@code PdfBookmarkEditor}.

### close {#close--}
```
public void close()
```

Fecha a instância de PdfBookmarkEditor e libera os recursos.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Cria marcadores para as páginas especificadas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Cria marcador para a página especificada. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Cria marcadores para todas as páginas. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Exclui todos os marcadores do documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Exclui todos os marcadores do documento PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Exporta marcadores para um arquivo HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Exporta marcadores para um fluxo XML.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Exporta marcadores para um arquivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
A coleção de marcadores de todos os marcadores que existem no documento.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
A coleção de marcadores de todos os marcadores que existem no documento.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Extrai marcadores de todos os níveis do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| upperLevel |  | Se verdadeiro, extrai apenas marcadores de nível superior. Caso contrário, extrai todos os marcadores recursivamente. |

**Returns:**
Lista de marcadores extraídos.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Extrai marcadores de todos os níveis do documento. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
A coleção de marcadores de todos os marcadores que existem no documento.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Exporta marcadores para um arquivo HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Importa marcadores para o documento a partir de um arquivo XML.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Importa marcadores para o documento a partir de um arquivo XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Modifica o título do marcador de acordo com o título de marcador especificado. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre>
