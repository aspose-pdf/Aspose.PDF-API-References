---
title: "Kelas HtmlSaveOptions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.HtmlSaveOptions. Opsi penyimpanan untuk ekspor ke format Html"
type: docs
weight: 5690
url: /id/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Opsi penyimpanan untuk mengekspor ke format Html

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah glif font akan di-cache saat menyiapkan halaman aps. Meningkatkan kinerja konversi PDF ke format lain tetapi meningkatkan konsumsi memori. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam respons. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Mendapatkan atau mengatur flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke format SVGZ selama penyimpanan. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten PDF yang ditandai (lapisan) akan ditempatkan ke dalam div HTML dengan atribut "data-pdflayer" yang menentukan nama lapisan. Nama lapisan ini akan diambil dari properti opsional dari konten PDF yang ditandai. Jika atribut ini false (secara default) maka tidak ada lapisan yang akan dibuat dari konten PDF yang ditandai. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Menentukan nama font yang terpasang yang digunakan untuk menggantikan font dokumen apa pun yang tidak tersemat dan tidak terpasang di sistem. Jika null maka font substitusi default akan digunakan. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Mendapatkan atau mengatur [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Dengan properti ini Anda dapat secara eksplisit menentukan halaman mana dari dokumen yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan mengikuti urutan di mana mereka hadir dalam PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) maka pengecualian akan dilempar. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Atribut ini mengaktifkan fungsionalitas untuk mengekstrak gambar atau teks dari dokumen PDF dengan sublayer OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Atribut ini menentukan teks paragraf lebar penuh untuk mode Flow, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Sumber font dari font yang telah disimpan sebelumnya. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Teks dengan ukuran yang ditentukan atau lebih kecil akan diabaikan selama konversi. Kami tidak menghapus teks ini, kami mengabaikannya dan tidak mentransfernya ke file output. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan ketidakhadiran font akan diabaikan. true - berarti bahwa kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false secara default |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Mendapatkan atau mengatur resolusi untuk rendering gambar. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Atribut ini mengatur lebar minimal garis jalur grafis. Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku tersebut pada peramban HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Atribut ini mengaktifkan mode di mana glif teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan mempertahankan presisi maksimum selama penempatan glif pada halaman dan dapat digunakan untuk mengonversi dokumen dengan notasi musik atau glif yang harus ditempatkan terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format penyimpanan data. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Atribut ini menentukan pengelompokan berurutan glif dan kata menjadi string. Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Ketika mode multipage dipilih (misalnya 'SplitIntoPages' adalah 'true'), atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini false, sehingga akan dibuat satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena pada kasus pertama kelas CSS duplikat di beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik pada pemrosesan masing-masing halaman HTML secara terpisah, dan oleh karena itu ukuran CSS untuk setiap halaman yang dipisahkan menjadi isu paling kritis. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Mendapatkan atau mengatur flag yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya masing-masing, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Mendapatkan atau mengatur judul halaman HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Flag untuk menggabungkan fragmen gambar menjadi satu gambar. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik diletakkan sebagai lapisan tunggal yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback untuk menangani peringatan apa pun yang dihasilkan. WarningHandler mengembalikan item enum ReturnAction yang menentukan Continue atau Abort. Continue adalah tindakan default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus berhenti. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang komposit dari PDF ke HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (misalnya \".stl_01 {}\" ... \".stl_NN {}\") dibuat dan digunakan dalam CSS hasil. Properti ini memungkinkan memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu seperti 'my_prefix_1' ... 'my_prefix_NNN'), cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak berubah (misalnya null akan dibiarkan sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (akan menjadi sesuatu seperti \".stl_01 {}\" ... \".stl_NN {}\"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi Pdf ke Html untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan tetapkan delegasi yang dibuat darinya ke properti ini. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file eksternal yang ditautkan jika ada) yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan (seperti menyimpan HTML halaman ke aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Dalam kasus tersebut semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' pada variabel parameter 'htmlSavingInfo': itu akan memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah-olah tidak ada kode khusus eksternal untuk pemrosesan. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Handler ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode handler yang menampilkan kemajuan di konsol adalah: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file sumber daya yang direferensikan (seperti gambar dan font) yang terkait dengan node HTML yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URL yang diinginkan untuk sumber daya yang disimpan dalam HTML yang dihasilkan. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika generasi multi‑halaman diaktifkan – lihat detail di bawah) dari CSS subjek sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu alih‑alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan ke properti ini metode yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi khusus ini (jika ada) harus mengembalikan bukan URL CSS yang tepat melainkan string templat yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi string.Format() di dalam konverter) dapat diubah menjadi URL untuk URL CSS halaman tertentu. Contoh string yang diharapkan dikembalikan dalam kasus tersebut adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Daftar nama font PDF yang tertanam yang tidak akan disematkan dalam HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekode PDF untuk dokumen saat ini |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Mendefinisikan mode penyimpanan font yang akan digunakan selama penyimpanan PDF ke format yang diinginkan |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Terkadang persyaratan khusus untuk pembuatan markup HTML muncul. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Proses halaman dengan beberapa thread. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Mengatur mode penempatan huruf dalam kata pada HTML hasil |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Atribut ini mewakili sekumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. Pada dasarnya ini berkaitan dengan penampilan tepi kertas halaman, bukan batas halaman yang direferensikan dalam halaman PDF itu sendiri. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Atribut ini mewakili sekumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input akan dimasukkan ke dalam satu file HTML hasil yang besar. Flag ini menentukan apakah HTML hasil akan dihasilkan dengan cara aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar penampil. Misalkan lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan secara horizontal. Jika flag ini diatur ke true, maka kesempatan ini akan digunakan (sebanyak mungkin halaman akan ditampilkan secara horizontal berdampingan, kemudian grup horizontal berikutnya akan ditampilkan di bawah grup pertama). Jika tidak, halaman akan mengalir dengan cara: halaman berikutnya selalu berada di bawah halaman sebelumnya. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Ini menentukan apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | PDF yang dikonversi dapat berisi gambar raster. Parameter ini menentukan bagaimana mereka harus diproses selama konversi PDF ke HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Menentukan apakah area kosong di bagian atas dan bawah pada HTML yang dibuat akan dihapus tanpa konten apa pun (jika ada). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDF dapat berisi teks yang tertutup oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR dari gambar tersebut). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks semacam itu biasanya disimpan sebagai tersembunyi, tidak dapat disalin ke clipboard). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDF dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR dari gambar tersebut). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Mendapatkan atau mengatur jalur ke direktori tempat semua gambar harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML. Hal ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Mendapatkan atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (di dekat file output) atau di folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Hal ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Terkadang PDF berisi gambar latar belakang (halaman atau sel tabel) yang dibangun dari beberapa gambar latar belakang berulang yang ditempatkan berdekatan. Dalam kasus seperti itu, renderer format target (mis. MsWord untuk format DOCS) kadang menghasilkan batas yang terlihat antara bagian-bagian gambar latar belakang, karena teknik penyamaran tepi gambar (anti-aliasing) mereka berbeda dari Acrobat Reader. Jika tampak bahwa dokumen yang diekspor mengandung batas terlihat antara bagian-bagian gambar latar belakang yang sama, silakan coba gunakan pengaturan ini untuk menghilangkan efek yang tidak diinginkan. PERHATIAN! Optimasi kualitas ini biasanya secara signifikan memperlambat konversi, jadi, harap gunakan opsi ini hanya ketika benar‑benar diperlukan. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | PDF sendiri tidak berisi penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis tertentu merupakan garis bawah teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis. |

## Contoh

Contoh berikut menunjukkan cara mengonversi file PDF ke file HTML

```csharp
[C#]
	// Jalur ke direktori dokumen.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Jalur ke File PDF Anda.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// Jalur ke File HTML output.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Inisialisasi HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Simpan file HTML
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


