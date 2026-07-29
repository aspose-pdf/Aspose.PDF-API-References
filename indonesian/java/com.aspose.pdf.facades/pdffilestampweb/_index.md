---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF. Mengaktifkan untuk bekerja dengan HttpServletResponse."
type: docs
weight: 550
url: /id/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF. Mengaktifkan untuk bekerja dengan HttpServletResponse.

## Fields

| Field | Deskripsi |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Posisi kiri bawah. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Posisi tengah bawah. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Posisi kanan bawah. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Posisi kiri. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Posisi kanan. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Posisi kiri atas. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Posisi tengah atas. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Posisi kanan atas. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Menambahkan footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Menambahkan footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Menambahkan gambar sebagai footer halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Menambahkan gambar sebagai footer halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Menambahkan gambar sebagai footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Menambahkan gambar sebagai footer halaman. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Menambahkan header ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Menambahkan header ke halaman file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Menambahkan gambar sebagai header pada halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Menambahkan gambar di bagian atas halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Menambahkan gambar sebagai header ke halaman file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Menambahkan gambar sebagai header pada halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Menambahkan nomor halaman ke halaman. Nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman dan diposisikan secara horizontal di tengah. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Menambahkan nomor halaman pada posisi yang ditentukan di halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Menambahkan nomor halaman ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Menambahkan nomor halaman ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman dan diposisikan secara horizontal di tengah. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Menambahkan nomor halaman pada posisi yang ditentukan di halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Menambahkan nomor halaman ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Menambahkan nomor halaman ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Menambahkan stempel ke file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Menutup file yang dibuka dan menyimpan perubahan. Peringatan. Jika aliran input atau output ditentukan, mereka tidak ditutup oleh metode Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Usang. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [getInputFile](#getInputFile--) | Mendapatkan nama dan jalur file input. |
| [getInputStream](#getInputStream--) | Mendapatkan aliran masukan. |
| [getKeepSecurity](#getKeepSecurity--) | Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya). |
| [getNumberingStyle](#getNumberingStyle--) | Mendapatkan atau mengatur gaya penomoran halaman. |
| [getOptimizeSize](#getOptimizeSize--) | Mendapatkan atau mengatur flag optimisasi. |
| [getOutputFile](#getOutputFile--) | Mendapatkan nama dan jalur file keluaran. |
| [getOutputStream](#getOutputStream--) | Mendapatkan aliran keluaran. |
| [getPageHeight](#getPageHeight--) | <p> Mendapatkan tinggi halaman pertama dalam file sumber. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | Mendapatkan rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0. |
| [getPageWidth](#getPageWidth--) | <p> Mendapatkan lebar halaman pertama dalam file input. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | Mendapatkan objek Response dimana hasil operasi akan disimpan. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [getStampId](#getStampId--) | ID stempel dari stempel berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman). |
| [getStartingNumber](#getStartingNumber--) | Mendapatkan atau mengatur nomor mulai untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi. |
| [setInputFile](#setInputFile-java.lang.String-) | Mengatur nama dan jalur file masukan. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Mengatur aliran masukan. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Mendapatkan atau mengatur gaya penomoran halaman. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Mendapatkan atau mengatur flag optimisasi. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Mengatur nama dan jalur file keluaran. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Mengatur atau mengatur aliran keluaran. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Mengatur rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Mengatur objek Response dimana hasil operasi akan disimpan. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Mengatur opsi penyimpanan saat hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions. |
| [setStampId](#setStampId-int-) | ID stempel dari stempel berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Mengatur nomor awal untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Posisi kiri bawah.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Posisi tengah bawah.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Posisi kanan bawah.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Posisi kiri.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Posisi kanan.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Posisi kiri atas.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Posisi tengah atas.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Posisi kanan atas.

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> Konstruktor PdfFileStamp. File input dan file output dapat ditentukan melalui properti yang sesuai. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Menambahkan footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Menambahkan footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addFooter(new FormattedText("Foot of the page"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Menambahkan gambar sebagai footer halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Menambahkan gambar sebagai footer halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Menambahkan gambar sebagai footer ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Menambahkan gambar sebagai footer halaman.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Menambahkan header ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addHeader(new FormattedText("Head of the page"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Menambahkan header ke halaman file. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); stamp.addHeader(new FormattedText("Head of the page"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Menambahkan gambar sebagai header pada halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Menambahkan gambar di bagian atas halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Menambahkan gambar sebagai header ke halaman file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Menambahkan gambar sebagai header pada halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Menambahkan nomor halaman ke halaman. Nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman dan diposisikan secara horizontal di tengah. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Menambahkan nomor halaman pada posisi yang ditentukan di halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Menambahkan nomor halaman ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Menambahkan nomor halaman ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Menambahkan nomor halaman ke file. Teks nomor halaman dapat berisi tanda # yang akan diganti dengan nomor halaman. Nomor halaman ditempatkan di bagian bawah halaman dan diposisikan secara horizontal di tengah. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Menambahkan nomor halaman pada posisi yang ditentukan di halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Menambahkan nomor halaman ke halaman. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Menambahkan nomor halaman ke halaman dokumen. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Menambahkan stempel ke file. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Menutup file yang dibuka dan menyimpan perubahan. Peringatan. Jika aliran input atau output ditentukan, mereka tidak ditutup oleh metode Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Usang.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

**Returns:**
objek string

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

**Returns:**
Elemen ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Mendapatkan nama dan jalur file input.

**Returns:**
Objek String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Mendapatkan aliran masukan.

**Returns:**
Objek InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya).

**Returns:**
nilai boolean

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Mendapatkan atau mengatur gaya penomoran halaman.

**Returns:**
Elemen NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Mendapatkan atau mengatur flag optimisasi.

**Returns:**
nilai boolean

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

Mendapatkan nama dan jalur file keluaran.

**Returns:**
Objek String

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

Mendapatkan aliran keluaran.

**Returns:**
objek OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Mendapatkan tinggi halaman pertama dalam file sumber. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Height = \" + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
nilai float

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Mendapatkan rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0.

**Returns:**
nilai float

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Mendapatkan lebar halaman pertama dalam file input. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); System.out.println(\"Width = \" + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
nilai float

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Mendapatkan objek Response dimana hasil operasi akan disimpan.

**Returns:**
Objek HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan opsi penyimpanan ketika hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

**Returns:**
Objek SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

ID stempel dari stempel berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman).

**Returns:**
nilai int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Mendapatkan atau mengatur nomor mulai untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini.

**Returns:**
nilai int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Mengatur nama lampiran ketika hasil operasi disimpan ke objek HttpResponse sebagai lampiran.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Mengatur cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpResponse. Nilai yang mungkin: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi.

### setInputFile {#setInputFile-java.lang.String-}
Mengatur nama dan jalur file masukan.

### setInputStream {#setInputStream-java.io.InputStream-}
Mengatur aliran masukan.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Menjaga keamanan jika true. (Fitur ini akan diimplementasikan pada versi berikutnya).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Mendapatkan atau mengatur gaya penomoran halaman.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Mendapatkan atau mengatur flag optimisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOutputFile {#setOutputFile-java.lang.String-}
Mengatur nama dan jalur file keluaran.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Mengatur atau mengatur aliran keluaran.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Mengatur rotasi nomor halaman. Rotasi dalam derajat. Default adalah 0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Mengatur objek Response dimana hasil operasi akan disimpan.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Mengatur opsi penyimpanan saat hasil disimpan sebagai HttpResponse. Nilai default: PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

ID stempel dari stempel berikutnya yang ditambahkan (termasuk header/footer halaman/nomor halaman).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Mengatur nomor awal untuk halaman pertama dalam file input. Halaman berikutnya akan diberi nomor mulai dari nilai ini. Misalnya jika StartingNumber diatur ke 100, halaman dokumen akan memiliki nomor 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
