---
title: "PdfBookmarkEditor"
linktitle: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF dosyasının yer imleriyle (oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme dahil) çalışmak için bir sınıfı temsil eder."
type: docs
weight: 370
url: /tr/java/com.aspose.pdf.facades/pdfbookmarkeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfBookmarkEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfBookmarkEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfBookmarkEditor extends SaveableFacade
```

PDF dosyasının yer imleriyle (oluşturma, değiştirme, dışa aktarma, içe aktarma ve silme dahil) çalışmak için bir sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfBookmarkEditor](#PdfBookmarkEditor--) | Yeni {@code PdfBookmarkEditor} nesnesini başlatır. |
| [PdfBookmarkEditor](#PdfBookmarkEditor-com.aspose.pdf.IDocument-) | Yeni {@code PdfBookmarkEditor} nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close](#close--) | PdfBookmarkEditor örneğini kapatır ve kaynakları serbest bırakır. |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String:A-int:A-) | <p> Belirtilen sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarkOfPage](#createBookmarkOfPage-java.lang.String-int-) | <p> Belirtilen sayfa için yer imi oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks--) | <p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [createBookmarks](#createBookmarks-java.awt.Color-boolean-boolean-) | <p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks--) | <p> PDF belgesinin tüm yer imlerini siler. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [deleteBookmarks](#deleteBookmarks-java.lang.String-) | <p> PDF belgesinin tüm yer imlerini siler. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre> |
| [exportBookmarksToHtml](#exportBookmarksToHtml-java.lang.String-java.lang.String-) | <p> Yer imlerini HTML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre> |
| [exportBookmarksToXML](#exportBookmarksToXML-java.io.OutputStream-) | Yer imlerini XML akışına dışa aktarır. |
| [exportBookmarksToXML](#exportBookmarksToXML-java.lang.String-) | <p> Yer imlerini XML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre> |
| [extractBookmarks](#extractBookmarks--) | <p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-com.aspose.pdf.facades.Bookmark-) | <p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarks](#extractBookmarks-boolean-) | Belgeden tüm seviyelerdeki yer imlerini çıkarır. |
| [extractBookmarks](#extractBookmarks-java.lang.String-) | <p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre> |
| [extractBookmarksToHTML](#extractBookmarksToHTML-java.lang.String-java.lang.String-) | <p> Yer imlerini HTML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre> |
| [importBookmarksWithXML](#importBookmarksWithXML-java.io.InputStream-) | Yer imlerini XML dosyasından belgeye içe aktarır. |
| [importBookmarksWithXML](#importBookmarksWithXML-java.lang.String-) | <p> Yer imlerini XML dosyasından belgeye içe aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre> |
| [modifyBookmarks](#modifyBookmarks-java.lang.String-java.lang.String-) | <p> Yer imi başlığını belirtilen yer imi başlığına göre değiştirir. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre> |

### PdfBookmarkEditor {#PdfBookmarkEditor--}
```
public PdfBookmarkEditor()
```

Yeni {@code PdfBookmarkEditor} nesnesini başlatır.

### PdfBookmarkEditor {#PdfBookmarkEditor-com.aspose.pdf.IDocument-}
Yeni {@code PdfBookmarkEditor} nesnesini başlatır.

### close {#close--}
```
public void close()
```

PdfBookmarkEditor örneğini kapatır ve kaynakları serbest bırakır.

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String:A-int:A-}
<p> Belirtilen sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarkOfPage {#createBookmarkOfPage-java.lang.String-int-}
<p> Belirtilen sayfa için yer imi oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarkOfPage("bookmark for page 1", 1); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks--}
```
public void createBookmarks()
```

<p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### createBookmarks {#createBookmarks-java.awt.Color-boolean-boolean-}
<p> Tüm sayfalar için yer imleri oluşturur. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.createBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks--}
```
public void deleteBookmarks()
```

<p> PDF belgesinin tüm yer imlerini siler. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### deleteBookmarks {#deleteBookmarks-java.lang.String-}
<p> PDF belgesinin tüm yer imlerini siler. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.deleteBookmarks(); editor.save("example_out.pdf"); </pre>

### exportBookmarksToHtml {#exportBookmarksToHtml-java.lang.String-java.lang.String-}
<p> Yer imlerini HTML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor.extractBookmarksToHTML("example.pdf", "bookmarks.html"); </pre>

### exportBookmarksToXML {#exportBookmarksToXML-java.io.OutputStream-}
Yer imlerini XML akışına dışa aktarır.

### exportBookmarksToXML {#exportBookmarksToXML-java.lang.String-}
<p> Yer imlerini XML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.exportBookmarksToXML("bookmarks.xml"); </pre>

### extractBookmarks {#extractBookmarks--}
```
public Bookmarks extractBookmarks()
```

<p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Belgede mevcut olan tüm yer imlerinin koleksiyonu.

### extractBookmarks {#extractBookmarks-com.aspose.pdf.facades.Bookmark-}
<p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Belgede mevcut olan tüm yer imlerinin koleksiyonu.

### extractBookmarks {#extractBookmarks-boolean-}
```
public Bookmarks extractBookmarks(boolean upperLevel)
```

Belgeden tüm seviyelerdeki yer imlerini çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| upperLevel |  | Doğru ise, yalnızca üst seviye yer imlerini çıkarır. Aksi takdirde, tüm yer imlerini özyinelemeli olarak çıkarır. |

**Returns:**
Çıkarılan yer imlerinin listesi.

### extractBookmarks {#extractBookmarks-java.lang.String-}
<p> Belgeden tüm seviyelerdeki yer imlerini çıkarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); Bookmarks bms = editor.ExtractBookmarks(); for(Bookmark bm : bms) System.out.println(bm.Title); </pre>

**Returns:**
Belgede mevcut olan tüm yer imlerinin koleksiyonu.

### extractBookmarksToHTML {#extractBookmarksToHTML-java.lang.String-java.lang.String-}
<p> Yer imlerini HTML dosyasına dışa aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.extractBookmarksToHTML("example.pdf", null); </pre>

### importBookmarksWithXML {#importBookmarksWithXML-java.io.InputStream-}
Yer imlerini XML dosyasından belgeye içe aktarır.

### importBookmarksWithXML {#importBookmarksWithXML-java.lang.String-}
<p> Yer imlerini XML dosyasından belgeye içe aktarır. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.importBookmarksWithXML("bookmarks.xml"); editor.save("example_out.pdf"); </pre>

### modifyBookmarks {#modifyBookmarks-java.lang.String-java.lang.String-}
<p> Yer imi başlığını belirtilen yer imi başlığına göre değiştirir. </p> <hr> <pre> PdfBookmarkEditor editor = new PdfBookmarkEditor(); editor.bindPdf("example.pdf"); editor.modifyBookmarks("existing bookmark title", "new bookmark title"); editor.save("example_out.pdf"); </pre>
