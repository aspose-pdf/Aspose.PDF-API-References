---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Document. Kelas yang mewakili dokumen PDF
type: docs
weight: 3780
url: /id/net/aspose.pdf/document/
---
## Kelas Dokumen

Kelas yang mewakili dokumen PDF.

```csharp
public sealed class Document : IDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Document](document/#constructor)() | Menginisialisasi dokumen kosong. |
| [Document](document/#constructor_1)(PdfVersion) | Menginisialisasi dokumen kosong berdasarkan versi. |
| [Document](document/#constructor_2)(Stream) | Menginisialisasi instance Dokumen baru dari *input* stream. |
| [Document](document/#constructor_7)(string) | Hanya menginisialisasi Dokumen menggunakan *filename*. Sama dengan [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Menginisialisasi instance Dokumen baru dari *input* stream. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Membuka dokumen yang ada dari stream dengan menyediakan konversi yang diperlukan untuk mendapatkan dokumen pdf. |
| [Document](document/#constructor_5)(Stream, string) | Menginisialisasi instance Dokumen baru dari *input* stream. |
| [Document](document/#constructor_9)(string, bool) | Hanya menginisialisasi Dokumen menggunakan *filename*. Sama dengan [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Membuka dokumen yang ada dari file dengan menyediakan opsi konversi yang diperlukan untuk mendapatkan dokumen pdf. |
| [Document](document/#constructor_10)(string, string) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |
| [Document](document/#constructor_6)(Stream, string, bool) | Menginisialisasi instance Dokumen baru dari *input* stream. |
| [Document](document/#constructor_11)(string, string, bool) | Menginisialisasi instance baru dari kelas `Document` untuk bekerja dengan dokumen terenkripsi. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Mendapatkan tindakan dokumen. Properti ini adalah instance dari kelas DocumentActions yang memungkinkan untuk mendapatkan/mengatur tindakan BeforClosing, BeforSaving, dll. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Memungkinkan untuk menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen. Jika digunakan, maka halaman yang berbeda tetapi duplikat dapat merujuk ke objek konten yang sama. Harap dicatat bahwa mode ini dapat menyebabkan efek samping seperti mengubah konten halaman ketika halaman lain diubah. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Mendapatkan atau mengatur warna latar belakang dokumen. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Mendapatkan koleksi dokumen. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Mendapatkan pengaturan keamanan jika dokumen terenkripsi. Jika dokumen tidak terenkripsi, maka pengecualian yang sesuai akan diangkat di .net 1.1 atau CryptoAlgorithm akan bernilai null untuk versi .net lainnya. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Mendapatkan koleksi tujuan. Usang. Harap gunakan NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Mendapatkan atau mengatur urutan bacaan teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | Banyak operasi dengan font tidak dapat dieksekusi jika operasi ini dilarang oleh lisensi font ini. Misalnya, beberapa font tidak dapat disematkan ke dalam dokumen PDF jika aturan lisensi menonaktifkan penyematan untuk font ini. Flag ini digunakan untuk menonaktifkan batasan lisensi untuk semua font dalam dokumen PDF saat ini. Hati-hati saat menggunakan flag ini. Ketika diatur, itu berarti bahwa orang yang mengatur flag ini, mengambil semua tanggung jawab atas kemungkinan pelanggaran lisensi/hukum pada dirinya sendiri. Jadi dia mengambilnya dengan risikonya sendiri. Sangat disarankan untuk menggunakan flag ini hanya ketika Anda sepenuhnya yakin bahwa Anda tidak melanggar undang-undang hak cipta. Secara default false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang akan digunakan saat mencetak file dari dialog cetak. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Mendapatkan koleksi file yang disematkan ke dokumen. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded diatur ke true. Semua font PDF dapat disematkan ke dalam dokumen hanya dengan mengatur flag IsEmbedded ke true, tetapi font Type1 standar PDF adalah pengecualian dari aturan ini. Penyematan font Type1 standar membutuhkan banyak waktu, jadi untuk menyematkan font ini, perlu tidak hanya mengatur flag IsEmbedded ke true untuk font yang ditentukan tetapi juga mengatur flag tambahan di tingkat dokumen - EmbedStandardFonts = true; Properti ini hanya dapat diatur satu kali untuk semua font. Secara default false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori. Ini memungkinkan untuk mengurangi penggunaan memori tetapi dapat memiliki efek negatif pada kinerja. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. Diaktifkan secara default. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nama file PDF yang menyebabkan dokumen ini |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instance IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Mendapatkan Acro Form dari dokumen. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Mengangkat Pengecualian jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah bilah menu harus disembunyikan saat dokumen aktif. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah toolbar harus disembunyikan saat dokumen aktif. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif. |
| [Id](../../aspose.pdf/document/id/) { get; } | Mendapatkan ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. Ketika halaman dari dokumen sumber disalin ke dalam dokumen tujuan, proses penyalinan dihentikan dengan pengecualian jika beberapa objek dalam file sumber rusak ketika flag ini false. contoh: dest.Pages.Add(src.Pages); Jika flag ini diatur ke true, maka objek yang rusak akan diganti dengan nilai kosong. Secara default: true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Mendapatkan info dokumen. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Mendapatkan status terenkripsi dari dokumen. True jika dokumen terenkripsi. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen telah dilinierkan. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Mendapatkan apakah dokumen sesuai pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Mendapatkan apakah dokumen sesuai pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Mendapatkan atau mengatur apakah dokumen sesuai pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Koleksi JavaScript dari tingkat dokumen. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Mendapatkan struktur logis dari dokumen. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Metadata dokumen. (Dokumen PDF dapat menyertakan informasi umum, seperti judul dokumen, penulis, dan tanggal pembuatan serta modifikasi. Informasi global tentang dokumen (berbeda dari konten atau strukturnya) disebut metadata dan dimaksudkan untuk membantu dalam pengkatalogan dan pencarian dokumen dalam basis data eksternal.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Koleksi Tujuan Bernama dalam dokumen. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Mendapatkan atau mengatur mode halaman, yang menentukan bagaimana menampilkan dokumen saat keluar dari mode layar penuh. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Mendapatkan atau mengatur tindakan yang dilakukan saat membuka dokumen. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Mendapatkan atau mengatur flag optimasi. Ketika halaman ditambahkan ke dokumen, aliran sumber yang sama dalam file hasil digabungkan menjadi satu objek PDF jika flag ini diatur. Ini memungkinkan untuk mengurangi ukuran file hasil tetapi dapat menyebabkan eksekusi yang lebih lambat dan kebutuhan memori yang lebih besar. Nilai default: false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Mendapatkan garis besar dokumen. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Mendapatkan koleksi Output intents dalam dokumen. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Mendapatkan atau mengatur info halaman.(hanya untuk generator, tidak diisi saat membaca dokumen) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Mendapatkan label halaman dalam dokumen. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Mendapatkan atau mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Mendapatkan atau mengatur mode halaman, yang menentukan bagaimana dokumen harus ditampilkan saat dibuka. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Mendapatkan atau mengatur koleksi halaman dokumen. Perhatikan bahwa halaman diberi nomor dari 1 dalam koleksi. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Mendapatkan format PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Mendapatkan izin dokumen. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Mendapatkan atau mengatur flag yang menentukan apakah ukuran halaman PDF harus digunakan untuk memilih baki kertas input. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Mendapatkan atau mengatur opsi skala halaman yang akan dipilih saat dialog cetak ditampilkan untuk dokumen ini. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Mendapatkan akses ke konten TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Mendapatkan versi Pdf dari header file Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Mendapatkan dan mengatur batas ukuran file untuk memuat seluruh file ke dalam memori. Nilai diatur dalam megabyte. Nilai default adalah 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Mendapatkan status berlisensi dari sistem. Mengembalikan true jika sistem bekerja dalam mode berlisensi dan false sebaliknya. |

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
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Mengubah kata sandi dokumen. Tindakan ini hanya dapat dilakukan menggunakan kata sandi pemilik. |
| [Check](../../aspose.pdf/document/check/)(bool) | Memvalidasi dokumen. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Mengonversi dokumen menggunakan opsi konversi yang ditentukan |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Mengenali gambar di dalam dokumen dan menambahkan string hocr di atasnya. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Mengenali gambar di dalam dokumen dan menambahkan string hocr di atasnya. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Mengonversi dokumen dan menyimpan kesalahan ke dalam stream yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Mengonversi dokumen dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Mengonversi dokumen dengan menerapkan Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Mengonversi dokumen dengan menerapkan Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Mengonversi dokumen dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Mengonversi dokumen dan menyimpan kesalahan ke dalam file yang ditentukan. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Mendekripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang didekripsi. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang terenkripsi. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang terenkripsi. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Mengenkripsi dokumen. Panggil kemudian Simpan untuk mendapatkan versi dokumen yang terenkripsi. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Mengekspor semua anotasi dokumen ke dalam stream. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Mengekspor semua anotasi dokumen ke file XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Menghapus semua bidang dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Menghapus semua bidang (dan anotasi) dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Mengganti konten transparan dengan grafik raster dan vektor non-transparan. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Menghapus memori |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Mengembalikan nilai item dari kamus katalog. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Mendapatkan objek dengan ID yang ditentukan dalam dokumen. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Mendapatkan metadata XMP dari dokumen. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Memeriksa apakah dokumen PDF saat ini telah disimpan dengan pembaruan inkremental. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Mengimpor anotasi dari stream ke dokumen. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Mengimpor anotasi dari file XFDF ke dokumen. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Memeriksa apakah dokumen memerlukan panggilan metode Perbaikan. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Memuat file, mengonversinya ke PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Menggabungkan dokumen. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Menggabungkan file pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Menggabungkan dokumen. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Menggabungkan dokumen. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Melinierkan dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data untuk halaman dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. Memanggil metode ini tidak benar-benar menyimpan dokumen. Sebaliknya, dokumen hanya dipersiapkan untuk memiliki struktur yang dioptimalkan, panggil kemudian Simpan untuk mendapatkan dokumen yang dioptimalkan. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Mengoptimalkan sumber daya dalam dokumen: 1. Sumber daya yang tidak digunakan di halaman dokumen dihapus; 2. Sumber daya yang sama digabungkan menjadi satu objek; 3. Objek yang tidak digunakan dihapus. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Mengoptimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Mengorganisir node pohon halaman dalam dokumen menjadi pohon yang seimbang. Hanya jika dokumen memiliki lebih dari nodesNumInSubtrees objek halaman, jika tidak, tidak melakukan apa-apa. Jangan panggil metode ini saat iterasi elemen Halaman, itu dapat memberikan hasil yang tidak terduga |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Memproses paragraf untuk generator. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Menghapus metadata dari dokumen. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Menghapus kepatuhan pdfa dari dokumen |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Menghapus kepatuhan pdfUa dari dokumen |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Memperbaiki dokumen yang rusak. |
| [Save](../../aspose.pdf/document/save/#save)() | Menyimpan dokumen secara inkremental (yaitu menggunakan teknik pembaruan inkremental). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Menyimpan dokumen dengan opsi simpan. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Menyimpan dokumen ke dalam stream. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Menyimpan dokumen dengan nama baru beserta format file. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Menyimpan dokumen ke stream dengan opsi simpan. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Menyimpan dokumen dengan nama baru beserta format file. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Menyimpan dokumen dengan nama baru dengan mengatur opsi simpan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Menyimpan dokumen secara inkremental (yaitu menggunakan teknik pembaruan inkremental). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Menyimpan dokumen dengan opsi simpan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Menyimpan dokumen ke dalam stream. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Menyimpan dokumen dengan nama baru beserta format file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Menyimpan dokumen ke stream dengan opsi simpan. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Menyimpan dokumen dengan nama baru beserta format file. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Menyimpan dokumen dengan nama baru dengan mengatur opsi simpan. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Menyimpan dokumen ke XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Mengatur Judul untuk Dokumen Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Mengatur metadata XMP dari dokumen. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Memvalidasi dokumen ke dalam file yang ditentukan. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Memvalidasi dokumen ke dalam file yang ditentukan. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Memvalidasi dokumen ke dalam file yang ditentukan. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Mengonversi stream dalam format sumber menjadi stream dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Mengonversi stream dalam format sumber menjadi file tujuan dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Mengonversi file sumber dalam format sumber menjadi stream dalam format tujuan. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Mengonversi file sumber dalam format sumber menjadi file tujuan dalam format tujuan. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Mengatur batas ukuran file untuk memuat seluruh file ke dalam memori ke nilai default yang sama dengan 210 Mb. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Acara

| Nama | Deskripsi |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Terjadi ketika font menggantikan font lain dalam dokumen. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Mewakili metode yang akan menangani acara FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Menyimpan fungsionalitas untuk mengatur font |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Mewakili opsi untuk metode Gabung. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Mewakili opsi untuk memperbaiki dokumen PDF. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)