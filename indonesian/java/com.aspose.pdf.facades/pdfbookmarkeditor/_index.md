---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk bekerja dengan bookmark file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus."
type: docs
weight: 370
url: /id/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

Mewakili kelas untuk bekerja dengan bookmark file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Menginisialisasi objek {@code PdfBookmarkEditor} baru. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Menginisialisasi objek {@code PdfBookmarkEditor} baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [close](#close--) | Tutup instance PdfBookmarkEditor dan lepaskan sumber daya. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Membuat bookmark untuk halaman yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Membuat bookmark untuk halaman yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> Menghapus semua bookmark dari dokumen PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> Menghapus semua bookmark dari dokumen PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Mengekspor bookmark ke file HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Mengekspor bookmark ke aliran XML. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Mengekspor bookmark ke file XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Mengekstrak bookmark dari semua level dalam dokumen. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Mengekspor bookmark ke file HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Mengimpor bookmark ke dokumen dari file XML. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Mengimpor bookmark ke dokumen dari file XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Memodifikasi judul bookmark sesuai dengan judul bookmark yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Menginisialisasi objek {@code PdfBookmarkEditor} baru.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Menginisialisasi objek {@code PdfBookmarkEditor} baru.

### close {#close--}
```
public void close()
```

Tutup instance PdfBookmarkEditor dan lepaskan sumber daya.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Membuat bookmark untuk halaman yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Membuat bookmark untuk halaman yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Membuat bookmark untuk semua halaman. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> Menghapus semua bookmark dari dokumen PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> Menghapus semua bookmark dari dokumen PDF. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Mengekspor bookmark ke file HTML. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML(\"example.pdf\", \"bookmarks.html\"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Mengekspor bookmark ke aliran XML.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Mengekspor bookmark ke file XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.exportBookmarksToXML(\"bookmarks.xml\"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Koleksi bookmark dari semua bookmark yang ada dalam dokumen.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Koleksi bookmark dari semua bookmark yang ada dalam dokumen.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Mengekstrak bookmark dari semua level dalam dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| upperLevel |  | Jika true, mengekstrak hanya bookmark level atas. Jika false, mengekstrak semua bookmark secara rekursif. |

**Returns:**
Daftar bookmark yang diekstrak.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Mengekstrak bookmark dari semua level dalam dokumen. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Koleksi bookmark dari semua bookmark yang ada dalam dokumen.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Mengekspor bookmark ke file HTML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML(\"example.pdf\", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Mengimpor bookmark ke dokumen dari file XML.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Mengimpor bookmark ke dokumen dari file XML. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.importBookmarksWithXML(\"bookmarks.xml\"); editor.save(\"example_out.pdf\"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Memodifikasi judul bookmark sesuai dengan judul bookmark yang ditentukan. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf(\"example.pdf\"); editor.modifyBookmarks(\"existing bookmark title\", \"new bookmark title\"); editor.save(\"example_out.pdf\"); </pre>
