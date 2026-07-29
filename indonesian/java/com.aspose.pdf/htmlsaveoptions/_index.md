---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format HTML"
type: docs
weight: 1990
url: /id/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Opsi penyimpanan untuk ekspor ke format HTML

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Menginisialisasi instance baru dari kelas HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Menginisialisasi instance baru dari kelas {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Menginisialisasi instance baru dari kelas HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Menginisialisasi instance baru dari kelas HtmlSaveOptions. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input tidak akan dipisahkan menjadi halaman HTML yang berbeda, melainkan akan ditempatkan dalam satu file HTML hasil yang besar. Namun setiap halaman PDF sumber akan ditampilkan dengan area persegi panjangnya sendiri dalam HTML (jika diperlukan area tersebut dapat diberi batas untuk menunjukkan tepi kertas halaman dengan atribut khusus 'PageBorderIfAny'). Parameter ini menentukan lebar margin yang akan dipaksa dibiarkan di sekitar area HTML keluaran yang mewakili halaman dokumen PDF sumber. Pada dasarnya parameter ini menentukan interval yang dijamin antara representasi HTML dari halaman \"kertas\" PDF dalam mode konversi ini. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang komposit dari PDF ke HTML. |
| [getBatchSize](#getBatchSize--) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (misalnya \".stl_01 {}\" ... \".stl_NN {}\") dibuat dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak berubah (misalnya null akan tetap sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (akan menjadi sesuatu seperti \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi PDF ke HTML untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan Tetapkan delegasi yang dibuat darinya ke properti ini. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file eksternal yang ditautkan jika ada) yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan (seperti penyimpanan HTML halaman dalam aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Dalam kasus tersebut semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'htmlSavingInfo': itu akan memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah-olah tidak ada kode khusus eksternal untuk pemrosesan. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Penangan ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode penangan yang menampilkan kemajuan di konsol adalah: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file sumber daya yang direferensikan yang dibuat (seperti gambar dan font) terkait dengan node HTML yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URL yang diinginkan untuk sumber daya yang disimpan dalam HTML yang dihasilkan. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika pembuatan multi‑halaman diaktifkan – lihat detail di bawah) dari CSS yang bersangkutan sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu alih‑alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan ke properti ini metode yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi khusus ini (jika ada) harus mengembalikan bukan URL CSS yang tepat melainkan string templat yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi String.Format() di dalam konverter) dapat diubah menjadi URL untuk URL CSS halaman tertentu. Contoh string yang diharapkan dikembalikan dalam kasus tersebut adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Menentukan nama font yang terpasang yang digunakan untuk menggantikan font dokumen apa pun yang tidak tertanam dan tidak terpasang di sistem. Jika null maka font pengganti default akan digunakan. |
| [getDocumentType](#getDocumentType--) | Mengambil {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Daftar nama font PDF yang disematkan yang tidak akan disematkan dalam HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Dengan properti ini Anda dapat secara eksplisit menentukan halaman dokumen mana yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan ditampilkan dalam urutan yang ada di PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) akan dilemparkan pengecualian. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Atribut ini menentukan teks paragraf lebar penuh untuk mode Aliran, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekode PDF untuk dokumen saat ini |
| [getFontSavingMode](#getFontSavingMode--) | Mendefinisikan mode penyimpanan font yang akan digunakan saat menyimpan PDF ke format yang diinginkan |
| [getFontSources](#getFontSources--) | <p> Sumber font dari font yang telah disimpan sebelumnya. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Kadang-kadang persyaratan khusus untuk pembuatan markup HTML muncul. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| [getImageResolution](#getImageResolution--) | Mendapatkan atau mengatur resolusi untuk rendering gambar. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Mengatur mode penempatan huruf dalam kata pada HTML hasil |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Atribut ini mengatur lebar minimal garis jalur grafis. Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku tersebut pada peramban HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Atribut ini mewakili kumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. Pada dasarnya ini berkaitan dengan penampilan tepi kertas halaman, bukan batas halaman yang dirujuk dalam halaman PDF itu sendiri. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Atribut ini mewakili kumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Ini mendefinisikan apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | PDF yang dikonversi dapat berisi gambar raster. Parameter ini mendefinisikan bagaimana mereka harus diproses selama konversi PDF ke HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Mendapatkan atau mengatur jalur ke direktori tempat semua gambar yang ditemui selama penyimpanan dokumen sebagai HTML harus disimpan. Jika parameter kosong atau null, maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML. Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Mendapatkan atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (dekat file output) atau dalam folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [getTitle](#getTitle--) | Mendapatkan atau mengatur judul halaman HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Mendapatkan flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke format SVGZ selama penyimpanan. Nilai: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten berpenanda PDF (lapisan) akan ditempatkan ke dalam div HTML dengan atribut \"data-pdflayer\" yang menentukan nama lapisan. Nama lapisan ini akan diambil dari properti opsional konten berpenanda PDF. Jika atribut ini false (default), maka tidak ada lapisan yang akan dibuat dari konten berpenanda PDF. |
| [isFixedLayout](#isFixedLayout--) | Mendapatkan nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF masukan akan dimasukkan ke dalam satu file HTML hasil yang besar. Bendera ini menentukan apakah HTML hasil akan dihasilkan dengan cara sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar penampil. Misalkan lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan secara horizontal. Jika bendera ini diatur ke true, maka kesempatan ini akan digunakan (sejumlah halaman akan ditampilkan secara horizontal berdampingan sebanyak mungkin, kemudian grup horizontal berikutnya akan ditampilkan di bawah yang pertama). Sebaliknya, halaman akan mengalir dengan cara: halaman berikutnya selalu berada di bawah halaman sebelumnya. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Atribut ini mengaktifkan mode di mana glif teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan mempertahankan presisi maksimum selama penempatan glif pada halaman dan dapat digunakan untuk konversi dokumen dengan notasi musik atau glif yang harus ditempatkan secara terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Menentukan apakah pada HTML yang dibuat area kosong di bagian atas dan bawah tanpa konten apa pun (jika ada) akan dihapus. |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar. |
| [isSaveFullFont](#isSaveFullFont--) | Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Pdf dapat berisi teks yang dibayangi oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks semacam itu biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Atribut ini menentukan pengelompokan berurutan dari glif dan kata menjadi string. Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Ketika mode multipage dipilih (misalnya 'SplitIntoPages' adalah 'true'), maka atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini false, sehingga akan dibuat satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena dalam kasus pertama kelas CSS duplikat di beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik pada pemrosesan masing-masing halaman HTML secara terpisah di masa depan, dan oleh karena itu ukuran CSS setiap halaman yang dipisahkan menjadi isu paling kritis. |
| [isSplitIntoPages](#isSplitIntoPages--) | Mengambil bendera yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya masing-masing, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF sendiri tidak berisi penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah garis bawah teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis. |
| [isUseZOrder](#isUseZOrder--) | Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik ditempatkan sebagai satu lapisan yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input tidak akan dipisahkan menjadi halaman HTML yang berbeda, melainkan akan ditempatkan dalam satu file HTML hasil yang besar. Namun setiap halaman PDF sumber akan ditampilkan dengan area persegi panjangnya sendiri dalam HTML (jika diperlukan area tersebut dapat diberi batas untuk menunjukkan tepi kertas halaman dengan atribut khusus 'PageBorderIfAny'). Parameter ini menentukan lebar margin yang akan dipaksa dibiarkan di sekitar area HTML keluaran yang mewakili halaman dokumen PDF sumber. Pada dasarnya parameter ini menentukan interval yang dijamin antara representasi HTML dari halaman \"kertas\" PDF dalam mode konversi ini. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang komposit dari PDF ke HTML. |
| [setBatchSize](#setBatchSize-int-) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Mengatur flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke format SVGZ saat penyimpanan Nilai: yang {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten berpenanda PDF (lapisan) akan ditempatkan ke dalam div HTML dengan atribut \"data-pdflayer\" yang menentukan nama lapisan. Nama lapisan ini akan diambil dari properti opsional konten berpenanda PDF. Jika atribut ini false (default), maka tidak ada lapisan yang akan dibuat dari konten berpenanda PDF. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (misalnya \".stl_01 {}\" ... \".stl_NN {}\") dibuat dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak berubah (misalnya null akan tetap sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (akan menjadi sesuatu seperti \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi PDF ke HTML untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan Tetapkan delegasi yang dibuat darinya ke properti ini. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file terhubung eksternal jika ada) yang dibuat selama konversi. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file sumber daya yang direferensikan (seperti gambar dan font) yang terkait dengan node HTML yang disimpan. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika generasi multi‑halaman diaktifkan – lihat detail di bawah) dari CSS yang bersangkutan sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Menentukan nama font yang terpasang yang digunakan untuk menggantikan font dokumen apa pun yang tidak tertanam dan tidak terpasang di sistem. Jika null maka font pengganti default akan digunakan. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Mengatur {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Daftar nama font PDF yang disematkan yang tidak akan disematkan dalam HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Dengan properti ini Anda dapat secara eksplisit menentukan halaman dokumen mana yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan ditampilkan dalam urutan yang ada di PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) akan dilemparkan pengecualian. |
| [setFixedLayout](#setFixedLayout-boolean-) | Mengatur nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Atribut ini menentukan teks paragraf lebar penuh untuk mode Aliran, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekode PDF untuk dokumen saat ini |
| [setFontSavingMode](#setFontSavingMode-int-) | Mendefinisikan mode penyimpanan font yang akan digunakan saat menyimpan PDF ke format yang diinginkan |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Kadang-kadang persyaratan khusus untuk pembuatan markup HTML muncul. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default |
| [setImageResolution](#setImageResolution-int-) | Mendapatkan atau mengatur resolusi untuk rendering gambar. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Mengatur mode penempatan huruf dalam kata pada HTML hasil |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Atribut ini mengatur lebar minimal garis jalur grafis. Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku tersebut pada peramban HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Atribut ini mewakili kumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Atribut ini mewakili kumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF masukan akan dimasukkan ke dalam satu file HTML hasil yang besar. Bendera ini menentukan apakah HTML hasil akan dihasilkan dengan cara sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar penampil. Misalkan lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan secara horizontal. Jika bendera ini diatur ke true, maka kesempatan ini akan digunakan (sejumlah halaman akan ditampilkan secara horizontal berdampingan sebanyak mungkin, kemudian grup horizontal berikutnya akan ditampilkan di bawah yang pertama). Sebaliknya, halaman akan mengalir dengan cara: halaman berikutnya selalu berada di bawah halaman sebelumnya. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Ini mendefinisikan apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Atribut ini mengaktifkan mode di mana glif teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan mempertahankan presisi maksimum selama penempatan glif pada halaman dan dapat digunakan untuk konversi dokumen dengan notasi musik atau glif yang harus ditempatkan secara terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | PDF yang dikonversi dapat berisi gambar raster. Parameter ini mendefinisikan bagaimana mereka harus diproses selama konversi PDF ke HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Menentukan apakah pada HTML yang dibuat area kosong di bagian atas dan bawah tanpa konten apa pun (jika ada) akan dihapus. |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf dapat berisi teks yang dibayangi oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks semacam itu biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Atribut ini menentukan pengelompokan berurutan dari glif dan kata menjadi string. Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Mendapatkan atau mengatur jalur ke direktori tempat semua gambar yang ditemui selama penyimpanan dokumen sebagai HTML harus disimpan. Jika parameter kosong atau null, maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML. Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Mendapatkan atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (dekat file output) atau dalam folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Ketika mode multipage dipilih (misalnya 'SplitIntoPages' adalah 'true'), maka atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini false, sehingga akan dibuat satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena dalam kasus pertama kelas CSS duplikat di beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik pada pemrosesan masing-masing halaman HTML secara terpisah di masa depan, dan oleh karena itu ukuran CSS setiap halaman yang dipisahkan menjadi isu paling kritis. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Mengatur flag yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya masing‑masing, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML. |
| [setTitle](#setTitle-java.lang.String-) | Mendapatkan atau mengatur judul halaman HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF sendiri tidak berisi penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah garis bawah teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis. |
| [setUseZOrder](#setUseZOrder-boolean-) | Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik ditempatkan sebagai satu lapisan yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Menginisialisasi instance baru dari kelas HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Menginisialisasi instance baru dari kelas {@code HtmlSaveOptions}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fixedLayout |  | nilai boolean |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Menginisialisasi instance baru dari kelas HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Menginisialisasi instance baru dari kelas HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input tidak akan dipisahkan menjadi halaman HTML yang berbeda, melainkan akan ditempatkan dalam satu file HTML hasil yang besar. Namun setiap halaman PDF sumber akan ditampilkan dengan area persegi panjangnya sendiri dalam HTML (jika diperlukan area tersebut dapat diberi batas untuk menunjukkan tepi kertas halaman dengan atribut khusus 'PageBorderIfAny'). Parameter ini menentukan lebar margin yang akan dipaksa dibiarkan di sekitar area HTML keluaran yang mewakili halaman dokumen PDF sumber. Pada dasarnya parameter ini menentukan interval yang dijamin antara representasi HTML dari halaman \"kertas\" PDF dalam mode konversi ini.

**Returns:**
nilai int @deprecated AdditionalMarginWidthInPoints sudah tidak dipakai, silakan gunakan PageMarginIfAny sebagai gantinya.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang komposit dari PDF ke HTML.

**Returns:**
elemen AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Returns:**
nilai int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (misalnya \".stl_01 {}\" ... \".stl_NN {}\") dibuat dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak berubah (misalnya null akan tetap sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (akan menjadi sesuatu seperti \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
nilai String

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi PDF ke HTML untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan Tetapkan delegasi yang dibuat darinya ke properti ini.

**Returns:**
instansi CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file eksternal yang ditautkan jika ada) yang dibuat selama konversi. Dalam kasus seperti itu, pemrosesan (seperti penyimpanan HTML halaman dalam aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Dalam kasus tersebut semua tindakan yang diperlukan untuk menyimpan halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'htmlSavingInfo': itu akan memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri dengan cara yang sama seolah-olah tidak ada kode khusus eksternal untuk pemrosesan.

**Returns:**
instansi HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Penangan ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya dapat digunakan untuk menampilkan bilah kemajuan atau pesan tentang jumlah halaman yang sedang diproses, contoh kode penangan yang menampilkan kemajuan di konsol adalah: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense(\"Aspose.Total.lic\"); Document doc = new Document(\"Booklet.pdf\"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save(\"Booklet.doc\", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format(\"%s - Conversion progress : %d % .\", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format(\"%s - Source page %d of %d analyzed.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format(\"%s - Result page's %d of %d layout created.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format(\"%s - Result page %d of %d exported.\", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
instansi ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file sumber daya yang direferensikan yang dibuat (seperti gambar dan font) terkait dengan node HTML yang disimpan. Strategi tersebut harus memproses sumber daya dan mengembalikan string yang mewakili URL yang diinginkan untuk sumber daya yang disimpan dalam HTML yang dihasilkan.

**Returns:**
instansi ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika pembuatan multi‑halaman diaktifkan – lihat detail di bawah) dari CSS yang bersangkutan sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan. Misalnya, jika Anda ingin konverter menempatkan URL tertentu alih‑alih nama file CSS standar ke dalam CSS yang dihasilkan, maka Anda cukup membuat dan menempatkan ke properti ini metode yang menghasilkan URL yang diinginkan. Jika flag 'SplitCssIntoPages' diatur, maka strategi khusus ini (jika ada) harus mengembalikan bukan URL CSS yang tepat melainkan string templat yang (setelah penggantian placeholder dengan nomor halaman menggunakan fungsi String.Format() di dalam konverter) dapat diubah menjadi URL untuk URL CSS halaman tertentu. Contoh string yang diharapkan dikembalikan dalam kasus tersebut adalah: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
instansi CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Menentukan nama font yang terpasang yang digunakan untuk menggantikan font dokumen apa pun yang tidak tertanam dan tidak terpasang di sistem. Jika null maka font pengganti default akan digunakan.

**Returns:**
nilai String: Nama font

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Mengambil {@code HtmlDocumentTypeInternal}.

**Returns:**
yang {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Daftar nama font PDF yang disematkan yang tidak akan disematkan dalam HTML.

**Returns:**
array elemen String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Dengan properti ini Anda dapat secara eksplisit menentukan halaman dokumen mana yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan ditampilkan dalam urutan yang ada di PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) akan dilemparkan pengecualian.

**Returns:**
array int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Atribut ini menentukan teks paragraf lebar penuh untuk mode Aliran, FixedLayout = false

**Returns:**
nilai boolean

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekode PDF untuk dokumen saat ini

**Returns:**
elemen FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Mendefinisikan mode penyimpanan font yang akan digunakan saat menyimpan PDF ke format yang diinginkan

**Returns:**
elemen FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Sumber font dari font yang telah disimpan sebelumnya. </p>

**Returns:**
objek FontSourceCollection <hr> <p> Font dapat disimpan terlebih dahulu untuk tujuan cache dan kemudian diteruskan ke proses konversi Html. Misalnya, ini dapat berguna dalam skenario pemisahan dokumen dan pemrosesan halaman dokumen dalam beberapa thread dengan satu set font. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Kadang-kadang persyaratan khusus untuk pembuatan markup HTML muncul. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut.

**Returns:**
elemen HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Mendapatkan atau mengatur resolusi untuk rendering gambar.

**Returns:**
Nilai: Resolusi

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Mengatur mode penempatan huruf dalam kata pada HTML hasil

**Returns:**
Elemen LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Atribut ini mengatur lebar minimal garis jalur grafis. Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku tersebut pada peramban HTML.

**Returns:**
nilai float

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Atribut ini mewakili kumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber. Pada dasarnya ini berkaitan dengan penampilan tepi kertas halaman, bukan batas halaman yang dirujuk dalam halaman PDF itu sendiri.

**Returns:**
Instansi BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Atribut ini mewakili kumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber.

**Returns:**
Instansi MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Ini mendefinisikan apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah

**Returns:**
Elemen PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

PDF yang dikonversi dapat berisi gambar raster. Parameter ini mendefinisikan bagaimana mereka harus diproses selama konversi PDF ke HTML

**Returns:**
Elemen RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Mendapatkan atau mengatur jalur ke direktori tempat semua gambar yang ditemui selama penyimpanan dokumen sebagai HTML harus disimpan. Jika parameter kosong atau null, maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML. Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan.

**Returns:**
nilai String

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Mendapatkan atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (dekat file output) atau dalam folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan.

**Returns:**
nilai String

### getTitle {#getTitle--}
```
public final String getTitle()
```

Mendapatkan atau mengatur judul halaman HTML.

**Returns:**
nilai String

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Mendapatkan flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke format SVGZ selama penyimpanan. Nilai: {@code HtmlDocumentType}.

**Returns:**
nilai boolean

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten berpenanda PDF (lapisan) akan ditempatkan ke dalam div HTML dengan atribut \"data-pdflayer\" yang menentukan nama lapisan. Nama lapisan ini akan diambil dari properti opsional konten berpenanda PDF. Jika atribut ini false (default), maka tidak ada lapisan yang akan dibuat dari konten berpenanda PDF.

**Returns:**
nilai boolean

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Mendapatkan nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap.

**Returns:**
nilai: {@code true} jika [fixed layout]; sebaliknya, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default

**Returns:**
nilai boolean

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF masukan akan dimasukkan ke dalam satu file HTML hasil yang besar. Bendera ini menentukan apakah HTML hasil akan dihasilkan dengan cara sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar penampil. Misalkan lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan secara horizontal. Jika bendera ini diatur ke true, maka kesempatan ini akan digunakan (sejumlah halaman akan ditampilkan secara horizontal berdampingan sebanyak mungkin, kemudian grup horizontal berikutnya akan ditampilkan di bawah yang pertama). Sebaliknya, halaman akan mengalir dengan cara: halaman berikutnya selalu berada di bawah halaman sebelumnya.

**Returns:**
nilai boolean

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Atribut ini mengaktifkan mode di mana glif teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan mempertahankan presisi maksimum selama penempatan glif pada halaman dan dapat digunakan untuk konversi dokumen dengan notasi musik atau glif yang harus ditempatkan secara terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true.

**Returns:**
nilai boolean

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Menentukan apakah pada HTML yang dibuat area kosong di bagian atas dan bawah tanpa konten apa pun (jika ada) akan dihapus.

**Returns:**
nilai boolean

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar.

**Returns:**
nilai boolean

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen.

**Returns:**
nilai boolean

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Pdf dapat berisi teks yang dibayangi oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks semacam itu biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard).

**Returns:**
nilai boolean

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil.

**Returns:**
nilai boolean

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Atribut ini menentukan pengelompokan berurutan dari glif dan kata menjadi string. Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true.

**Returns:**
nilai boolean

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Ketika mode multipage dipilih (misalnya 'SplitIntoPages' adalah 'true'), maka atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini false, sehingga akan dibuat satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena dalam kasus pertama kelas CSS duplikat di beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik pada pemrosesan masing-masing halaman HTML secara terpisah di masa depan, dan oleh karena itu ukuran CSS setiap halaman yang dipisahkan menjadi isu paling kritis.

**Returns:**
nilai boolean

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Mengambil bendera yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya masing-masing, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML.

**Returns:**
nilai boolean

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF sendiri tidak berisi penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah garis bawah teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis.

**Returns:**
nilai boolean

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik ditempatkan sebagai satu lapisan yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih.

**Returns:**
nilai boolean

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF input tidak akan dipisahkan menjadi halaman HTML yang berbeda, melainkan akan ditempatkan dalam satu file HTML hasil yang besar. Namun setiap halaman PDF sumber akan ditampilkan dengan area persegi panjangnya sendiri dalam HTML (jika diperlukan area tersebut dapat diberi batas untuk menunjukkan tepi kertas halaman dengan atribut khusus 'PageBorderIfAny'). Parameter ini menentukan lebar margin yang akan dipaksa dibiarkan di sekitar area HTML keluaran yang mewakili halaman dokumen PDF sumber. Pada dasarnya parameter ini menentukan interval yang dijamin antara representasi HTML dari halaman \"kertas\" PDF dalam mode konversi ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @deprecated AdditionalMarginWidthInPoints sudah tidak dipakai, silakan gunakan PageMarginIfAny sebagai gantinya. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Parameter ini menentukan langkah antialiasing yang diperlukan selama konversi gambar latar belakang komposit dari PDF ke HTML.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| antialiasingProcessing |  | elemen AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Mengatur flag yang menunjukkan apakah grafik SVG yang ditemukan (jika ada) akan dikompresi (dizip) ke format SVGZ saat penyimpanan Nilai: yang {@code HtmlDocumentType}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Jika atribut ConvertMarkedContentToLayers diatur ke true maka semua elemen di dalam konten berpenanda PDF (lapisan) akan ditempatkan ke dalam div HTML dengan atribut \"data-pdflayer\" yang menentukan nama lapisan. Nama lapisan ini akan diambil dari properti opsional konten berpenanda PDF. Jika atribut ini false (default), maka tidak ada lapisan yang akan dibuat dari konten berpenanda PDF.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Ketika konverter PDFtoHTML menghasilkan CSS hasil, nama kelas CSS (misalnya \".stl_01 {}\" ... \".stl_NN {}\") dibuat dan digunakan dalam CSS hasil. Properti ini memungkinkan untuk memaksa menetapkan awalan nama kelas. Misalnya, jika Anda ingin semua nama kelas dimulai dengan 'my_prefix_' (yaitu sesuatu seperti 'my_prefix_1' ... 'my_prefix_NNN'), cukup tetapkan 'my_prefix_' ke properti ini sebelum konversi. Jika properti ini dibiarkan tidak berubah (misalnya null akan tetap sebagai nilai), maka konverter akan menghasilkan nama kelas sendiri (akan menjadi sesuatu seperti \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi PDF ke HTML untuk menangani penyimpanan CSS yang terkait dengan dokumen HTML yang dibuat secara keseluruhan atau ke halamannya (jika beberapa halaman HTML dihasilkan). Jika Anda ingin menangani file CSS dengan cara tertentu, silakan buat metode yang relevan dan Tetapkan delegasi yang dibuat darinya ke properti ini.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Hasil konversi dapat berisi satu atau beberapa halaman HTML. Anda dapat menetapkan ke properti ini delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan satu halaman HTML (secara tepat - markup-HTML, tanpa file terhubung eksternal jika ada) yang dibuat selama konversi.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Penangkap ini dapat digunakan untuk menangani peristiwa kemajuan konversi, misalnya.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Bidang ini dapat berisi strategi penyimpanan yang harus digunakan (jika ada) selama konversi untuk penanganan khusus file sumber daya yang direferensikan (seperti gambar dan font) yang terkait dengan node HTML yang disimpan.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Bidang ini dapat berisi metode khusus yang mengembalikan URL (atau templat URL jika generasi multi‑halaman diaktifkan – lihat detail di bawah) dari CSS yang bersangkutan sebagaimana harus dimasukkan ke dalam HTML hasil yang dihasilkan.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Menentukan nama font yang terpasang yang digunakan untuk menggantikan font dokumen apa pun yang tidak tertanam dan tidak terpasang di sistem. Jika null maka font pengganti default akan digunakan.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Mengatur {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Daftar nama font PDF yang disematkan yang tidak akan disematkan dalam HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Dengan properti ini Anda dapat secara eksplisit menentukan halaman dokumen mana yang harus dikonversi. Halaman dalam daftar ini harus memiliki nomor berbasis 1. Misalnya, nomor halaman yang valid harus diambil dari rentang (1...[NumberOfPagesInConvertedDocument]). Urutan munculnya halaman dalam daftar ini tidak memengaruhi urutan mereka dalam halaman HTML hasil - dalam halaman hasil selalu akan ditampilkan dalam urutan yang ada di PDF sumber. Jika daftar ini null (seperti default), semua halaman akan dikonversi. Jika nomor halaman mana pun dalam daftar ini berada di luar rentang halaman yang ada (1-[amountOfPagesInDocument]) akan dilemparkan pengecualian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Mengatur nilai yang menunjukkan apakah HTML tersebut dibuat sebagai tata letak tetap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | : {@code true} jika [fixed layout]; sebaliknya, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Atribut ini menentukan teks paragraf lebar penuh untuk mode Aliran, FixedLayout = false

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Mendefinisikan aturan khusus pengkodean untuk menyesuaikan dekode PDF untuk dokumen saat ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontEncodingStrategy |  | elemen FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Mendefinisikan mode penyimpanan font yang akan digunakan saat menyimpan PDF ke format yang diinginkan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontSavingMode |  | elemen FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Kadang-kadang persyaratan khusus untuk pembuatan markup HTML muncul. Parameter ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | elemen HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Mendapatkan atau mengatur resolusi untuk rendering gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai: Resolusi |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Mengatur mode penempatan huruf dalam kata pada HTML hasil

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Atribut ini mengatur lebar minimal garis jalur grafis. Jika ketebalan garis kurang dari 1px, Adobe Acrobat membulatkannya ke nilai ini. Jadi atribut ini dapat digunakan untuk meniru perilaku tersebut pada peramban HTML.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Atribut ini mewakili kumpulan pengaturan yang digunakan untuk menggambar batas (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Atribut ini mewakili kumpulan margin halaman tambahan (jika ada) dalam dokumen HTML hasil di sekitar area yang mewakili halaman PDF sumber.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Jika atribut 'SplitOnPages=false', maka seluruh HTML yang mewakili semua halaman PDF masukan akan dimasukkan ke dalam satu file HTML hasil yang besar. Bendera ini menentukan apakah HTML hasil akan dihasilkan dengan cara sehingga aliran area yang mewakili halaman PDF dalam HTML hasil akan bergantung pada resolusi layar penampil. Misalkan lebar layar pada sisi penampil cukup besar untuk menempatkan 2 atau lebih halaman berdampingan secara horizontal. Jika bendera ini diatur ke true, maka kesempatan ini akan digunakan (sejumlah halaman akan ditampilkan secara horizontal berdampingan sebanyak mungkin, kemudian grup horizontal berikutnya akan ditampilkan di bawah yang pertama). Sebaliknya, halaman akan mengalir dengan cara: halaman berikutnya selalu berada di bawah halaman sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | nilai boolean |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Ini mendefinisikan apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| partsEmbeddingMode |  | Elemen PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Atribut ini mengaktifkan mode di mana glif teks tidak akan dikelompokkan menjadi kata dan string. Mode ini memungkinkan mempertahankan presisi maksimum selama penempatan glif pada halaman dan dapat digunakan untuk konversi dokumen dengan notasi musik atau glif yang harus ditempatkan secara terpisah satu sama lain. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

PDF yang dikonversi dapat berisi gambar raster. Parameter ini mendefinisikan bagaimana mereka harus diproses selama konversi PDF ke HTML

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasterImagesSavingMode |  | Elemen RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Menentukan apakah pada HTML yang dibuat area kosong di bagian atas dan bawah tanpa konten apa pun (jika ada) akan dihapus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | nilai boolean |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Jika atribut RenderTextAsImage diatur ke true, teks dari sumber menjadi gambar dalam HTML. Mungkin berguna untuk membuat teks tidak dapat dipilih atau teks HTML tidak dirender dengan benar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Menunjukkan bahwa font lengkap akan disimpan, hanya mendukung True Type Fonts. Secara default SaveFullFont = false dan konverter menyimpan subset dari font awal yang diperlukan untuk menampilkan teks dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Pdf dapat berisi teks yang dibayangi oleh elemen lain (misalnya oleh gambar) tetapi dapat dipilih ke clipboard di Acrobat Reader (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil untuk meniru perilaku Acrobat Reader (sebaliknya teks semacam itu biasanya disimpan sebagai tersembunyi, tidak tersedia untuk disalin ke clipboard).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | nilai boolean |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf dapat berisi teks transparan yang dapat dipilih ke clipboard (biasanya terjadi ketika dokumen berisi gambar dan teks yang di-OCR yang diekstrak darinya). Pengaturan ini memberi tahu konverter apakah kita perlu menyimpan teks tersebut sebagai teks transparan yang dapat dipilih dalam HTML hasil.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| saveTransparentTexts |  | nilai boolean |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Atribut ini menentukan pengelompokan berurutan dari glif dan kata menjadi string. Misalnya tag dan kata memiliki urutan yang berbeda dalam HTML yang dikonversi dan Anda ingin mereka cocok. Parameter ini akan diterapkan pada dokumen hanya ketika nilai atribut FixedLayout adalah true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Mendapatkan atau mengatur jalur ke direktori tempat semua gambar yang ditemui selama penyimpanan dokumen sebagai HTML harus disimpan. Jika parameter kosong atau null, maka file gambar (jika ada) akan disimpan bersama file lain yang terhubung ke HTML. Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Mendapatkan atau mengatur jalur ke direktori tempat hanya gambar SVG yang harus disimpan jika ditemukan selama penyimpanan dokumen sebagai HTML. Jika parameter kosong atau null, maka file SVG (jika ada) akan disimpan bersama file gambar lainnya (dekat file output) atau dalam folder khusus untuk gambar (jika ditentukan dalam opsi SpecialImagesFolderIfAny). Ini tidak memengaruhi apa pun jika properti CustomImageSavingStrategy berhasil digunakan untuk memproses file gambar yang relevan.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Ketika mode multipage dipilih (misalnya 'SplitIntoPages' adalah 'true'), maka atribut ini menentukan apakah harus dibuat file CSS terpisah untuk setiap halaman HTML hasil. Secara default atribut ini false, sehingga akan dibuat satu CSS besar bersama untuk semua halaman yang dibuat. Ukuran total semua CSS yang dihasilkan dalam mode ini (satu CSS per halaman) biasanya jauh lebih besar daripada ukuran satu file CSS besar, karena dalam kasus pertama kelas CSS duplikat di beberapa file CSS untuk setiap halaman. Jadi, pengaturan ini sebaiknya hanya digunakan ketika Anda tertarik pada pemrosesan masing-masing halaman HTML secara terpisah di masa depan, dan oleh karena itu ukuran CSS setiap halaman yang dipisahkan menjadi isu paling kritis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Mengatur flag yang menunjukkan apakah setiap halaman dokumen sumber akan dikonversi menjadi dokumen HTML targetnya masing‑masing, yaitu apakah HTML hasil akan dibagi menjadi beberapa halaman HTML.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTitle {#setTitle-java.lang.String-}
Mendapatkan atau mengatur judul halaman HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF sendiri tidak berisi penanda garis bawah untuk teks. Itu disimulasikan dengan garis yang terletak di bawah teks. Opsi ini memungkinkan konverter mencoba menebak bahwa garis ini atau itu adalah garis bawah teks dan menempatkan informasi ini ke dalam CSS alih-alih menggambar garis bawah secara grafis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | nilai boolean |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Jika atribut UseZORder diatur ke true, grafik dan teks ditambahkan ke dokumen HTML hasil sesuai urutan Z dalam dokumen PDF asli. Jika atribut ini false, semua grafik ditempatkan sebagai satu lapisan yang dapat menyebabkan efek tidak perlu pada objek yang tumpang tindih.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
