---
title: "PdfContentEditor"
linktitle: "PdfContentEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk mengedit konten file PDF."
type: docs
weight: 380
url: /id/java/com.aspose.pdf.facades/pdfcontenteditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfContentEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfContentEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfContentEditor extends SaveableFacade
```

Mewakili kelas untuk mengedit konten file PDF.

## Fields

| Field | Deskripsi |
| --- | --- |
| [DOCUMENT_CLOSE](#DOCUMENT_CLOSE) | Tipe peristiwa dokumen. Menutup sebuah dokumen. |
| [DOCUMENT_OPEN](#DOCUMENT_OPEN) | Tipe peristiwa dokumen. Membuka sebuah dokumen. |
| [DOCUMENT_PRINTED](#DOCUMENT_PRINTED) | Tipe peristiwa dokumen. Menjalankan aksi setelah pencetakan. |
| [DOCUMENT_SAVED](#DOCUMENT_SAVED) | Tipe peristiwa dokumen. Menjalankan aksi setelah penyimpanan. |
| [DOCUMENT_WILL_PRINT](#DOCUMENT_WILL_PRINT) | Tipe peristiwa dokumen. Menjalankan aksi sebelum pencetakan. |
| [DOCUMENT_WILL_SAVE](#DOCUMENT_WILL_SAVE) | Tipe peristiwa dokumen. Menjalankan aksi sebelum penyimpanan. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfContentEditor](#PdfContentEditor--) | Konstruktor dari objek PdfContentEditor. |
| [PdfContentEditor](#PdfContentEditor-com.aspose.pdf.IDocument-) | Konstruktor dari objek PdfContentEditor. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addDocumentAdditionalAction](#addDocumentAdditionalAction-java.lang.String-java.lang.String-) | <p> Menambahkan aksi tambahan untuk peristiwa dokumen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-) | <p> Menambahkan lampiran dokumen tanpa anotasi. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [addDocumentAttachment](#addDocumentAttachment-java.lang.String-java.lang.String-) | <p> Menambahkan lampiran dokumen tanpa anotasi. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre> |
| [bindPdf](#bindPdf-java.io.InputStream-) | Mengikat aliran PDF untuk penyuntingan. |
| [bindPdf](#bindPdf-java.lang.String-) | Mengikat file PDF untuk penyuntingan. |
| [changeViewerPreference](#changeViewerPreference-int-) | <p> Mengubah preferensi tampilan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre> |
| [close](#close--) | Menutup dokumen yang dibuka. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-) | Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF. |
| [createApplicationLink](#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF. |
| [createBookmarksAction](#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-) | Membuat penanda dengan aksi yang ditentukan. |
| [createCaret](#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Membuat anotasi caret. |
| [createCustomActionLink](#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Membuat tautan ke aksi khusus dalam dokumen PDF. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-) | Membuat anotasi lampiran file. |
| [createFileAttachment](#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) | Membuat anotasi lampiran file. |
| [createFreeText](#createFreeText-java.awt.Rectangle-java.lang.String-int-) | Membuat anotasi teks bebas dalam dokumen PDF |
| [createJavaScriptLink](#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-) | Membuat tautan ke JavaScript dalam dokumen PDF. |
| [createLine](#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-) | Membuat anotasi garis. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-) | Membuat tautan lokal dalam dokumen PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-) | Membuat tautan lokal dalam dokumen PDF. |
| [createLocalLink](#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Membuat tautan lokal dalam dokumen PDF. |
| [createMarkup](#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Membuat anotasi markup di dokumen PDF. |
| [createMovie](#createMovie-java.awt.Rectangle-java.lang.String-int-) |  |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-) | Membuat tautan ke halaman dokumen PDF lain. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-) | Membuat tautan ke halaman dokumen PDF lain. |
| [createPdfDocumentLink](#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Membuat tautan ke halaman dokumen PDF lain. |
| [createPolygon](#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Membuat anotasi poligon. |
| [createPolyLine](#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Membuat anotasi polyline. |
| [createPopup](#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-) | Membuat anotasi popup dalam dokumen PDF. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-) | Membuat anotasi stempel karet. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-) | Membuat anotasi stempel karet. |
| [createRubberStamp](#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-) | Membuat anotasi stempel karet. |
| [createSound](#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-) |  |
| [createSquareCircle](#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-) | Membuat anotasi kotak-lingkaran. |
| [createText](#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-) | Membuat anotasi teks dalam dokumen PDF |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-) | Membuat tautan web dalam dokumen PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-) | Membuat tautan web dalam dokumen PDF. |
| [createWebLink](#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-) | Membuat tautan web dalam dokumen PDF. |
| [deleteAttachments](#deleteAttachments--) | <p> Menghapus semua lampiran dalam dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage--) | <p> Menghapus semua gambar dari dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre> |
| [deleteImage](#deleteImage-int-int:A-) | <p> Menghapus gambar yang ditentukan pada halaman yang ditentukan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre> |
| [deleteStamp](#deleteStamp-int-int:A-) | <p> Menghapus beberapa stempel pada halaman yang ditentukan berdasarkan indeks stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-) | <p> Menghapus stempel berdasarkan ID dari semua halaman dokumen. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampById](#deleteStampById-int-int-) | <p> Menghapus stempel pada halaman yang ditentukan berdasarkan ID stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int:A-) | <p> Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre> |
| [deleteStampByIds](#deleteStampByIds-int-int:A-) | <p> Menghapus stempel pada halaman yang ditentukan berdasarkan beberapa ID stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre> |
| [drawCurve](#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-) | Membuat anotasi kurva. |
| [extractLink](#extractLink--) | <p> Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre> |
| [getReplaceTextStrategy](#getReplaceTextStrategy--) | Dapatkan sekumpulan parameter untuk operasi penggantian teks |
| [getStamps](#getStamps-int-) | Mengembalikan array stempel pada halaman. |
| [getTextEditOptions](#getTextEditOptions--) | Mendapatkan opsi penyuntingan teks. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | Mendapatkan opsi penggantian teks. |
| [getTextSearchOptions](#getTextSearchOptions--) | Mendapatkan opsi pencarian teks. |
| [getViewerPreference](#getViewerPreference--) | <p> Mengembalikan preferensi tampilan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre> |
| [hideStampById](#hideStampById-int-int-) | Menyembunyikan stempel. Setelah disembunyikan, visibilitas stempel dapat dipulihkan dengan metode ShowStampById. |
| [moveStamp](#moveStamp-int-int-double-double-) | Mengubah posisi stempel pada halaman. |
| [moveStampById](#moveStampById-int-int-double-double-) | Mengubah posisi stempel pada halaman. |
| [removeDocumentOpenAction](#removeDocumentOpenAction--) | <p> Menghapus aksi buka dari dokumen. Operasi ini berguna saat menggabungkan beberapa dokumen yang menggunakan aksi 'GoTo' eksplisit saat memulai. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre> |
| [replaceImage](#replaceImage-int-int-java.lang.String-) | <p> Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-) | <p> Mengganti teks dalam file PDF pada halaman yang ditentukan. </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file on the specified page. {@code TextState} object (font family, color) can be specified to replaced text. </p> <hr> <pre> The example demonstrates how to replace text on the first page of the PDF document and set {@code TextState} text properties for the new text. // open document Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", 1, "hi world", textState); // simpan dokumen doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-) | <p> Mengganti teks dalam file PDF. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF. Secara default, ia mengganti teks pertama yang ditemukan. // buka dokumen Document doc = new Document(inFile); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ubah teks editor.replaceText("hello world", "hi world"); // simpan dokumen doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-int-) | <p> Mengganti teks dalam file PDF dan mengatur ukuran font. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks dan mengatur ukuran font untuk teks baru. // buka dokumen Document doc = new Document(inFile); // Buat font dan tandai untuk disematkan com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", "hi world", 14); // simpan dokumen doc.save(outFile); </pre> |
| [replaceText](#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-) | <p> Replaces text in the PDF file using specified {@code TextState} object. </p> <hr> <pre> The example demonstrates how to replace text and set {@code TextState} text properties for the new text. Document doc = new Document(inFile); // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // create textState object com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold \ | com.aspose.pdf.FontStyles.Italic); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", "hi world", textState); // simpan dokumen doc.save(outFile); </pre> |
| [setReplaceTextStrategy](#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-) | Atur sekumpulan parameter untuk operasi mengganti teks |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | Mengatur opsi penyuntingan teks. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | Mengatur opsi penggantian teks. |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Mengatur opsi pencarian teks. |
| [showStampById](#showStampById-int-int-) | Menampilkan stempel yang disembunyikan oleh HiddenStampById. |

### DOCUMENT_CLOSE {#DOCUMENT_CLOSE}
```
public static final String DOCUMENT_CLOSE
```

Tipe peristiwa dokumen. Menutup sebuah dokumen.

### DOCUMENT_OPEN {#DOCUMENT_OPEN}
```
public static final String DOCUMENT_OPEN
```

Tipe peristiwa dokumen. Membuka sebuah dokumen.

### DOCUMENT_PRINTED {#DOCUMENT_PRINTED}
```
public static final String DOCUMENT_PRINTED
```

Tipe peristiwa dokumen. Menjalankan aksi setelah pencetakan.

### DOCUMENT_SAVED {#DOCUMENT_SAVED}
```
public static final String DOCUMENT_SAVED
```

Tipe peristiwa dokumen. Menjalankan aksi setelah penyimpanan.

### DOCUMENT_WILL_PRINT {#DOCUMENT_WILL_PRINT}
```
public static final String DOCUMENT_WILL_PRINT
```

Tipe peristiwa dokumen. Menjalankan aksi sebelum pencetakan.

### DOCUMENT_WILL_SAVE {#DOCUMENT_WILL_SAVE}
```
public static final String DOCUMENT_WILL_SAVE
```

Tipe peristiwa dokumen. Menjalankan aksi sebelum penyimpanan.

### PdfContentEditor {#PdfContentEditor--}
```
public PdfContentEditor()
```

Konstruktor dari objek PdfContentEditor.

### PdfContentEditor {#PdfContentEditor-com.aspose.pdf.IDocument-}
Konstruktor dari objek PdfContentEditor.

### addDocumentAdditionalAction {#addDocumentAdditionalAction-java.lang.String-java.lang.String-}
<p> Menambahkan aksi tambahan untuk peristiwa dokumen. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.io.InputStream-java.lang.String-java.lang.String-}
<p> Menambahkan lampiran dokumen tanpa anotasi. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); InputStream attStream = new FileInputStream("attachment_file.pdf") editor.addDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### addDocumentAttachment {#addDocumentAttachment-java.lang.String-java.lang.String-}
<p> Menambahkan lampiran dokumen tanpa anotasi. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.addDocumentAttachment("attachment_file.pdf", "description of attachment_file"); editor.save("example_out.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-}
Mengikat aliran PDF untuk penyuntingan.

### bindPdf {#bindPdf-java.lang.String-}
Mengikat file PDF untuk penyuntingan.

### changeViewerPreference {#changeViewerPreference-int-}
```
public void changeViewerPreference(int viewerAttribution)
```

<p> Mengubah preferensi tampilan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.changeViewerPreference(ViewerPreference.HideMenubar); editor.changeViewerPreference(ViewerPreference.PageModeUseNone); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| viewerAttribution |  | Atribusi tampilan yang didefinisikan dalam kelas ViewerPreference. |

### close {#close--}
```
public void close()
```

Menutup dokumen yang dibuka.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-}
Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF.

### createApplicationLink {#createApplicationLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Membuat tautan untuk menjalankan aplikasi dalam dokumen PDF.

### createBookmarksAction {#createBookmarksAction-java.lang.String-java.awt.Color-boolean-boolean-java.lang.String-java.lang.String-java.lang.String-}
Membuat penanda dengan aksi yang ditentukan.

### createCaret {#createCaret-int-java.awt.Rectangle-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Membuat anotasi caret.

### createCustomActionLink {#createCustomActionLink-java.awt.Rectangle-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Membuat tautan ke aksi khusus dalam dokumen PDF.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.io.InputStream-java.lang.String-int-java.lang.String-}
Membuat anotasi lampiran file.

### createFileAttachment {#createFileAttachment-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}
Membuat anotasi lampiran file.

### createFreeText {#createFreeText-java.awt.Rectangle-java.lang.String-int-}
Membuat anotasi teks bebas dalam dokumen PDF

### createJavaScriptLink {#createJavaScriptLink-java.lang.String-java.awt.Rectangle-int-java.awt.Color-}
Membuat tautan ke JavaScript dalam dokumen PDF.

### createLine {#createLine-java.awt.Rectangle-java.lang.String-float-float-float-float-int-int-java.awt.Color-java.lang.String-int:A-java.lang.String:A-}
Membuat anotasi garis.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-}
Membuat tautan lokal dalam dokumen PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-}
Membuat tautan lokal dalam dokumen PDF.

### createLocalLink {#createLocalLink-java.awt.Rectangle-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Membuat tautan lokal dalam dokumen PDF.

### createMarkup {#createMarkup-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Membuat anotasi markup di dokumen PDF.

### createMovie {#createMovie-java.awt.Rectangle-java.lang.String-int-}


### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-}
Membuat tautan ke halaman dokumen PDF lain.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-}
Membuat tautan ke halaman dokumen PDF lain.

### createPdfDocumentLink {#createPdfDocumentLink-java.awt.Rectangle-java.lang.String-int-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Membuat tautan ke halaman dokumen PDF lain.

### createPolygon {#createPolygon-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Membuat anotasi poligon.

### createPolyLine {#createPolyLine-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Membuat anotasi polyline.

### createPopup {#createPopup-java.awt.Rectangle-java.lang.String-boolean-int-}
Membuat anotasi popup dalam dokumen PDF.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.io.InputStream-}
Membuat anotasi stempel karet.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.awt.Color-java.lang.String-}
Membuat anotasi stempel karet.

### createRubberStamp {#createRubberStamp-int-java.awt.Rectangle-java.lang.String-java.lang.String-java.awt.Color-}
Membuat anotasi stempel karet.

### createSound {#createSound-java.awt.Rectangle-java.lang.String-java.lang.String-int-java.lang.String-}


### createSquareCircle {#createSquareCircle-java.awt.Rectangle-java.lang.String-java.awt.Color-boolean-int-int-}
Membuat anotasi kotak-lingkaran.

### createText {#createText-java.awt.Rectangle-java.lang.String-java.lang.String-boolean-java.lang.String-int-}
Membuat anotasi teks dalam dokumen PDF

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-}
Membuat tautan web dalam dokumen PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-}
Membuat tautan web dalam dokumen PDF.

### createWebLink {#createWebLink-java.awt.Rectangle-java.lang.String-int-java.awt.Color-com.aspose.pdf.PredefinedAction:A-}
Membuat tautan web dalam dokumen PDF.

### deleteAttachments {#deleteAttachments--}
```
public void deleteAttachments()
```

<p> Menghapus semua lampiran dalam dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteAttachments(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage--}
```
public void deleteImage()
```

<p> Menghapus semua gambar dari dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(); editor.save("example_out.pdf"); </pre>

### deleteImage {#deleteImage-int-int:A-}
```
public void deleteImage(int pageNumber, int[] index)
```

<p> Menghapus gambar yang ditentukan pada halaman yang ditentukan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.deleteImage(1, new int[] {1, 2}); editor.save("example_out.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman di mana gambar harus dihapus. |
| indeks |  | Array yang mewakili indeks gambar. |

### deleteStamp {#deleteStamp-int-int:A-}
```
public void deleteStamp(int pageNumber, int[] index)
```

<p> Menghapus beberapa stempel pada halaman yang ditentukan berdasarkan indeks stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStamp(1, new int[] { 2, 3, 5} ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tempat stempel akan dihapus. |
| indeks |  | Indeks stempel. |

### deleteStampById {#deleteStampById-int-}
```
public void deleteStampById(int stampId)
```

<p> Menghapus stempel berdasarkan ID dari semua halaman dokumen. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stampId |  | Pengidentifikasi stempel yang harus dihapus. |

### deleteStampById {#deleteStampById-int-int-}
```
public void deleteStampById(int pageNumber, int stampId)
```

<p> Menghapus stempel pada halaman yang ditentukan berdasarkan ID stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampById(1, 100); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tempat stempel akan dihapus. |
| stampId |  | Pengidentifikasi stempel yang harus dihapus. |

### deleteStampByIds {#deleteStampByIds-int:A-}
```
public void deleteStampByIds(int[] stampIds)
```

<p> Menghapus stempel dengan ID yang ditentukan dari semua halaman dokumen. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(new int[] { 102, 103 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stampIds |  | Array ID stempel. |

### deleteStampByIds {#deleteStampByIds-int-int:A-}
```
public void deleteStampByIds(int pageNumber, int[] stampIds)
```

<p> Menghapus stempel pada halaman yang ditentukan berdasarkan beberapa ID stempel. </p> <hr> <pre> PdfContentEditor contentEditor = new PdfContentEditor(); contentEditor.bindPdf("file.pdf"); contentEditor.deleteStampByIds(1, new int[] { 100, 101 } ); contentEditor.save("outfile.pdf"); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tempat stempel akan dihapus. |
| stampIds |  | Array ID stempel. |

### drawCurve {#drawCurve-com.aspose.pdf.facades.LineInfo-int-java.awt.Rectangle-java.lang.String-}
Membuat anotasi kurva.

### extractLink {#extractLink--}
```
public List < Annotation > extractLink()
```

<p> Mengekstrak koleksi instance Link yang terdapat dalam dokumen PDF. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); List links = editor.extractLink(); for (object obj : links) { Link link = (Link)obj; // work with Link instance } </pre>

**Returns:**
Koleksi objek Link

### getReplaceTextStrategy {#getReplaceTextStrategy--}
```
public ReplaceTextStrategy getReplaceTextStrategy()
```

Dapatkan sekumpulan parameter untuk operasi penggantian teks

**Returns:**
Elemen ReplaceTextStrategy

### getStamps {#getStamps-int-}
```
public StampInfo [] getStamps(int pageNumber)
```

Mengembalikan array stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tempat stempel akan dicari. |

**Returns:**
Array stempel.

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

Mendapatkan opsi penyuntingan teks.

**Returns:**
Elemen TextEditOptions

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

Mendapatkan opsi penggantian teks.

**Returns:**
Elemen TextReplaceOptions

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Mendapatkan opsi pencarian teks.

**Returns:**
Elemen TextSearchOptions

### getViewerPreference {#getViewerPreference--}
```
public int getViewerPreference()
```

<p> Mengembalikan preferensi tampilan. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); int prefValue = editor.GetViewerPreference(); if ((prefValue & ViewerPreference.PageModeUseOutline) != 0) { // ... } </pre>

**Returns:**
Mengembalikan sekumpulan flag ViewerPrefernece

### hideStampById {#hideStampById-int-int-}
```
public void hideStampById(int pageNumber, int stampId)
```

Menyembunyikan stempel. Setelah disembunyikan, visibilitas stempel dapat dipulihkan dengan metode ShowStampById.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman. |
| stampId |  | Pengidentifikasi stempel yang harus disembunyikan. |

### moveStamp {#moveStamp-int-int-double-double-}
```
public void moveStamp(int pageNumber, int stampIndex, double x, double y)
```

Mengubah posisi stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman. |
| stampIndex |  | Indeks stempel pada halaman. |
| x |  | Posisi horizontal stempel baru. |
| y |  | Posisi vertikal stempel baru. |

### moveStampById {#moveStampById-int-int-double-double-}
```
public void moveStampById(int pageNumber, int stampId, double x, double y)
```

Mengubah posisi stempel pada halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman. |
| stampId |  | Pengidentifikasi stempel yang harus dipindahkan. |
| x |  | Posisi horizontal stempel baru pada halaman. |
| y |  | Posisi vertikal stempel baru pada halaman. |

### removeDocumentOpenAction {#removeDocumentOpenAction--}
```
public void removeDocumentOpenAction()
```

<p> Menghapus aksi buka dari dokumen. Operasi ini berguna saat menggabungkan beberapa dokumen yang menggunakan aksi 'GoTo' eksplisit saat memulai. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.removeDocumentOpenAction(); editor.save("example_out.pdf"); </pre>

### replaceImage {#replaceImage-int-int-java.lang.String-}
<p> Mengganti gambar yang ditentukan pada halaman yang ditentukan dari dokumen PDF dengan gambar lain. </p> <hr> <pre> PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf("example.pdf"); editor.replaceImage(1, 1, "image.jpg"); editor.save("example_out.pdf"); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-}
<p> Mengganti teks dalam file PDF pada halaman yang ditentukan. </p> <hr> <pre> The example demonstrates how to replace text in PDF document on the specified page. // open document Document doc = new Document(inFile); // create PdfContentEditor object to edit text PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // change text editor.replaceText("hello world", 1, "hi world"); // save document doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-int-java.lang.String-com.aspose.pdf.TextState-}
<p> Mengganti teks dalam file PDF pada halaman yang ditentukan. {@code TextState} objek (font family, color) dapat ditentukan untuk teks yang diganti. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks pada halaman pertama dokumen PDF dan mengatur properti teks {@code TextState} untuk teks baru. // buka dokumen Document doc = new Document(inFile); com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // buat objek textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontSize ( 17); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); textState.setForegroundColor ( com.aspose.pdf.Color.getRed()); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", 1, "hi world", textState); // simpan dokumen doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-}
<p> Mengganti teks dalam file PDF. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks dalam dokumen PDF. Secara default, ia mengganti teks pertama yang ditemukan. // buka dokumen Document doc = new Document(inFile); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ubah teks editor.replaceText("hello world", "hi world"); // simpan dokumen doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-int-}
<p> Mengganti teks dalam file PDF dan mengatur ukuran font. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks dan mengatur ukuran font untuk teks baru. // buka dokumen Document doc = new Document(inFile); // Buat font dan tandai untuk disematkan com.aspose.pdf.Font font = FontRepository.FindFont("Courier New"); font.isEmbedded ( true); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", "hi world", 14); // simpan dokumen doc.save(outFile); </pre>

### replaceText {#replaceText-java.lang.String-java.lang.String-com.aspose.pdf.TextState-}
<p> Mengganti teks dalam file PDF menggunakan objek {@code TextState} yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara mengganti teks dan mengatur properti teks {@code TextState} untuk teks baru. Document doc = new Document(inFile); // Buat font dan tandai untuk disematkan com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Courier New"); font.isEmbedded ( true); // buat objek PdfContentEditor untuk mengedit teks PdfContentEditor editor = new PdfContentEditor(); editor.bindPdf(doc); // buat objek textState com.aspose.pdf.TextState textState = new com.aspose.pdf.TextState(); textState.setFont ( font); textState.setFontStyle ( com.aspose.pdf.FontStyles.Bold | com.aspose.pdf.FontStyles.Italic); // ubah teks dengan font yang ditentukan editor.replaceText("hello world", "hi world", textState); // simpan dokumen doc.save(outFile); </pre>

### setReplaceTextStrategy {#setReplaceTextStrategy-com.aspose.pdf.facades.ReplaceTextStrategy-}
Atur sekumpulan parameter untuk operasi mengganti teks

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
Mengatur opsi penyuntingan teks.

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
Mengatur opsi penggantian teks.

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Mengatur opsi pencarian teks.

### showStampById {#showStampById-int-int-}
```
public void showStampById(int pageNumber, int stampId)
```

Menampilkan stempel yang disembunyikan oleh HiddenStampById.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman. |
| stampId |  | Pengidentifikasi stempel yang harus ditampilkan. |
