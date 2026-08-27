---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk mengekstrak gambar dan teks dari dokumen PDF."
type: docs
weight: 400
url: /id/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Kelas untuk mengekstrak gambar dan teks dari dokumen PDF.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Mengikat dokumen Pdf untuk penyuntingan. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Mengikat dokumen Pdf untuk penyuntingan. / * / * / * |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Mengikat dokumen PDF dari aliran. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Mengikat file PDF input. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre> |
| [extractAttachment](#extractAttachment--) | Mengekstrak lampiran dari dokumen Pdf. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Mengekstrak lampiran dari dokumen Pdf. |
| [extractImage](#extractImage--) | <p> Mengekstrak gambar dari file PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Mendapatkan semua kontainer Marked Content sebagai gambar terpisah. </p> <p> Setiap Marked Content akan disimpan sebagai gambar dengan format png yang dinamai dengan {@code MCID_<ID number of block for the page>.png} |
| [extractText](#extractText--) | <p> Mengekstrak teks dari dokumen Pdf. </p> <hr> <pre> Contoh pertama menunjukkan cara mengekstrak semua teks dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Contoh kedua menunjukkan cara mengekstrak teks setiap halaman ke dalam satu file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Mengekstrak teks dari dokumen Pdf. </p> <hr> <pre> Contoh pertama menunjukkan cara mengekstrak semua teks dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Contoh kedua menunjukkan cara mengekstrak teks setiap halaman ke dalam satu file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Hanya untuk penggunaan internal |
| [getAttachment](#getAttachment--) | <p> Menyimpan semua file lampiran ke aliran. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Menyimpan semua file lampiran ke aliran. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Mendapatkan daftar lampiran. |
| [getAttachNames](#getAttachNames--) | <p> Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak nama lampiran dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Mendapatkan halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Mengatur mode untuk proses ekstraksi gambar. </p> <hr> Nilai default adalah ExtractImageMode.DefinedInResources yang mengekstrak semua gambar yang didefinisikan dalam sumber daya. Untuk mengekstrak gambar yang sebenarnya ditampilkan, mode ExtractImageMode.ActuallyUsed harus digunakan. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Mendapatkan mode untuk hasil ekstraksi teks. </p> <hr> <pre> Contoh ini menunjukkan penggunaan properti {@code ExtractTextMode} dalam skenario ekstraksi teks. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> <p> Nilai: 0 adalah mode teks murni dan 1 adalah mode urutan mentah. Default adalah 0. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream dengan format gambar yang diberikan. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Menyimpan teks satu halaman ke stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Menyimpan teks satu halaman ke file. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Mendapatkan kata sandi file input. |
| [getResolution](#getResolution--) | Mendapatkan resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar yang memiliki nilai resolusi lebih tinggi akan lebih jelas. Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300. |
| [getStartPage](#getStartPage--) | Objek Pdf.Engine yang mewakili dokumen PDF. |
| [getText](#getText-java.io.OutputStream-) | Menyimpan teks ke stream. lihat juga:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Menyimpan teks ke stream. lihat juga:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Menyimpan teks ke file. lihat juga:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Mendapatkan opsi pencarian teks. |
| [hasNextImage](#hasNextImage--) | <p> Memeriksa apakah ada lebih banyak gambar yang dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Menunjukkan apakah dapat mengambil lebih banyak teks atau tidak. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Benar ketika teks memiliki simbol Ibrani atau Arab. Kasus ini harus dipertimbangkan secara khusus karena fungsi string mengubah perilakunya dan memulai proses teks dari kanan ke kiri (kecuali angka dan karakter non-teks lainnya). |
| [setEndPage](#setEndPage-int-) | <p> Menetapkan halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Mengatur mode untuk proses ekstraksi gambar. </p> <hr> Nilai default adalah ExtractImageMode.DefinedInResources yang mengekstrak semua gambar yang didefinisikan dalam sumber daya. Untuk mengekstrak gambar yang sebenarnya ditampilkan, mode ExtractImageMode.ActuallyUsed harus digunakan. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Menetapkan mode untuk hasil ekstraksi teks. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Nilai: 0 adalah mode teks murni dan 1 adalah mode urutan mentah. Default adalah 0. |
| [setPassword](#setPassword-java.lang.String-) | Menetapkan kata sandi file input. |
| [setResolution](#setResolution-int-) | Atur resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar yang memiliki nilai resolusi lebih tinggi menjadi lebih jelas. Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300. |
| [setStartPage](#setStartPage-int-) | <p> Mengatur halaman mulai dalam rentang halaman di mana operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Mengatur opsi pencarian teks. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Mengikat dokumen Pdf untuk penyuntingan. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Mengikat dokumen Pdf untuk penyuntingan. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Mengikat dokumen PDF dari aliran. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream(\"sample.pdf\"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Mengikat file PDF input. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf(\"sample.pdf\"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Mengekstrak lampiran dari dokumen Pdf.

### extractAttachment {#extractAttachment-java.lang.String-}
Mengekstrak lampiran dari dokumen Pdf.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Mengekstrak gambar dari file PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"sample.pdf\"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage(\"image-\" + i +\".pdf\"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Mendapatkan semua kontainer Marked Content sebagai gambar terpisah. </p> <p> Setiap Marked Content akan disimpan sebagai gambar dengan format png yang dinamai dengan {@code MCID_<ID number of block for the page>.png}

### extractText {#extractText--}
```
public void extractText()
```

<p> Mengekstrak teks dari dokumen Pdf. </p> <hr> <pre> Contoh pertama menunjukkan cara mengekstrak semua teks dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Contoh kedua menunjukkan cara mengekstrak teks setiap halaman ke dalam satu file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Mengekstrak teks dari dokumen Pdf. </p> <hr> <pre> Contoh pertama menunjukkan cara mengekstrak semua teks dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(\"D:\\\\Text\\\\text.pdf\"); extractor.extractText(); extractor.getText(\"D:\\\\Text\\\\text.txt\"); </pre> <p> Contoh kedua menunjukkan cara mengekstrak teks setiap halaman ke dalam satu file txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + \"Aspose.Pdf.Kit.Pdf\"); extractor.extractText(); String prefix = TestPath + \"Aspose.Pdf.Kit\"; String suffix = \".txt\"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Hanya untuk penggunaan internal

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Menyimpan semua file lampiran ke aliran. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Array aliran dari file lampiran dalam dokumen pdf.

### getAttachment {#getAttachment-java.lang.String-}
<p> Menyimpan semua file lampiran ke aliran. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + \"Attach.pdf\"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Array aliran dari file lampiran dalam dokumen pdf.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Mendapatkan daftar lampiran.

**Returns:**
Mengembalikan sebuah List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Mengembalikan daftar lampiran dalam file PDF. Catatan: ExtractAttachments harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> Contoh menunjukkan cara mengekstrak nama lampiran dari file PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile(\"sample.pdf\")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Daftar lampiran

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Mendapatkan halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
halaman akhir.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Mengatur mode untuk proses ekstraksi gambar. </p> <hr> Nilai default adalah ExtractImageMode.DefinedInResources yang mengekstrak semua gambar yang didefinisikan dalam sumber daya. Untuk mengekstrak gambar yang sebenarnya ditampilkan, mode ExtractImageMode.ActuallyUsed harus digunakan.

**Returns:**
Nilai ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Mendapatkan mode untuk hasil ekstraksi teks. </p> <hr> <pre> Contoh ini menunjukkan penggunaan properti {@code ExtractTextMode} dalam skenario ekstraksi teks. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> <p> Nilai: 0 adalah mode teks murni dan 1 adalah mode urutan mentah. Default adalah 0.

**Returns:**
hasil ekstraksi teks.

### getNextImage {#getNextImage-java.io.OutputStream-}
Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Mengambil gambar berikutnya dari file PDF dan menyimpannya ke dalam stream dengan format gambar yang diberikan.

### getNextImage {#getNextImage-java.lang.String-}
<p> Mengambil gambar berikutnya dari dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Mengambil gambar berikutnya dari dokumen PDF dengan format gambar yang diberikan. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Menyimpan teks satu halaman ke stream. </p> <hr> <pre> The example demonstrates the {@code GetNextPageText} method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Menyimpan teks satu halaman ke file. </p> <hr> <pre> The example demonstrates the GetNextPageText method usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Mendapatkan kata sandi file input.

**Returns:**
nilai String

### getResolution {#getResolution--}
```
public int getResolution()
```

Mendapatkan resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar yang memiliki nilai resolusi lebih tinggi akan lebih jelas. Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300.

**Returns:**
nilai int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Objek Pdf.Engine yang mewakili dokumen PDF.

**Returns:**
halaman mulai dalam rentang halaman.

### getText {#getText-java.io.OutputStream-}
Menyimpan teks ke stream. lihat juga:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Menyimpan teks ke stream. lihat juga:{@code ExtractText}

### getText {#getText-java.lang.String-}
Menyimpan teks ke file. lihat juga:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Mendapatkan opsi pencarian teks.

**Returns:**
opsi pencarian teks.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Memeriksa apakah ada lebih banyak gambar yang dapat diakses dalam dokumen PDF. Catatan: ExtractImage harus dipanggil sebelum menggunakan metode ini. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Benar jika lebih banyak gambar dapat diakses.

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Menunjukkan apakah dapat mengambil lebih banyak teks atau tidak. </p> <hr> <pre> The example demonstrates the {@code HasNextPageText} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Dapat mengambil lebih banyak teks atau tidak, true berarti bisa, atau false.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Benar ketika teks memiliki simbol Ibrani atau Arab. Kasus ini harus dipertimbangkan secara khusus karena fungsi string mengubah perilakunya dan memulai proses teks dari kanan ke kiri (kecuali angka dan karakter non-teks lainnya).

**Returns:**
nilai boolean

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Menetapkan halaman akhir dalam rentang halaman tempat operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | halaman akhir. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Mengatur mode untuk proses ekstraksi gambar. </p> <hr> Nilai default adalah ExtractImageMode.DefinedInResources yang mengekstrak semua gambar yang didefinisikan dalam sumber daya. Untuk mengekstrak gambar yang sebenarnya ditampilkan, mode ExtractImageMode.ActuallyUsed harus digunakan.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Mengatur mode untuk hasil ekstraksi teks. </p> <hr> <pre> Contoh ini menunjukkan penggunaan properti {@code ExtractTextMode} dalam skenario ekstraksi teks. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@\"D:\\\\Text\\\\text.pdf\"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@\"D:\\\\Text\\\\text.txt\"); </pre> Nilai: 0 adalah mode teks murni dan 1 adalah mode urutan mentah. Default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | hasil ekstraksi teks. |

### setPassword {#setPassword-java.lang.String-}
Menetapkan kata sandi file input.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Atur resolusi untuk gambar yang diekstrak. Nilai default adalah 150. Gambar yang memiliki nilai resolusi lebih tinggi menjadi lebih jelas. Namun meningkatkan nilai resolusi akan meningkatkan waktu dan memori yang dibutuhkan untuk mengekstrak gambar. Biasanya untuk mendapatkan gambar yang jelas cukup mengatur resolusi ke 150 atau 300.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Mengatur halaman mulai dalam rentang halaman di mana operasi ekstraksi akan dilakukan. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf(\"sample.pdf\"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | halaman mulai dalam rentang halaman. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Mengatur opsi pencarian teks.
