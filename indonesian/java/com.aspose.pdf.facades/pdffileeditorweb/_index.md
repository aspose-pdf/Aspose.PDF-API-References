---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas PdfFileEditorWeb yang melakukan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll."
type: docs
weight: 480
url: /id/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Mewakili kelas PdfFileEditorWeb yang melakukan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Konstruktor PdfFileEditorWeb. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Menambahkan jeda halaman ke halaman dokumen. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek respons. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Menambahkan halaman, yang dipilih dari array dokumen di portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage hingga endPage, di portStream pada akhir firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Menambahkan halaman, yang dipilih dari dokumen portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage hingga endPage, di portFile pada akhir firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Menggabungkan dokumen. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Menggabungkan file dan menyimpan hasil ke objek HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Menggabungkan file |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Menggabungkan dua file. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Menggabungkan file dan menyimpan reslt ke objek HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Menggabungkan file menjadi satu file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Menggabungkan dua file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Usang. Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian. |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Jika diatur ke true, aliran ditutup setelah operasi. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Mendapatkan log proses konversi. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Jika true maka struktur logis file disalin saat penggabungan dilakukan. |
| [getCopyOutlines](#getCopyOutlines--) | Jika true maka outline akan disalin. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak. |
| [getCorruptedItems](#getCorruptedItems--) | Array masalah yang ditemui ketika penggabungan dilakukan. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [getKeepActions](#getKeepActions--) | Jika true, tindakan akan disalin dari dokumen sumber. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. |
| [getLastException](#getLastException--) | Mendapatkan pengecualian terakhir yang terjadi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Jika true, outline duplikat digabung. |
| [getOptimizeSize](#getOptimizeSize--) | Mendapatkan atau mengatur flag optimisasi. |
| [getOwnerPassword](#getOwnerPassword--) | Mendapatkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. |
| [getPreserveUserRights](#getPreserveUserRights--) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [getRemoveSignatures](#getRemoveSignatures--) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Menyisipkan dokumen ke dokumen lain dan menyimpan hasil ke objek respons. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Menyisipkan isi file ke file sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Membuat buku kecil dari InputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Membuat buku kecil dari aliran masukan dan menyimpan hasil ke aliran keluaran. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Membuat buku kecil dari firstInputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Membuat buku kecil dari file sumber dan menyimpan hasil ke HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Membuat buku kecil dari file PDF dan menyimpannya ke HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Membuat buku kecil dari file masukan ke file keluaran. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Membuat buku kecil dari inputFile ke outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Membuat dokumen N-Up dari dua aliran PDF masukan ke outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Membuat dokumen N-up dan menyimpan hasil ke HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Membuat dokumen N-up dan menyimpan hasil ke HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Membuat dokumen N-up dan menyimpan hasil ke objek HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Membuat dokumen N-Up dari file masukan ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Membuat dokumen N-Up dari dua file PDF masukan ke outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Mengubah ukuran konten halaman dalam dokumen. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Mengubah ukuran konten halaman dalam dokumen. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran konten halaman dalam dokumen. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Mengubah ukuran halaman dokumen. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Usang. Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Jika diatur ke true, aliran ditutup setelah operasi. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Menentukan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Jika true maka struktur logis file disalin saat penggabungan dilakukan. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Jika true maka outline akan disalin. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representasi pemroses peristiwa kemajuan internal yang bekerja selama penggabungan dan menerjemahkan peristiwa penggabungan pada tahap internal menjadi kode eksternal pelanggan. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [setKeepActions](#setKeepActions-boolean-) | Jika true, tindakan akan disalin dari dokumen sumber. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Jika true, outline duplikat digabung. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Mendapatkan atau mengatur flag optimisasi. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Kadang-kadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang sama yang diletakkan bersebelahan. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik saat formulir digabungkan. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Membagi dokumen dari awal hingga lokasi yang ditentukan dan menyimpan hasil ke objek HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Membagi dokumen dari halaman pertama hingga lokasi dan menyimpan hasil ke objek HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Membagi file Pdf menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |
| [splitToPages](#splitToPages-java.lang.String-) | Memisahkan file PDF menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Konstruktor PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Menambahkan jeda halaman ke halaman dokumen.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek respons.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Menambahkan halaman, yang dipilih dari array dokumen di portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage hingga endPage, di portStream pada akhir firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Menambahkan dokumen ke dokumen sumber dan menyimpan hasil ke objek HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Menambahkan halaman, yang dipilih dari dokumen portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage hingga endPage, di portFile pada akhir firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Menggabungkan dokumen.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Menggabungkan file dan menyimpan hasil ke objek HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Menggabungkan file

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Menggabungkan dua file.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Menggabungkan file dan menyimpan reslt ke objek HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Menggabungkan file menjadi satu file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Menggabungkan dua file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Menghapus halaman yang ditentukan dari dokumen dan menyimpan hasil ke objek HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Mengekstrak halaman yang ditentukan dari file sumber dan menyimpan hasil ke objek HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Usang. Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian.

**Returns:**
Nilai boolean

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

**Returns:**
nilai string

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

Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse.

**Returns:**
Elemen ContentDisposition

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

Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak.

**Returns:**
Elemen ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Array masalah yang ditemui ketika penggabungan dilakukan.

**Returns:**
PdfFileEditor.CorruptedItem array

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

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan.

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

Mendapatkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi.

**Returns:**
Objek String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan.

**Returns:**
nilai boolean

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Returns:**
nilai boolean

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse.

**Returns:**
Objek SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan.

**Returns:**
Objek String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Menyisipkan dokumen ke dokumen lain dan menyimpan hasil ke objek respons.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Menyisipkan isi file ke file sumber dan menyimpan hasil ke objek HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu.

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
Membuat buku kecil dari InputStream ke outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Membuat buku kecil dari aliran masukan dan menyimpan hasil ke aliran keluaran.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Membuat buku kecil dari firstInputStream ke outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Membuat buku kecil dari file sumber dan menyimpan hasil ke HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Membuat buku kecil dari file PDF dan menyimpannya ke HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Membuat buku kecil dari file sumber dan menyimpan hasil ke objek HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Membuat buku kecil dari file masukan ke file keluaran.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Membuat buku kecil dari inputFile ke outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Membuat dokumen N-Up dari dua aliran PDF masukan ke outputStream.

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Membuat dokumen N-up dan menyimpan hasil ke HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Membuat dokumen N-up dan menyimpan hasil ke objek HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Membuat dokumen N-up dan menyimpan hasil ke HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Membuat dokumen N-up dan menyimpan hasil ke objek HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Membuat dokumen N-Up dari firstInputFile ke outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Membuat dokumen N-Up dari file masukan ke outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Membuat dokumen N-Up dari dua file PDF masukan ke outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran konten halaman dokumen.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Mengubah ukuran konten halaman dalam dokumen.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Mengubah ukuran konten halaman dalam dokumen.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran konten halaman dalam dokumen.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Mengubah ukuran halaman dokumen.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Usang. Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai boolean |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Jika diatur ke true, aliran ditutup setelah operasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

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
Menentukan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF.

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

Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ConcatenateCorruptedFileAction |

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

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan.

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
Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi.

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
public void setRemoveSignatures(boolean value)
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse.

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
Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik saat formulir digabungkan.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Jika opsi ini digunakan, maka dokumen tujuan akan disimpan ke disk secara berkala dan penggabungan selanjutnya akan diterapkan padanya sebagai pembaruan inkremental.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Membagi dokumen dari awal hingga lokasi yang ditentukan dan menyimpan hasil ke objek HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Membagi dokumen dari halaman pertama hingga lokasi dan menyimpan hasil ke objek HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang ke objek HttpServletResponse.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru.

### splitToPages {#splitToPages-java.io.InputStream-}
Membagi file Pdf menjadi dokumen satu halaman.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan.

### splitToPages {#splitToPages-java.lang.String-}
Memisahkan file PDF menjadi dokumen satu halaman.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan.
