---
title: "Kelas Document"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.Document. Kelas yang mewakili dokumen PDF"
type: docs
weight: 3900
url: /id/net/aspose.pdf/document/
---
## Document class

Kelas yang mewakili dokumen PDF.

```csharp
public sealed class Document : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Document](document/#constructor)() | Menginisialisasi dokumen kosong. |
| [Document](document/#constructor_1)(PdfVersion) | Menginisialisasi dokumen kosong berdasarkan versi. |
| [Document](document/#constructor_2)(Stream) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_11)(string) | Cukup inisialisasi Document menggunakan *filename*. Sama dengan [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Membuka dokumen yang ada dari aliran dengan menyediakan konversi yang diperlukan untuk mendapatkan dokumen pdf. |
| [Document](document/#constructor_7)(Stream, string) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_15)(string, bool) | Cukup inisialisasi Document menggunakan *filename*. Sama dengan [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_12)(string, LoadOptions) | Membuka dokumen yang ada dari file dengan menyediakan opsi konversi yang diperlukan untuk mendapatkan dokumen pdf. |
| [Document](document/#constructor_16)(string, string) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_9)(Stream, string, bool) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_18)(string, string, bool) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | Menginisialisasi instance Document baru dari aliran *input*. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Mendapatkan aksi dokumen. Properti ini adalah instance dari kelas DocumentActions yang memungkinkan untuk mendapatkan/mengatur aksi BeforClosing, BeforSaving, dll. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Memungkinkan menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen. Jika digunakan, maka halaman yang berbeda namun duplikat dapat merujuk ke objek konten yang sama. Harap perhatikan bahwa mode ini dapat menyebabkan efek samping seperti mengubah konten halaman ketika halaman lain diubah. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Mendapatkan atau mengatur warna latar belakang dokumen. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Mendapatkan koleksi dokumen. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Mendapatkan pengaturan keamanan jika dokumen terenkripsi. Jika dokumen tidak terenkripsi maka pengecualian yang sesuai akan dilempar di .net 1.1 atau CryptoAlgorithm akan bernilai null untuk versi .net lainnya. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | Mendapatkan handler keamanan khusus. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Mendapatkan koleksi tujuan. Usang. Harap gunakan NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Mendapatkan atau mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. Misalnya beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font tersebut. Flag ini digunakan untuk menonaktifkan semua pembatasan lisensi untuk semua font dalam dokumen PDF saat ini. Harap berhati-hati saat menggunakan flag ini. Ketika flag ini diatur, berarti orang yang mengaturnya mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum atas dirinya sendiri. Jadi dia mengambilnya dengan risiko sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda yakin sepenuhnya bahwa Anda tidak melanggar hukum hak cipta. Secara default false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Mendapatkan koleksi file yang disematkan ke dokumen. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded diatur ke true. Semua font PDF dapat disematkan ke dokumen cukup dengan mengatur flag IsEmbedded ke true, tetapi font Type1 standar PDF merupakan pengecualian dari aturan ini. Penyematan font Type1 standar memerlukan waktu yang cukup lama, sehingga untuk menyematkan font tersebut tidak hanya perlu mengatur flag IsEmbedded ke true untuk font yang bersangkutan, tetapi juga harus mengatur flag tambahan pada tingkat dokumen — EmbedStandardFonts = true; Properti ini hanya dapat diatur satu kali untuk semua font. Secara default false. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah logging notifikasi diaktifkan. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori. Ini memungkinkan mengurangi penggunaan memori tetapi dapat berdampak negatif pada kinerja. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. Diaktifkan secara default. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nama file PDF yang menyebabkan dokumen ini |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instansi IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Mendapatkan Acro Form dari dokumen. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Melempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah menu bar harus disembunyikan saat dokumen aktif. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah toolbar harus disembunyikan saat dokumen aktif. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif. |
| [Id](../../aspose.pdf/document/id/) { get; } | Mendapatkan ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. Ketika halaman dari dokumen sumber disalin ke dokumen tujuan, proses penyalinan dihentikan dengan exception jika beberapa objek dalam file sumber rusak ketika flag ini false. contoh: dest.Pages.Add(src.Pages); Jika flag ini diatur ke true, maka objek yang rusak akan diganti dengan nilai kosong. Secara default: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Mendapatkan info dokumen. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Mendapatkan status enkripsi dokumen. True jika dokumen terenkripsi. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Mendapatkan apakah dokumen pdfa mematuhi standar. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Mendapatkan apakah dokumen pdfua mematuhi standar. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Mendapatkan atau mengatur apakah dokumen pdfa sesuai. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Koleksi JavaScript tingkat dokumen. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Mendapatkan struktur logis dokumen. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadata dokumen. (Sebuah dokumen PDF dapat mencakup informasi umum, seperti judul dokumen, penulis, serta tanggal pembuatan dan modifikasi. Informasi global tentang dokumen (berlawanan dengan isi atau strukturnya) disebut metadata dan dimaksudkan untuk membantu dalam pengkatalogan dan pencarian dokumen di basis data eksternal.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Koleksi Named Destination dalam dokumen. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Mendapatkan atau mengatur mode halaman, yang menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Mendapatkan atau mengatur aksi yang dilakukan saat membuka dokumen. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Mendapatkan atau mengatur bendera optimasi. Ketika halaman ditambahkan ke dokumen, aliran sumber daya yang sama dalam file hasil digabung menjadi satu objek PDF jika bendera ini diatur. Hal ini memungkinkan mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi lebih lambat dan kebutuhan memori yang lebih besar. Nilai default: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Mendapatkan outline dokumen. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Mendapatkan koleksi Output intents dalam dokumen. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Mendapatkan atau mengatur info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Mendapatkan label halaman dalam dokumen. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Mendapatkan atau mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Mendapatkan atau mengatur mode halaman, yang menentukan cara dokumen ditampilkan saat dibuka. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Mendapatkan atau mengatur koleksi halaman dokumen. Perhatikan bahwa halaman diberi nomor mulai dari 1 dalam koleksi. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Mendapatkan format PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Mendapatkan izin dokumen. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Mendapatkan atau mengatur bendera yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Mendapatkan atau mengatur opsi skala halaman yang akan dipilih ketika dialog cetak ditampilkan untuk dokumen ini. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Mendapatkan akses ke konten TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Mendapatkan versi Pdf dari header file Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Mendapatkan dan mengatur batas ukuran file untuk memuat seluruh file ke memori. Nilainya diatur dalam megabyte. Nilai default adalah 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Mendapatkan status berlisensi sistem. Mengembalikan true jika sistem beroperasi dalam mode berlisensi dan false jika tidak. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Menggabungkan dokumen. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Menggabungkan file pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Menggabungkan dokumen. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Menggabungkan dokumen. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Mengikat xml ke dokumen |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Mengikat xml ke dokumen |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Mengikat xml/xsl ke dokumen |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Mengikat xml/xsl ke dokumen |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Mengikat xml/xsl ke dokumen |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Mengubah password document. Tindakan ini hanya dapat dilakukan menggunakan password pemilik. |
| [Check](../../aspose.pdf/document/check/)(bool) | Memvalidasi document. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Mengonversi document menggunakan opsi konversi yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Mengenali gambar di dalam document dan menambahkan string hocr di atasnya. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Mengenali gambar di dalam document dan menambahkan string hocr di atasnya. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Mengonversi document dan menyimpan kesalahan ke dalam stream yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Mengonversi document dengan menerapkan Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Mengonversi document dengan menerapkan Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Mengonversi document dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Mengonversi page ke PNG untuk stream gambar DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Mendekripsi document. Panggil kemudian Save untuk memperoleh versi document yang telah didekripsi. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Menutup semua sumber daya yang digunakan oleh document ini. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Mengenkripsi document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Mengenkripsi document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Mengenkripsi document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Mengenkripsi document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Mengenkripsi document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Mengenkripsi document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Mengekspor semua anotasi document ke dalam stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Mengekspor semua anotasi document ke file XFDF. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Menghapus semua bidang dari document dan menempatkan nilai mereka sebagai gantinya. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Menghapus semua bidang (dan anotasi) dari document dan menempatkan nilai mereka sebagai gantinya. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Mengganti konten transparan dengan grafik raster dan vektor yang tidak transparan. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Membersihkan memori |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Mengembalikan nilai item dari kamus katalog. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Mendapatkan objek dengan ID yang ditentukan dalam document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Mendapatkan metadata XMP dari document. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Memeriksa apakah PDF document saat ini telah disimpan dengan pembaruan inkremental. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Mengimpor anotasi dari stream ke document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Mengimpor anotasi dari file XFDF ke document. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Memeriksa apakah document memerlukan pemanggilan metode Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Memuat file, mengonversinya ke PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Menggabungkan dokumen. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Menggabungkan file pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Menggabungkan dokumen. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Menggabungkan dokumen. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linearize dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara inkremental saat data halaman tiba ketika data untuk sebuah halaman dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar-benar menyimpan dokumen. Sebaliknya dokumen hanya dipersiapkan untuk memiliki struktur yang dioptimalkan, panggil Save kemudian untuk mendapatkan dokumen yang dioptimalkan. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimalkan sumber daya dalam dokumen: 1. Sumber daya yang tidak digunakan pada halaman dokumen dihapus; 2. Sumber daya yang sama digabung menjadi satu objek; 3. Objek yang tidak terpakai dihapus. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimisasi yang ditentukan. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang. Hanya jika dokumen memiliki lebih dari nodesNumInSubtrees objek halaman, jika tidak tidak melakukan apa‑apa. Jangan panggil metode ini saat mengiterasi elemen Pages, karena dapat menghasilkan hasil yang tidak dapat diprediksi. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Proses paragraf untuk generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Menghapus metadata dari dokumen. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Hapus kepatuhan pdfa dari dokumen. |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Hapus kepatuhan pdfUa dari dokumen. |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Memperbaiki dokumen yang rusak. |
| [Save](../../aspose.pdf/document/save/#save)() | Simpan dokumen secara inkremental (misalnya menggunakan teknik pembaruan inkremental). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Menyimpan dokumen dengan opsi penyimpanan. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Menyimpan dokumen ke dalam stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Menyimpan dokumen ke file yang ditentukan. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Menyimpan dokumen dengan nama baru beserta format file. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Menyimpan dokumen ke stream dengan opsi penyimpanan. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Menyimpan dokumen dengan nama baru beserta format file. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Simpan dokumen secara inkremental (misalnya menggunakan teknik pembaruan inkremental). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Menyimpan dokumen dengan opsi penyimpanan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Menyimpan dokumen ke dalam stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Menyimpan dokumen ke file yang ditentukan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Menyimpan dokumen dengan nama baru beserta format file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Menyimpan dokumen ke stream dengan opsi penyimpanan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Menyimpan dokumen dengan nama baru beserta format file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Simpan dokumen ke XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Atur Judul untuk Dokumen Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Atur metadata XMP dokumen. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Validasi dokumen ke file yang ditentukan. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Validasi dokumen ke file yang ditentukan. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Validasi dokumen ke file yang ditentukan. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Mengonversi stream dalam format sumber menjadi stream dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Mengonversi stream dalam format sumber menjadi file tujuan dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Mengonversi file sumber dalam format sumber menjadi stream dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Mengonversi file sumber dalam format sumber menjadi file tujuan dalam format tujuan. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Mengatur batas ukuran file untuk memuat seluruh file ke memori ke nilai default sebesar 210 Mb. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Acara

| Nama | Deskripsi |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Terjadi ketika font menggantikan font lain dalam dokumen. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Mewakili metode yang akan menangani peristiwa FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Menyimpan fungsionalitas untuk menyesuaikan font |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Mewakili opsi untuk metode Merge. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Mewakili opsi untuk memperbaiki dokumen PDF. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


