---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll."
type: docs
weight: 290
url: /id/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Menambahkan halaman, yang dipilih dari array dokumen di portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage hingga endPage, di portStream pada akhir firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Menambahkan halaman, yang dipilih dari dokumen portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage hingga endPage, di portFile pada akhir firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Menggabungkan dokumen. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Menggabungkan file |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Menggabungkan dua file. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Menggabungkan file menjadi satu file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Menggabungkan dua file. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | adalah Allow Concatenate Exceptions |
| [getAttachmentName](#getAttachmentName--) | Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Jika diatur ke true, aliran ditutup setelah operasi. |
| [getContentDisposition](#getContentDisposition--) | Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Mendapatkan log proses konversi. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. |
| [getLastException](#getLastException--) | Mendapatkan pengecualian terakhir yang terjadi. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Jika true, outline duplikat digabung. |
| [getOwnerPassword](#getOwnerPassword--) | Mendapatkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. |
| [getPreserveUserRights](#getPreserveUserRights--) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [getRemoveSignatures](#getRemoveSignatures--) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [getSaveOptions](#getSaveOptions--) | Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Menyisipkan halaman dari file lain ke dalam file Pdf masukan. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Membuat buku kecil dari InputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Membuat buku kecil dari aliran masukan dan menyimpan hasil ke aliran keluaran. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Membuat buku kecil dari firstInputStream ke outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Membuat buku kecil dari file masukan ke file keluaran. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Membuat buku kecil dari inputFile ke outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Membuat dokumen N-Up dari beberapa aliran PDF masukan ke outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Membuat dokumen N-Up dari dua aliran PDF masukan ke outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Membuat dokumen N-Up dari file masukan ke outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Membuat dokumen N-Up dari dua file PDF masukan ke outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Mengubah ukuran konten halaman dokumen. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Jika disetel ke true, pengecualian akan dilempar jika terjadi kesalahan. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Jika diatur ke true, aliran ditutup setelah operasi. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Menentukan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Mengatur format file PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Jika true, pembaruan inkremental dibuat selama penggabungan. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Jika true, outline duplikat digabung. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik saat formulir digabungkan. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Membagi dari lokasi, dan menyimpan bagian belakang sebagai file baru. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Membagi file Pdf menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |
| [splitToPages](#splitToPages-java.lang.String-) | Memisahkan file PDF menjadi dokumen satu halaman. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Pisahkan file Pdf menjadi dokumen satu halaman dan simpan ke jalur yang ditentukan. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Menambahkan halaman, yang dipilih dari array dokumen di portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage hingga endPage, di portStream pada akhir firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Menambahkan halaman, yang dipilih dari dokumen portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage hingga endPage, di portFile pada akhir firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Menggabungkan dokumen.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Menggabungkan file

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Menggabungkan dua file.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Menggabungkan file menjadi satu file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Menggabungkan dua file.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Mengekstrak halaman dari file input,menyimpan sebagai file Pdf baru.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

adalah Allow Concatenate Exceptions

**Returns:**
nilai boolean

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Mendapatkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

**Returns:**
nilai string

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Jika diatur ke true, aliran ditutup setelah operasi.

**Returns:**
nilai boolean

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Mendapatkan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse.

**Returns:**
Elemen ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Mendapatkan log proses konversi.

**Returns:**
nilai string

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak.

**Returns:**
Elemen ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Jika true, pembaruan inkremental dibuat selama penggabungan.

**Returns:**
nilai boolean

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan.

**Returns:**
nilai boolean

### getLastException {#getLastException--}
```
Exception getLastException()
```

Mendapatkan pengecualian terakhir yang terjadi.

**Returns:**
objek java.lang.Exception

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true.

**Returns:**
nilai boolean

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Jika true, outline duplikat digabung.

**Returns:**
nilai boolean

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Mendapatkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi.

**Returns:**
nilai string

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan.

**Returns:**
nilai boolean

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Returns:**
nilai boolean

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Mendapatkan atau mengatur opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse.

**Returns:**
Objek SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Dapatkan format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan.

**Returns:**
nilai string

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Menyisipkan halaman dari file lain ke dalam file Pdf masukan.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Membuat buku kecil dari InputStream ke outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Membuat buku kecil dari aliran masukan dan menyimpan hasil ke aliran keluaran.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Membuat buku kecil dari firstInputStream ke outputStream.

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

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Membuat dokumen N-Up dari aliran masukan dan menyimpan hasil ke aliran keluaran.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Membuat dokumen N-Up dari aliran masukan pertama ke aliran keluaran.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Membuat dokumen N-Up dari beberapa file PDF masukan ke outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Membuat dokumen N-Up dari firstInputFile ke outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Membuat dokumen N-Up dari file masukan ke outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Membuat dokumen N-Up dari dua file PDF masukan ke outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Mengubah ukuran konten halaman dokumen.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Jika disetel ke true, pengecualian akan dilempar jika terjadi kesalahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Menetapkan nama lampiran ketika hasil operasi disimpan ke objek HttpServletResponse sebagai lampiran.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Jika diatur ke true, aliran ditutup setelah operasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Menentukan bagaimana konten akan disimpan ketika hasil operasi disimpan ke objek HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Mengatur format file PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Properti ini mendefinisikan perilaku ketika proses penggabungan menemukan file yang rusak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Jika true, pembaruan inkremental dibuat selama penggabungan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Jika true maka nama bidang akan dibuat unik ketika formulir digabungkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabung menjadi satu lapisan dalam dokumen hasil jika properti ini bernilai true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Jika true, outline duplikat digabung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Menetapkan kata sandi pemilik jika file Pdf sumber yang dimasukkan terenkripsi.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Jika true, hak pengguna dari dokumen pertama diterapkan pada dokumen yang digabungkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Jika true, semua tanda tangan akan dihapus dari bidang (bidang akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Menetapkan opsi penyimpanan ketika hasil disimpan sebagai HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Atur format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik saat formulir digabungkan.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Membagi dari awal hingga lokasi yang ditentukan, dan menyimpan bagian depan ke Stream output.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Membagi file Pdf dari halaman pertama hingga lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Membagi file Pdf menjadi beberapa dokumen. Dokumen dapat berupa satu halaman atau multi-halaman.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Membagi dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai Stream file baru.

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
