---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll."
type: docs
weight: 410
url: /id/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | Konstruktor PdfFileEditor. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Menambahkan halaman, yang dipilih dari array dokumen dalam portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Menambahkan halaman, yang dipilih dari portStream dalam rentang startPage hingga endPage, di portStream pada akhir firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Menambahkan halaman, yang dipilih dari portFile dalam rentang startPage hingga endPage, di portFile pada akhir firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Menggabungkan dokumen. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Menggabungkan file </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Menggabungkan dua file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Menggabungkan file menjadi satu file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Menggabungkan dua file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Menghapus halaman yang ditentukan oleh array nomor dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Menghapus halaman yang ditentukan oleh array nomor dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Mengekstrak halaman dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file PDF baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Mengekstrak halaman dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Jika diatur ke true, pengecualian dilemparkan jika terjadi kesalahan. Jika tidak, pengecualian tidak dilemparkan dan metode mengembalikan false jika gagal. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Jika diatur ke true, aliran ditutup setelah operasi. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [getConversionLog](#getConversionLog--) | Mendapatkan log proses konversi. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Jika true maka struktur logis file disalin saat penggabungan dilakukan. |
| [getCopyOutlines](#getCopyOutlines--) | Jika true maka outline akan disalin. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Properti ini menentukan perilaku ketika proses penggabungan menemukan file yang rusak. Nilai yang mungkin: StopWithError dan ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Array masalah yang ditemui ketika penggabungan dilakukan. Untuk setiap dokumen yang rusak yang diteruskan ke fungsi Concatenate() dibuat entri CorruptedItem baru. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [getKeepActions](#getKeepActions--) | Jika true, tindakan akan disalin dari dokumen sumber. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. Akhiran akan ditambahkan ke nama bidang, templat akhiran dapat ditentukan dalam properti UniqueSuffix. |
| [getLastException](#getLastException--) | Mendapatkan pengecualian terakhir yang terjadi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Jika true, outline duplikat digabung. |
| [getOptimizeSize](#getOptimizeSize--) | Mendapatkan atau mengatur flag optimisasi. |
| [getOwnerPassword](#getOwnerPassword--) | Mendapatkan kata sandi pemilik jika file Pdf masukan sumber dienkripsi. Properti ini belum diimplementasikan. |
| [getPreserveUserRights](#getPreserveUserRights--) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [getRemoveSignatures](#getRemoveSignatures--) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. Nilai default: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. String ini harus berisi substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk bidang "fieldName" nama-namanya akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Membuat buku kecil dari InputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Membuat buku kecil dari input stream dan menyimpan hasil ke output stream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Membuat buku kecil dari firstInputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Membuat buku kecil dari file input ke file output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Membuat booklet dari inputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Membuat booklet yang disesuaikan dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream. Setiap halaman outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman pada aliran masukan dengan nomor halaman yang sama. Halaman‑halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Membuat dokumen N-Up dari dua aliran PDF masukan ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. Setiap halaman outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman pada file masukan dengan nomor halaman yang sama. Halaman‑halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Membuat dokumen N-Up dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Membuat dokumen N-Up dari file masukan ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Membuat dokumen N-Up dari dua file PDF masukan ke outputFile. Setiap halaman outputFile akan berisi dua halaman, satu halaman berasal dari file masukan pertama dan satu lagi dari file masukan kedua. Kedua halaman tersebut ditumpuk secara horizontal. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Mengubah ukuran konten halaman dokumen. Mengecilkan konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //ubah ukuran semua halaman dokumen null, //lebar konten baru = 200 200, //tinggi konten baru = 300 300); // area sisa halaman akan kosong </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran konten halaman dalam dokumen. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //ubah ukuran semua halaman dokumen null, //lebar konten baru = 60% dari ukuran awal 60, //tinggi konten baru = 60% dari ukuran awal 60); // Area sisa halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20% // Sama untuk margin atas dan bawah. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ubah ukuran semua halaman dokumen null, //lebar konten baru = 60% dari ukuran awal 60, //tinggi konten baru = 60% dari ukuran awal 60); // Area sisa halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20% // Sama untuk margin atas dan bawah. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Jika disetel ke true, pengecualian akan dilempar jika terjadi kesalahan. Jika tidak, pengecualian tidak dilempar dan metode mengembalikan false jika gagal. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Jika disetel ke true, aliran akan ditutup setelah operasi. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Menetapkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. Nilai yang mungkin: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Jika true maka struktur logis file disalin saat penggabungan dilakukan. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Jika true maka outline akan disalin. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Properti ini menentukan perilaku ketika proses penggabungan menemukan file yang rusak. Nilai yang mungkin: StopWithError dan ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [setKeepActions](#setKeepActions-boolean-) | Jika true, tindakan akan disalin dari dokumen sumber. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. Akhiran akan ditambahkan ke nama bidang, templat akhiran dapat ditentukan dalam properti UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Jika true, outline duplikat digabung. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Mendapatkan atau mengatur flag optimisasi. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. Properti ini belum diimplementasikan. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. Nilai default: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. String ini harus berisi substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk bidang "fieldName" nama-nya akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Aliran tidak DITUTUP setelah operasi ini. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Aliran tidak DITUTUP setelah operasi ini kecuali CloseConcatedStreams ditentukan. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Membagi file Pdf menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |
| [splitToPages](#splitToPages-java.lang.String-) | Memisahkan file PDF menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

Konstruktor PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Menambahkan halaman, yang dipilih dari array dokumen dalam portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Menambahkan halaman, yang dipilih dari portStream dalam rentang startPage hingga endPage, di portStream pada akhir firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Menambahkan halaman, yang dipilih dari portFile dalam rentang startPage hingga endPage, di portFile pada akhir firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Menggabungkan dokumen.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Menggabungkan file </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Menggabungkan dua file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Menggabungkan file menjadi satu file. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Menggabungkan dua file. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: document1 memiliki 5 halaman: p1, p2, p3, p4, p5. document2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Menghapus halaman yang ditentukan oleh array nomor dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Menghapus halaman yang ditentukan oleh array nomor dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Mengekstrak halaman dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Mengekstrak halaman yang ditentukan oleh array nomor, menyimpannya sebagai file PDF baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Mengekstrak halaman dari file masukan, menyimpannya sebagai file Pdf baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Jika diatur ke true, pengecualian dilemparkan jika terjadi kesalahan. Jika tidak, pengecualian tidak dilemparkan dan metode mengembalikan false jika gagal. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
nilai boolean @deprecated Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

**Returns:**
nilai String

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Jika diatur ke true, aliran ditutup setelah operasi.

**Returns:**
nilai boolean

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true.

**Returns:**
nilai int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Mendapatkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. Nilai yang mungkin: inline / attachment. Default: inline.

**Returns:**
Elemen ContentDisposition @see ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Mendapatkan log proses konversi.

**Returns:**
nilai string

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Jika true maka struktur logis file disalin saat penggabungan dilakukan.

**Returns:**
nilai boolean

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Jika true maka outline akan disalin.

**Returns:**
nilai boolean

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Properti ini menentukan perilaku ketika proses penggabungan menemukan file yang rusak. Nilai yang mungkin: StopWithError dan ConcatenateIgnoringCorrupted.

**Returns:**
Elemen ConcatenateCorruptedFileAction @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Array masalah yang ditemui ketika penggabungan dilakukan. Untuk setiap dokumen yang rusak yang diteruskan ke fungsi Concatenate() dibuat entri CorruptedItem baru. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
array dari PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan.

**Returns:**
instance ConcatenationProgressHandler

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Jika true, pembaruan inkremental dibuat selama penggabungan.

**Returns:**
nilai boolean

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Jika true, tindakan akan disalin dari dokumen sumber.

**Returns:**
nilai boolean

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. Akhiran akan ditambahkan ke nama bidang, templat akhiran dapat ditentukan dalam properti UniqueSuffix.

**Returns:**
nilai boolean

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Mendapatkan pengecualian terakhir yang terjadi.

**Returns:**
objek java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true.

**Returns:**
nilai boolean

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Jika true, outline duplikat digabung.

**Returns:**
nilai boolean

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Mendapatkan atau mengatur flag optimisasi.

**Returns:**
nilai boolean

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Mendapatkan kata sandi pemilik jika file Pdf masukan sumber dienkripsi. Properti ini belum diimplementasikan.

**Returns:**
nilai String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan.

**Returns:**
nilai boolean

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Returns:**
nilai boolean

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. Nilai default: PdfSaveOptions.

**Returns:**
Objek SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. String ini harus berisi substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk bidang "fieldName" nama-namanya akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll.

**Returns:**
nilai String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileoutputStream("out.pdf"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Menyisipkan halaman dari file lain ke dalam file Pdf input. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream("file1.pdf"); outstream insertedStream = new FileInputStream("file2.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf"); </pre>

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan.

**Returns:**
nilai boolean

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental.

**Returns:**
nilai boolean

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
<p> Membuat buku kecil dari InputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Membuat buku kecil dari input stream dan menyimpan hasil ke output stream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Membuat buku kecil dari firstInputStream ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Membuat buku kecil dari file input ke file output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Membuat booklet dari inputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Membuat booklet yang disesuaikan dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream. Setiap halaman outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman pada aliran masukan dengan nomor halaman yang sama. Halaman‑halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Membuat dokumen N-Up dari dua aliran PDF masukan ke outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. Setiap halaman outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman pada file masukan dengan nomor halaman yang sama. Halaman‑halaman tersebut ditumpuk secara horizontal jika isSidewise bernilai true dan ditumpuk secara vertikal jika isSidewise bernilai false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Membuat dokumen N-Up dari firstInputFile ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Membuat dokumen N-Up dari file masukan ke outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Membuat dokumen N-Up dari dua file PDF masukan ke outputFile. Setiap halaman outputFile akan berisi dua halaman, satu halaman berasal dari file masukan pertama dan satu lagi dari file masukan kedua. Kedua halaman tersebut ditumpuk secara horizontal. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Mengubah ukuran konten halaman dokumen. Mengecilkan konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran konten halaman dokumen.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //ubah ukuran semua halaman dokumen null, //lebar konten baru = 200 200, //tinggi konten baru = 300 300); // area sisa halaman akan kosong </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran konten halaman dalam dokumen.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //ubah ukuran semua halaman dokumen null, //lebar konten baru = 60% dari ukuran awal 60, //tinggi konten baru = 60% dari ukuran awal 60); // Area sisa halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20% // Sama untuk margin atas dan bawah. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //ubah ukuran semua halaman dokumen null, //lebar konten baru = 60% dari ukuran awal 60, //tinggi konten baru = 60% dari ukuran awal 60); // Area sisa halaman akan kosong (margin halaman). Ukuran margin kiri dan kanan adalah (100% - 60%) / 2 = 20% // Sama untuk margin atas dan bawah. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Jika disetel ke true, pengecualian akan dilempar jika terjadi kesalahan. Jika tidak, pengecualian tidak dilempar dan metode mengembalikan false jika gagal. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Jika disetel ke true, aliran akan ditutup setelah operasi. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Menetapkan cara konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. Nilai yang mungkin: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Jika true maka struktur logis file disalin saat penggabungan dilakukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Jika true maka outline akan disalin.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Properti ini menentukan perilaku ketika proses penggabungan menemukan file yang rusak. Nilai yang mungkin: StopWithError dan ConcatenateIgnoringCorrupted.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Jika true, pembaruan inkremental dibuat selama penggabungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Jika true, tindakan akan disalin dari dokumen sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. Akhiran akan ditambahkan ke nama bidang, templat akhiran dapat ditentukan dalam properti UniqueSuffix.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Jika true, outline duplikat digabung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Mendapatkan atau mengatur flag optimisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. Properti ini belum diimplementasikan.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures(boolean value)
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. Nilai default: PdfSaveOptions.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | nilai boolean |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
<p> Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. String ini harus berisi substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk bidang "fieldName" nama-nya akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Aliran tidak DITUTUP setelah operasi ini.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Aliran tidak DITUTUP setelah operasi ini kecuali CloseConcatedStreams ditentukan.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Membagi file Pdf menjadi dokumen satu halaman.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan.

### splitToPages {#splitToPages-java.lang.String-}
Memisahkan file PDF menjadi dokumen satu halaman.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan.
