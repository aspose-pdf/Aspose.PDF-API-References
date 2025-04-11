---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfFileEditor. Mengimplementasikan operasi dengan penggabungan file PDF, pemisahan, ekstraksi halaman, pembuatan buku kecil, dll.
type: docs
weight: 4460
url: /id/net/aspose.pdf.facades/pdffileeditor/
---
## Kelas PdfFileEditor

Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, ekstraksi halaman, pembuatan buku kecil, dll.

```csharp
public sealed class PdfFileEditor
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Jika diatur ke true, aliran ditutup setelah operasi. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Jumlah dokumen yang digabungkan sebelum pembaruan inkremental baru dibuat selama penggabungan ketika UseDiskBuffer diatur ke true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Mendapatkan log dari proses konversi. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Mengatur format file PDF. File hasil akan disimpan dalam format file yang ditentukan. Jika properti ini tidak ditentukan maka file akan disimpan dalam format PDF default tanpa konversi. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Jika true maka struktur logis file akan disalin saat penggabungan dilakukan. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Jika true maka garis besar akan disalin. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Properti ini mendefinisikan perilaku ketika proses penggabungan menemui file yang rusak. Nilai yang mungkin adalah: StopWithError dan ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array masalah yang dihadapi saat penggabungan dilakukan. Untuk setiap dokumen yang rusak dari fungsi Concatenate() yang diteruskan, entri CorruptedItem baru dibuat. Properti ini hanya dapat digunakan ketika CorruptedFileAction adalah ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Jika true, pembaruan inkremental dilakukan selama penggabungan. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Jika true tindakan akan disalin dari dokumen sumber. Nilai default: true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Jika true maka nama field akan dibuat unik saat formulir digabungkan. Akhiran akan ditambahkan ke nama field, template akhiran dapat ditentukan dalam properti UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Mendapatkan pengecualian terakhir yang terjadi. Dapat digunakan untuk memeriksa alasan kegagalan. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Konten opsional dari dokumen yang digabungkan dengan nama yang sama akan digabungkan menjadi satu lapisan dalam dokumen hasil jika properti ini true. Jika tidak, lapisan dengan nama yang sama akan disimpan sebagai lapisan yang berbeda dalam dokumen hasil. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Jika true, garis besar duplikat digabungkan. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Mendapatkan atau mengatur flag optimasi. Aliran sumber yang sama dalam file hasil digabungkan menjadi satu objek PDF jika flag ini diatur. Ini memungkinkan untuk mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi yang lebih lambat dan kebutuhan memori yang lebih besar. Nilai default: false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Mengatur kata sandi pemilik jika file Pdf input sumber dienkripsi. Properti ini belum diimplementasikan. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Jika true, hak pengguna dari dokumen pertama diterapkan ke dokumen yang digabungkan. Hak pengguna dari semua dokumen lainnya diabaikan. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Jika true, semua tanda tangan akan dihapus dari field (field akan tetap ada); jika tidak, Anda dapat mendapatkan tanda tangan yang tidak valid. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Format akhiran yang ditambahkan ke nama field untuk membuatnya unik saat formulir digabungkan. String ini harus mengandung substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk field "fieldName" nama akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Jika opsi ini digunakan maka dokumen tujuan akan disimpan di disk secara berkala dan penggabungan lebih lanjut akan diterapkan padanya sebagai pembaruan inkremental. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam satuan ruang default. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Mengubah ukuran konten halaman dan menambahkan margin yang ditentukan. Margin ditentukan dalam persentase dari ukuran halaman awal. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Menambahkan pemisah halaman ke halaman dokumen. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Menambahkan pemisah halaman ke halaman dokumen. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Menambahkan pemisah halaman ke halaman dokumen. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Menambahkan halaman, yang dipilih dari portStream dalam rentang dari startPage ke endPage, di portStream di akhir firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Menambahkan halaman, yang dipilih dari array dokumen di portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Menambahkan halaman, yang dipilih dari portFile dalam rentang dari startPage ke endPage, di portFile di akhir firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Menggabungkan dokumen. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Menggabungkan file |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Menggabungkan file menjadi satu file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Menggabungkan dua file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Menggabungkan dua file. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Menyisipkan halaman dari file lain ke dalam file Pdf pada posisi tertentu. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Membuat buku kecil dari InputStream ke outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Membuat buku kecil dari file input ke file output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Membuat buku kecil dari aliran input dan menyimpan hasilnya ke aliran output. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Membuat buku kecil dari inputFile ke outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Membuat buku kecil dari firstInputStream ke outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Membuat dokumen N-Up dari dua aliran PDF input ke outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Membuat dokumen N-Up dari beberapa aliran PDF input ke outputStream. Setiap halaman dari outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam aliran input dengan nomor halaman yang sama. Halaman multi ditumpuk secara horizontal jika isSidewise true dan ditumpuk secara vertikal jika isSidewise false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi dua halaman, satu halaman dari file input pertama dan satu halaman dari file input kedua. Dua halaman ditumpuk secara horizontal. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Membuat dokumen N-Up dari beberapa file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam file input dengan nomor halaman yang sama. Halaman multi ditumpuk secara horizontal jika isSidewise true dan ditumpuk secara vertikal jika isSidewise false. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Membuat dokumen N-Up dari aliran input dan menyimpan hasilnya ke aliran output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Membuat dokumen N-Up dari aliran input pertama ke aliran output. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Membuat dokumen N-Up dari file input ke outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Mengubah ukuran halaman dokumen. Margin kosong ditambahkan di sekitar halaman yang diperkecil. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Mengubah ukuran konten halaman dokumen. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran konten baru ditentukan dalam persentase. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Memisahkan dari awal ke lokasi yang ditentukan, dan menyimpan bagian depan di aliran output. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Memisahkan file Pdf menjadi beberapa dokumen. Dokumen dapat berupa halaman tunggal atau multi-halaman. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Memisahkan file Pdf menjadi beberapa dokumen. Dokumen dapat berupa halaman tunggal atau multi-halaman. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai aliran file baru. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Memisahkan dari lokasi, dan menyimpan bagian belakang sebagai file baru. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Memisahkan file Pdf menjadi dokumen halaman tunggal. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Memisahkan file PDF menjadi dokumen halaman tunggal. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Memisahkan file Pdf menjadi dokumen halaman tunggal dan menyimpannya ke jalur yang ditentukan. Jalur ditentukan oleh template nama field. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Memisahkan file Pdf menjadi dokumen halaman tunggal dan menyimpannya ke jalur yang ditentukan. Jalur ditentukan oleh template nama field. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Menambahkan halaman, yang dipilih dari array dokumen di portStreams. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portStreams dalam rentang startPage hingga endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Menambahkan halaman, yang dipilih dari dokumen portFiles. Dokumen hasil mencakup firstInputFile dan semua halaman dokumen portFiles dalam rentang startPage hingga endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Menggabungkan dokumen. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Menggabungkan file |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Menggabungkan file menjadi satu file. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Menggabungkan dua file. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Menggabungkan dua dokumen Pdf menjadi dokumen Pdf baru dengan halaman secara bergantian dan mengisi tempat kosong dengan halaman kosong. misalnya: dokumen1 memiliki 5 halaman: p1, p2, p3, p4, p5. dokumen2 memiliki 3 halaman: p1', p2', p3'. Menggabungkan dua dokumen Pdf akan menghasilkan dokumen hasil dengan halaman: p1, p1', p2, p2', p3, p3', p4, halaman kosong, p5, halaman kosong. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Menghapus halaman yang ditentukan oleh array nomor dari file input, menyimpan sebagai file Pdf baru. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file Pdf baru. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Mengekstrak halaman yang ditentukan oleh array nomor, menyimpan sebagai file PDF baru. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Mengekstrak halaman dari file input, menyimpan sebagai file Pdf baru. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Menyisipkan halaman dari file lain ke dalam file Pdf input. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Membuat buku kecil dari InputStream ke outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Membuat buku kecil dari file input ke file output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Membuat buku kecil dari aliran input dan menyimpan hasilnya ke aliran output. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Membuat buku kecil dari inputFile ke outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputStream ke outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Membuat buku kecil dari firstInputStream ke outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Membuat buku kecil yang disesuaikan dari firstInputFile ke outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Membuat dokumen N-Up dari dua aliran PDF input ke outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Membuat dokumen N-Up dari beberapa aliran PDF input ke outputStream. Setiap halaman dari outputStream akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam aliran input dengan nomor halaman yang sama. Halaman multi ditumpuk secara horizontal jika isSidewise true dan ditumpuk secara vertikal jika isSidewise false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Membuat dokumen N-Up dari dua file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi dua halaman, satu halaman dari file input pertama dan satu halaman dari file input kedua. Dua halaman ditumpuk secara horizontal. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Membuat dokumen N-Up dari beberapa file PDF input ke outputFile. Setiap halaman dari outputFile akan berisi beberapa halaman, yang merupakan kombinasi dengan halaman dalam file input dengan nomor halaman yang sama. Halaman multi ditumpuk secara horizontal jika isSidewise true dan ditumpuk secara vertikal jika isSidewise false. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Membuat dokumen N-Up dari aliran input dan menyimpan hasilnya ke aliran output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Membuat dokumen N-Up dari firstInputFile ke outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Membuat dokumen N-Up dari aliran input pertama ke aliran output. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Membuat dokumen N-Up dari file input ke outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Mengubah ukuran konten halaman dokumen. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Mengubah ukuran konten halaman dalam dokumen. Jika halaman diperkecil, margin kosong ditambahkan di sekitar halaman. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Mengubah ukuran konten halaman dokumen. Memperkecil konten halaman dan menambahkan margin. Ukuran baru konten ditentukan dalam satuan ruang default. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Memisahkan dari awal ke lokasi yang ditentukan, dan menyimpan bagian depan di aliran output. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Memisahkan file Pdf dari halaman pertama ke lokasi yang ditentukan, dan menyimpan bagian depan sebagai file baru. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Memisahkan dari lokasi yang ditentukan, dan menyimpan bagian belakang sebagai aliran file baru. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Memisahkan dari lokasi, dan menyimpan bagian belakang sebagai file baru. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Tindakan yang dilakukan ketika file yang rusak ditemukan dalam proses penggabungan. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan untuk mengatur parameter berikut: Ukuran halaman hasil (lebar, tinggi) dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Margin Kiri, Atas, Bawah, dan Kanan dalam satuan ruang default atau dalam persentase dari ukuran halaman awal; Beberapa nilai dapat dibiarkan null untuk perhitungan otomatis. Nilai-nilai ini akan dihitung dari sisa ukuran halaman setelah perhitungan nilai yang ditentukan secara eksplisit. Misalnya: jika lebar halaman = 100 dan lebar halaman baru ditentukan 60 unit maka margin kiri dan kanan dihitung secara otomatis: (100 - 60) / 2 = 15. Kelas ini digunakan dalam metode ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Nilai margin atau ukuran konten yang ditentukan dalam persentase dari satuan ruang default. Kelas ini digunakan dalam ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Kelas yang memberikan informasi tentang file yang rusak pada saat penggabungan. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Data posisi pemisah halaman. |

### Lihat Juga

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)