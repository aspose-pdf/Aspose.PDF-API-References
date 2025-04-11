---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.HtmlSaveOptions. Opsi penyimpanan untuk ekspor ke format Html
type: docs
weight: 5560
url: /id/net/aspose.pdf/htmlsaveoptions/
---
## Kelas HtmlSaveOptions

Opsi penyimpanan untuk ekspor ke format Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Menginisialisasi instance baru dari kelas `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Menginisialisasi instance baru dari kelas `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Menginisialisasi instance baru dari kelas `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Menginisialisasi instance baru dari kelas `HtmlSaveOptions`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Mendefinisikan ukuran batch jika konversi batch berlaku untuk pasangan format sumber dan tujuan. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah glyph font akan disimpan saat menyiapkan halaman aps. Meningkatkan kinerja konversi pdf ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau menetapkan nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Mendapatkan atau menetapkan flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke dalam format SVGZ saat menyimpan |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten yang ditandai PDF (lapisan) akan dimasukkan ke dalam div HTML dengan atribut "data-pdflayer" yang menentukan nama lapisan. Nama lapisan ini akan diekstrak dari properti opsional konten yang ditandai PDF. Jika atribut ini false (secara default) maka tidak ada lapisan yang akan dibuat dari konten yang ditandai PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Menentukan nama font yang terinstal yang digunakan untuk menggantikan font dokumen yang tidak disematkan dan tidak terinstal di sistem. Jika null maka font pengganti default digunakan. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Mendapatkan atau menetapkan [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Dengan properti ini Anda dapat secara eksplisit menentukan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. I.e. nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]) Urutan kemunculan halaman dalam daftar ini tidak mempengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan mengikuti urutan di mana mereka hadir dalam PDF sumber. Jika daftar ini null (seperti yang ada secara default), semua halaman akan dikonversi. Jika nomor halaman mana pun dari daftar ini keluar dari rentang halaman yang ada (1-[amountOfPagesInDocument]) pengecualian akan dilemparkan. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks untuk dokumen PDF dengan sublayer OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah HTML dibuat sebagai tata letak tetap. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Atribut ini menentukan teks paragraf lebar penuh untuk mode Flow, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Sumber font dari font yang disimpan sebelumnya. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Teks dengan ukuran tertentu atau lebih kecil akan diabaikan selama konversi. Kami tidak menghapus teks ini, kami mengabaikannya dan tidak mentransfernya ke file output |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Mendapatkan atau menetapkan indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti bahwa kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak benar akan dilewati selama pemrosesan. false secara default |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Mendapatkan atau menetapkan resolusi untuk rendering gambar. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Atribut ini menetapkan lebar minimal jalur grafik. Jika ketebalan garis kurang dari 1px Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku ini untuk browser HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Atribut ini mengaktifkan mode ketika glyph teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan untuk menjaga presisi maksimum selama penempatan glyph di halaman dan dapat digunakan untuk konversi dokumen dengan not musik atau glyph yang harus ditempatkan terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Menunjukkan bahwa font penuh akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Atribut ini menentukan pengelompokan berurutan glyph dan kata menjadi string. Misalnya, tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Ketika mode multipage dipilih (yaitu 'SplitIntoPages' adalah 'true'), maka atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini adalah false, jadi, akan dibuat satu CSS besar umum untuk semua halaman yang dibuat. Ukuran ringkasan semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena dalam kasus sebelumnya kelas CSS adalah duplikat dalam beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini lebih baik digunakan hanya ketika Anda tertarik pada pemrosesan masa depan dari setiap halaman HTML secara independen, dan oleh karena itu ukuran CSS dari setiap halaman diambil terpisah adalah masalah yang paling kritis. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Mendapatkan atau menetapkan flag yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya sendiri, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Mendapatkan atau menetapkan judul halaman HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Flag untuk menggabungkan fragmen gambar menjadi satu gambar. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Jika atribut UseZOrder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai dengan urutan Z dalam dokumen PDF asli. Jika atribut ini false semua grafik ditempatkan sebagai satu lapisan yang dapat menyebabkan beberapa efek yang tidak perlu untuk objek yang tumpang tindih. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah akan Melanjutkan atau Menghentikan. Melanjutkan adalah tindakan default dan operasi Simpan dilanjutkan, namun pengguna juga dapat mengembalikan Hentikan dalam hal ini operasi Simpan harus dihentikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Parameter ini mendefinisikan langkah-langkah antialiasing yang diperlukan selama konversi gambar latar belakang gabungan dari PDF ke HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (sesuatu seperti ".stl_01 {}" ... ".stl_NN {}") dihasilkan dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu, menjadi sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), maka cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak tersentuh (yaitu, null akan dibiarkan sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (itu akan menjadi sesuatu seperti ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi PDF ke HTML untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan tetapkan delegasi yang dibuat dari metode tersebut ke properti ini. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan delegasi yang dibuat dari metode kustom yang mengimplementasikan pemrosesan satu halaman HTML (secara akurat - markup-HTML, tanpa file terkait eksternal jika ada) yang dibuat selama konversi. Dalam hal ini, pemrosesan (seperti menyimpan HTML halaman dalam aliran atau disk) dapat dilakukan dalam kode kustom tersebut. Dalam hal ini, semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disuplai, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter itu sendiri, bukan dalam kode kustom, silakan atur dalam kode kustom flag 'CustomProcessingCancelled' dari variabel parameter 'htmlSavingInfo': itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk pemrosesan sumber daya tersebut harus dilakukan dalam konverter itu sendiri dengan cara yang sama seolah-olah tidak ada kode kustom eksternal untuk pemrosesan. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Pengendali ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya, dapat digunakan untuk menunjukkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode pengendali yang menunjukkan kemajuan di konsol adalah: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan kustom dari file sumber daya yang dirujuk yang dibuat (seperti gambar dan font) yang terkait dengan node HTML yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URL yang diinginkan dari sumber daya yang disimpan dalam HTML yang dihasilkan. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Bidang ini dapat berisi metode kustom yang mengembalikan URL (atau template URL jika generasi multipage diaktifkan - lihat detail di bawah) dari CSS subjek seperti yang harus dimasukkan dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu sebagai pengganti nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan metode yang menghasilkan URL yang diinginkan ke dalam properti ini. Jika flag 'SplitCssIntoPages' diatur, maka strategi kustom ini (jika ada) harus mengembalikan bukan URL CSS yang tepat tetapi lebih tepatnya string template yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi string.Format() di dalam konverter) dapat diselesaikan menjadi URL untuk URL CSS halaman ini atau itu. Contoh string yang diharapkan dalam kasus seperti itu adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Daftar nama font PDF yang disematkan yang tidak akan disematkan dalam HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Mendefinisikan aturan pengkodean khusus untuk menyesuaikan dekode PDF untuk dokumen saat ini |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Mendefinisikan mode penyimpanan font yang akan digunakan selama penyimpanan PDF ke format yang diinginkan |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Terkadang persyaratan khusus untuk pembuatan markup HTML ada. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Memproses halaman dalam beberapa utas. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Mengatur mode penempatan huruf dalam kata di HTML hasil |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Atribut ini mewakili sekumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. Pada dasarnya ini berkaitan dengan menunjukkan tepi kertas halaman, bukan batas halaman yang dirujuk dalam halaman PDF itu sendiri. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Atribut ini mewakili sekumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input akan dimasukkan ke dalam satu file HTML hasil yang besar. Flag ini menentukan apakah HTML hasil akan dihasilkan sedemikian rupa sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar pemirsa. Misalkan lebar layar di sisi pemirsa cukup besar untuk menempatkan 2 atau lebih halaman berdampingan dalam arah horizontal. Jika flag ini diatur ke true, maka kesempatan ini akan digunakan (sebanyak mungkin halaman akan ditampilkan dalam arah horizontal berdampingan satu sama lain, kemudian kelompok halaman horizontal berikutnya akan ditampilkan di bawah yang pertama). Jika tidak, halaman akan mengalir dengan cara berikut: halaman berikutnya selalu berada di bawah halaman sebelumnya. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Ini menentukan apakah file yang dirujuk (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | PDF yang dikonversi dapat berisi gambar raster. Parameter ini menentukan bagaimana mereka harus ditangani selama konversi PDF ke HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Menentukan apakah area kosong di bagian atas dan bawah yang tidak memiliki konten (jika ada) akan dihapus dalam HTML yang dibuat. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF dapat berisi teks yang dibayangi oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya ini terjadi ketika dokumen berisi gambar dan teks yang di-OCR dari itu). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (jika tidak, teks tersebut biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya ini terjadi ketika dokumen berisi gambar dan teks yang di-OCR dari itu). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Mendapatkan atau menetapkan jalur ke direktori tempat semua gambar harus disimpan jika mereka ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null maka file gambar (jika ada) akan disimpan bersama dengan file lain yang terkait dengan HTML. Ini tidak mempengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Mendapatkan atau menetapkan jalur ke direktori tempat hanya gambar SVG harus disimpan jika mereka ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null maka file SVG (jika ada) akan disimpan bersama dengan file gambar lainnya (dekat dengan file output) atau di folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Ini tidak mempengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang yang sama yang diletakkan berdampingan. Dalam hal ini, perender format target (misalnya MsWord untuk format DOCS) terkadang menghasilkan batas yang terlihat antara bagian gambar latar belakang, karena teknik penghalusan tepi gambar mereka (anti-aliasing) berbeda dari Acrobat Reader. Jika terlihat bahwa dokumen yang diekspor mengandung batas yang terlihat antara bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan tersebut. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, silakan gunakan opsi ini hanya ketika benar-benar diperlukan. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF itu sendiri tidak mengandung penanda penggarisan untuk teks. Ini disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah penggarisan teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar penggarisan secara grafis |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Lihat Juga

* kelas [UnifiedSaveOptions](../unifiedsaveoptions/)
* antarmuka [IPageSetOptions](../ipagesetoptions/)
* antarmuka [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)