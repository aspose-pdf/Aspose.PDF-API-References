---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Paket com.aspose.pdf.facades menyediakan kelas yang awalnya berasal dari Aspose.Pdf.Kit."
type: docs
weight: 180
url: /id/java/com.aspose.pdf.facades/
---
Paket com.aspose.pdf.facades menyediakan kelas yang awalnya berasal dari Aspose.Pdf.Kit.

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IFacade](./ifacade/) | Antarmuka fasad umum yang mendefinisikan metode fasad umum. |
| [IForm](./iform/) | Kelas yang mewakili objek formulir Acro. |
| [IFormEditor](./iformeditor/) | Kelas untuk mengedit formulir (menambah/menghapus bidang, dll). |
| [IPdfFileEditor](./ipdffileeditor/) | Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll. |
| [IPdfFileStamp](./ipdffilestamp/) | Antarmuka untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF. |
| [ISaveableFacade](./isaveablefacade/) | Antarmuka fasad yang mendefinisikan metode umum untuk semua fasad yang dapat disimpan. |
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AlignmentType](./alignmenttype/) | Kelas berisi kemungkinan tipe perataan. Gunakan HorizontalAlignment sebagai gantinya. |
| [AutoRotateMode](./autorotatemode/) | Arah rotasi saat dokumen dicetak. |
| [BDCProperties](./bdcproperties/) | Properti operator BDC. |
| [Bookmark](./bookmark/) | Mewakili penanda buku. |
| [Bookmarks](./bookmarks/) | Mewakili kumpulan objek {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | Mewakili kelas untuk menghasilkan PDF dari format Computer Graphics Metafile (CGM). |
| [DataType](./datatype/) | Menumerasikan definisi tipe bidang. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Enumerasi properti XMP standar. |
| [DocumentPrivilege](./documentprivilege/) | Mewakili hak istimewa untuk mengakses file Pdf. Lihat {@code PdfFileSecurity}. Ada 4 cara menggunakan kelas ini: 1. Menggunakan hak istimewa yang telah ditentukan secara langsung. 2. Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. 3. Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin Adobe Professional tertentu. 4. Menggabungkan cara 2 dan cara 3. //Way1: Menggunakan hak istimewa yang telah ditentukan secara langsung. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin Adobe Professional tertentu. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Menggabungkan cara 2 dan cara 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Menumerasikan jenis pengkodean teks yang digunakan. |
| [Facade](./facade/) | Kelas fasad dasar. |
| [FontColor](./fontcolor/) | Kelas yang mewakili warna teks. |
| [Form](./form/) | Kelas yang mewakili objek formulir Acro. |
| [Form.ImportStatus](./form.importstatus/) | Status bidang yang diimpor |
| [FormattedText](./formattedtext/) | Kelas yang mewakili teks terformat. Berisi informasi tentang teks serta warna, ukuran, dan gaya teksnya. |
| [FormEditor](./formeditor/) | Kelas untuk mengedit formulir (menambah/menghapus bidang, dll). |
| [FormEditorWeb](./formeditorweb/) | Kelas untuk mengedit formulir (menambah/menghapus bidang, dll) |
| [FormFieldFacade](./formfieldfacade/) | Kelas untuk mewakili properti bidang. |
| [FormWeb](./formweb/) | Mewakili Antarmuka formulir Acro. |
| [InternalHelper](./internalhelper/) | Kelas bantuan |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Kelas untuk menentukan parameter pengubahan ukuran halaman. Memungkinkan pengaturan parameter berikut: Ukuran halaman hasil (lebar, tinggi) dalam satuan ruang default atau dalam persentase ukuran halaman awal; Margin Kiri, Atas, Bawah, dan Kanan dalam satuan ruang default atau dalam persentase ukuran halaman awal; Beberapa nilai dapat dibiarkan null untuk perhitungan otomatis. Nilai-nilai ini akan dihitung dari sisa ukuran halaman setelah perhitungan nilai yang ditentukan secara eksplisit. Misalnya: jika lebar halaman = 100 dan lebar halaman baru ditentukan 60 satuan maka margin kiri dan kanan dihitung otomatis: (100 - 60) / 2 = 15. Kelas ini digunakan dalam metode ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Nilai margin atau ukuran konten yang ditentukan dalam persentase satuan ruang default. Kelas ini digunakan dalam ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Mewakili informasi baris. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Mewakili kelas untuk bekerja dengan anotasi dokumen PDF (komentar). |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Mewakili kelas untuk bekerja dengan bookmark file PDF termasuk membuat, memodifikasi, mengekspor, mengimpor, dan menghapus. |
| [PdfContentEditor](./pdfcontenteditor/) | Mewakili kelas untuk mengedit konten file PDF. |
| [PdfConverter](./pdfconverter/) | Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, kini mendukung BMP, JPEG, PNG, dan TIFF. Konten yang didukung dalam pdf: gambar, formulir, komentar. |
| [PdfExtractor](./pdfextractor/) | Kelas untuk mengekstrak gambar dan teks dari dokumen PDF. |
| [PdfFileEditor](./pdffileeditor/) | Mengimplementasikan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Aksi yang dilakukan ketika file rusak ditemui dalam proses penggabungan. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Mewakili kelas dengan metode abstrak yang biasanya disediakan oleh pihak pemanggil dan menangani peristiwa kemajuan yang berasal dari penggabungan. Biasanya penangan pelanggan yang disediakan tersebut dapat digunakan untuk menampilkan total kemajuan penggabungan di konsol atau pada bilah kemajuan. Mewakili informasi tentang peristiwa kemajuan yang terjadi. |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Kelas yang menyediakan informasi tentang file rusak pada saat penggabungan. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Data posisi pemisah halaman. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Kelas ini mewakili informasi tentang kemajuan penggabungan yang dapat digunakan dalam aplikasi eksternal. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Enum ini menjelaskan jenis peristiwa kemajuan yang mungkin terjadi selama penggabungan. |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Mewakili kelas PdfFileEditorWeb yang melakukan operasi dengan file PDF: penggabungan, pemisahan, mengekstrak halaman, membuat buku kecil, dll. |
| [PdfFileInfo](./pdffileinfo/) | Mewakili kelas untuk mengakses meta informasi dokumen PDF. |
| [PdfFileMend](./pdffilemend/) | Mewakili kelas untuk menambahkan teks dan gambar pada halaman dokumen PDF yang ada. |
| [PdfFileSanitization](./pdffilesanitization/) | Mewakili API sanitasi dan pemulihan. Gunakan jika Anda tidak dapat membuat/membuka dokumen dengan cara lain. |
| [PdfFileSecurity](./pdffilesecurity/) | Mewakili enkripsi atau dekripsi file PDF dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi. |
| [PdfFileSignature](./pdffilesignature/) | Mewakili kelas untuk menandatangani file PDF dengan sertifikat. |
| [PdfFileStamp](./pdffilestamp/) | Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | Kelas untuk menambahkan stempel (tanda air atau latar belakang) ke file PDF. Mengaktifkan untuk bekerja dengan HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Kelas untuk menghapus semua kode Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Mewakili kelas untuk mengedit halaman file PDF, termasuk memutar halaman, memperbesar halaman, memindahkan posisi, dan mengubah ukuran halaman. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Mewakili objek yang berisi informasi halaman pencetakan saat ini. |
| [PdfProducer](./pdfproducer/) | <p> Mewakili kelas untuk menghasilkan PDF dari format lain. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Mewakili metode yang menangani peristiwa QueryPageSettings dari PrintDocument. |
| [PdfViewer](./pdfviewer/) | Mewakili kelas untuk melihat atau mencetak PDF. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Kelas untuk manipulasi metadata XMP. |
| [PositioningMode](./positioningmode/) | Mendefinisikan mode penempatan. Nilai yang mungkin termasuk Legacy (kompatibilitas mundur) dan Current (metode perhitungan posisi teks yang diperbarui). |
| [PropertyFlag](./propertyflag/) | Enumerasi flag bidang yang mungkin. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Kelas ini berisi parameter yang menentukan perilaku PdfContentEditor saat operasi ReplaceText dilakukan. |
| [SaveableFacade](./saveablefacade/) | <p> Kelas dasar untuk semua fasad yang dapat disimpan. |
| [SignatureName](./signaturename/) | Mewakili kelas untuk nama tanda tangan. Mewakili nama tanda tangan yang lebih tepat. Digunakan sebagai pengganti nama string. Memungkinkan Anda menampilkan tanda tangan dengan nama string yang sama. |
| [Stamp](./stamp/) | Kelas yang mewakili stempel. |
| [StampInfo](./stampinfo/) | Kelas yang mewakili informasi stempel. |
| [TextProperties](./textproperties/) | Mewakili properti teks seperti: ukuran teks, warna, gaya, dll. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Kelas yang mewakili nilai perataan vertikal yang mungkin. Gunakan VerticalAlignment sebagai gantinya |
| [ViewerPreference](./viewerpreference/) | Menjelaskan preferensi penampil (mode halaman, mode halaman non layar penuh, tata letak halaman). |
| [WordWrapMode](./wordwrapmode/) | Mendefinisikan strategi pembungkus kata |
## Enums

| Enum | Deskripsi |
| --- | --- |
| [Algorithm](./algorithm/) | Mewakili algoritma yang dapat digunakan untuk mengenkripsi dokumen PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | Kelas yang mewakili ruang warna pencampuran. |
| [FieldType](./fieldtype/) | Enumerasi tipe bidang yang mungkin. |
| [FontStyle](./fontstyle/) | Menumerasikan 14 jenis font. |
| [ImageMergeMode](./imagemergemode/) | Mewakili mode untuk menggabungkan gambar. |
| [KeySize](./keysize/) | Mendefinisikan ukuran kunci yang berbeda yang dapat digunakan untuk mengenkripsi dokumen PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Tindakan yang harus dilakukan jika font tidak mengandung karakter yang diperlukan |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Lingkup di mana operasi ganti teks diterapkan REPLACE_FIRST secara default |
| [StampType](./stamptype/) | Menjelaskan tipe stempel. |
| [SubmitFormFlag](./submitformflag/) | Enumerasi flag formulir kirim yang mungkin. |
