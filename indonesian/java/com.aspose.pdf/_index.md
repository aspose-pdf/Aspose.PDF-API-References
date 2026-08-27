---
title: "com.aspose.pdf"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "com.aspose.pdf adalah paket root untuk semua kelas dalam pustaka Aspose.PDF untuk Java yang berada baik secara langsung di dalamnya seperti Document maupun secara tidak langsung melalui beberapa subpaket."
type: docs
weight: 10
url: /id/java/com.aspose.pdf/
---
com.aspose.pdf adalah paket root untuk semua kelas dalam pustaka Aspose.PDF untuk Java yang berada baik secara langsung di dalamnya seperti Document maupun secara tidak langsung melalui beberapa subpaket.

## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [Document.CallBackGetHocr](./document.callbackgethocr/) | Prosedur panggilan balik untuk pengenalan hocr. |
| [Document.CallBackGetHocrBase](./document.callbackgethocrbase/) | Prosedur panggilan balik untuk pengenalan hocr. |
| [Document.CallBackGetHocrWithPage](./document.callbackgethocrwithpage/) | Prosedur panggilan balik untuk pengenalan hocr. |
| [Document.IDocumentFontUtilities](./document.idocumentfontutilities/) | Menyimpan fungsionalitas untuk menyesuaikan font |
| [IAnnotationVisitor](./iannotationvisitor/) | Mendefinisikan Visitor untuk mengunjungi anotasi dokumen yang berbeda. |
| [IAppointment](./iappointment/) | Mewakili antarmuka umum untuk tindakan dan tujuan. |
| [IColorSpaceConversionStrategy](./icolorspaceconversionstrategy/) | Antarmuka untuk strategi konversi ruang warna. |
| [IDocument](./idocument/) | antarmuka yang mewakili dokumen PDF |
| [IFontOptions](./ifontoptions/) | Properti berguna untuk menyesuaikan perilaku Font |
| [IIndexBitmapConverter](./iindexbitmapconverter/) | Antarmuka ini dideklarasikan untuk algoritma kustomisasi kuantisasi. Pengguna dapat mengimplementasikan realisasi mereka sendiri dari algoritma ini (misalnya algoritma berbasis kode tidak terkelola). |
| [IIndexBitmapConverterInternal](./iindexbitmapconverterinternal/) | Antarmuka ini dideklarasikan untuk algoritma kustomisasi kuantisasi. Pengguna dapat mengimplementasikan realisasi mereka sendiri dari algoritma ini (misalnya algoritma berbasis kode tidak terkelola). |
| [ILicenseProvider](./ilicenseprovider/) |  |
| [IOperatorSelector](./ioperatorselector/) | Mendefinisikan Visitor untuk mengunjungi operator pdf yang berbeda. |
| [IPageSetOptions](./ipagesetoptions/) | Mendefinisikan opsi konversi terkait dengan sekumpulan halaman yang akan dikonversi. |
| [IPipelineOptions](./ipipelineoptions/) | Mendefinisikan opsi konversi terkait dengan konfigurasi pipeline. |
| [ITableElement](./itableelement/) | Antarmuka ini mewakili elemen tabel yang ada yang diekstrak oleh TableAbsorber. |
| [LoadOptions.ResourceLoadingStrategy](./loadoptions.resourceloadingstrategy/) | Kadang-kadang diperlukan untuk menghindari penggunaan pemuat internal sumber daya eksternal (seperti gambar atau CSS) dan menyediakan metode khusus, yang akan mengambil sumber daya yang diminta dari suatu tempat. Misalnya selama penggunaan Aspose.PDf di cloud akses langsung ke file yang direferensikan tidak memungkinkan, dan beberapa kode khusus yang dimasukkan ke dalam metode khusus harus digunakan. Delegasi ini mendefinisikan tanda tangan dari metode khusus tersebut. |
| [MemoryExtender.CallBackPageImage](./memoryextender.callbackpageimage/) | / * Atur flag apakah folder sementara akan digunakan untuk menampung data font sementara. / * True secara default. / * Menggunakan memori heap jika nilai = false; / * |
| [SvgSaveOptions.EmbeddedImagesSavingStrategy](./svgsaveoptions.embeddedimagessavingstrategy/) | Untuk properti tipe tersebut Anda dapat menetapkan delegasi yang dibuat dari metode khusus yang mengimplementasikan pemrosesan penyimpanan eksternal gambar yang diekstrak dari SVG yang dibuat dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus ini pemrosesan (seperti penyimpanan buatan sendiri ke aliran atau ke disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus itu harus mengembalikan jalur (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam SVG yang dihasilkan menggantikan jalur asli yang seharusnya menuju sumber daya gambar tersebut. Dalam kasus ini semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan set dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'imageSavingInfo'. Ini memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun. |
## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [AbsorbedCell](./absorbedcell/) | Mewakili sel tabel yang ada di halaman. |
| [AbsorbedRow](./absorbedrow/) | Mewakili baris tabel yang ada di halaman. |
| [AbsorbedTable](./absorbedtable/) | Mewakili tabel yang ada di halaman. |
| [ActionCollection](./actioncollection/) | Koleksi aksi. |
| [Annotation](./annotation/) | Kelas yang mewakili objek anotasi. |
| [AnnotationActionCollection](./annotationactioncollection/) | Mewakili koleksi aksi anotasi. |
| [AnnotationCollection](./annotationcollection/) | Kelas yang mewakili koleksi anotasi. |
| [AnnotationFlags](./annotationflags/) | Flags Sekumpulan flag biner yang menentukan berbagai karakteristik anotasi. |
| [AnnotationSelector](./annotationselector/) | Kelas ini digunakan untuk memilih anotasi menggunakan ide template Visitor. |
| [AnnotationTextRenderer](./annotationtextrenderer/) | Kelas untuk merender teks normal dan kaya. |
| [AppearanceDictionary](./appearancedictionary/) | Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman. |
| [ApsLoadOptions](./apsloadoptions/) | Kelas yang menjelaskan opsi pemuatan APS. Opsi untuk impor dari format XML APS. |
| [ApsSaveOptions](./apssaveoptions/) | Opsi penyimpanan untuk ekspor ke format XML APS. |
| [ApsToFlowConverter](./apstoflowconverter/) | Konversi APS ke Flow. |
| [Artifact](./artifact/) | Kelas yang mewakili objek PDF Artifact. |
| [ArtifactCollection](./artifactcollection/) | Kelas yang mewakili koleksi artefak. |
| [AutoTaggingSettings](./autotaggingsettings/) | Menyediakan pengaturan untuk fungsi auto-tagging dalam dokumen PDF. Kelas {@link AutoTaggingSettings} memungkinkan konfigurasi opsi untuk penandaan otomatis konten PDF. Ini mencakup properti untuk mengaktifkan atau menonaktifkan auto-tagging, menentukan strategi untuk pengenalan heading, dan mendefinisikan tingkat heading berdasarkan ukuran font. |
| [BackgroundArtifact](./backgroundartifact/) | Kelas yang menjelaskan artefak latar belakang. Artefak ini memungkinkan pengaturan latar belakang halaman. |
| [BarcodeField](./barcodefield/) | Kelas yang mewakili bidang barcode. |
| [BaseActionCollection](./baseactioncollection/) | Kelas yang mengenkapsulasi aksi dasar dengan aksi interaktif halaman/anotasi/bidang. |
| [BaseOperatorCollection](./baseoperatorcollection/) | Mewakili kelas dasar untuk koleksi operator. |
| [BaseParagraph](./baseparagraph/) | Mewakili objek dasar abstrak yang dapat ditambahkan ke halaman (doc.Paragraphs.Add()). |
| [BatesNArtifact](./batesnartifact/) | Kelas menjelaskan artefak Penomoran Bates. |
| [BitmapInfo](./bitmapinfo/) | Objek yang berisi array piksel dan informasi bitmap. |
| [BitmapInfo.PixelFormat](./bitmapinfo.pixelformat/) | Format piksel bitmap. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Mewakili anotasi Tanda Bleed. Tanda bleed ditempatkan di sudut-sudut halaman cetak untuk menunjukkan di mana halaman akan dipotong dan sejauh mana boleh menyimpang dari tanda potong. |
| [Border](./border/) | Kelas yang mewakili karakteristik batas anotasi. |
| [BorderInfo](./borderinfo/) | Kelas ini mewakili batas untuk elemen grafis. |
| [BorderSide](./borderside/) | Flag mengenumerasi sisi-sisi batas secara biner. |
| [BorderStyleConverter](./borderstyleconverter/) | Mewakili kelas BorderStyleConverter |
| [Brush](./brush/) | Kelas ini mewakili kuas abstrak |
| [BuildVersionInfo](./buildversioninfo/) | Kelas ini menyediakan informasi tentang build produk saat ini. |
| [ButtonField](./buttonfield/) | Kelas mewakili bidang tombol dorong. |
| [CaretAnnotation](./caretannotation/) | Kelas yang mewakili anotasi Caret. |
| [CaretSymbolConverter](./caretsymbolconverter/) | Mewakili kelas CaretSymbolConverter |
| [CdrLoadOptions](./cdrloadoptions/) | Kelas menjelaskan opsi pemuatan CDR. |
| [Cell](./cell/) | Mewakili sel dari baris tabel. |
| [Cells](./cells/) | Mewakili koleksi sel dari baris. |
| [CgmImportOptions](./cgmimportoptions/) | Opsi impor untuk mengimpor dari format Computer Graphics Metafile (CGM). |
| [CgmLoadOptions](./cgmloadoptions/) | Berisi opsi untuk memuat/mengimpor file CGM ke dalam dokumen PDF. |
| [Characteristics](./characteristics/) | Mewakili karakteristik anotasi |
| [CharInfo](./charinfo/) | Mewakili objek info karakter. Menyediakan informasi penempatan karakter. |
| [CharInfoCollection](./charinfocollection/) | <p> Mewakili koleksi objek CharInfo. </p> <hr> <pre> The example demonstrates how to iterate thought all the characters and retrieve the character //open document Document pdfDocument = new Document(inFile); //create TextFragmentAbsorber object to collect all the text objects of the page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accept the absorber for all the pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //get the extracted text fragments TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //loop through the fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //loop through the segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //loop through the characters {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); // print character position and rectangle info System.out.println(\"XIndent : \" + charInfo.getPosition().getXIndent()); System.out.println(\"YIndent : \" + charInfo.getPosition().getYIndent()); System.out.println(\"Width : \" + charInfo.getRectangle().getWidth()); System.out.println(\"Height : \" + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Menyediakan akses ke informasi penempatan karakter segmen teks. </p> |
| [CheckboxField](./checkboxfield/) | Kelas yang mewakili bidang kotak centang |
| [ChoiceField](./choicefield/) | Mewakili kelas dasar untuk bidang pilihan. |
| [CircleAnnotation](./circleannotation/) | Kelas yang mewakili anotasi Lingkaran. |
| [Collection](./collection/) | Mewakili kelas untuk Collection(12.3.5 Collections). |
| [CollectionField](./collectionfield/) | Mewakili kelas bidang skema koleksi dokumen. |
| [CollectionFieldSubtype](./collectionfieldsubtype/) | Mewakili parameter subtipe dari sebuah bidang dalam koleksi skema. |
| [CollectionItem](./collectionitem/) | Mewakili kelas item koleksi. Item koleksi berisi data yang dijelaskan oleh skema koleksi. |
| [CollectionItem.Value<T>](./collectionitem.value-t/) | Mewakili kelas untuk nilai item koleksi. |
| [CollectionSchema](./collectionschema/) | Mewakili kelas yang mendeskripsikan "Skema" dari koleksi dokumen. |
| [Color](./color/) | Mewakili kelas untuk nilai warna yang dapat diekspresikan dalam ruang warna yang berbeda. |
| [ColorBarAnnotation](./colorbarannotation/) | Kelas yang merepresentasikan anotasi ColorBarAnnotation. Properti Color diabaikan, sebagai gantinya digunakan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa apakah persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam kasus ini, anotasi tetap ada di halaman, tetapi tidak ditampilkan). |
| [ColumnInfo](./columninfo/) | Kelas ini merepresentasikan info kolom. |
| [com.aspose.ms.System.MulticastDelegate>](./com.aspose.ms.system.multicastdelegate/) | Kelas yang merepresentasikan peristiwa |
| [ComboBoxField](./comboboxfield/) | Kelas yang merepresentasikan bidang Combobox dari formulir. |
| [ComHelper](./comhelper/) | <p> Menyediakan metode untuk klien COM untuk memuat dokumen ke dalam Aspose.PDF. </p> <hr> <p> Gunakan kelas ComHelper untuk memuat dokumen dari file atau aliran ke dalam objek Document dalam aplikasi COM. Kelas Document menyediakan konstruktor default untuk membuat dokumen baru dan juga menyediakan konstruktor overload untuk memuat dokumen dari file atau aliran. Jika Anda menggunakan Aspose.Words dari aplikasi .NET, Anda dapat menggunakan semua konstruktor Document secara langsung, tetapi jika Anda menggunakan Aspose.PDF dari aplikasi COM, hanya konstruktor Document default yang tersedia. </p> |
| [CommonFigureAnnotation](./commonfigureannotation/) | Kelas abstrak yang merepresentasikan anotasi gambar umum. |
| [CompositingParameters](./compositingparameters/) | Mewakili objek yang berisi parameter komposit grafis dari keadaan grafis saat ini. |
| [ContentsAppender](./contentsappender/) | Melakukan modifikasi konten hanya dalam mode APPEND. mode ini memungkinkan menghindari parsing konten yang tidak diperlukan dan berat sebelum perubahan dilakukan pada konten. Ini hanya menambahkan operator baru ke akhir atau ke awal konten. |
| [Copier](./copier/) | Kelas untuk menyalin objek. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Mewakili tipe anotasi yang ditempatkan di sudut-sudut halaman tercetak. |
| [CustomExplicitDestination](./customexplicitdestination/) | Mewakili tujuan eksplisit khusus. |
| [CustomSign](./customsign/) | Delegasi untuk menandatangani dokumen secara khusus (Beta). |
| [Dash](./dash/) | Kelas yang merepresentasikan pola dash garis. |
| [DateField](./datefield/) | Bidang tanggal dengan tampilan kalender. DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField |
| [DefaultAppearance](./defaultappearance/) | Mendeskripsikan tampilan default bidang (font, ukuran teks, dan warna). |
| [DefaultDirectory](./defaultdirectory/) | Menentukan jalur default untuk tujuan tertentu |
| [DestinationCollection](./destinationcollection/) | Kelas yang merepresentasikan koleksi semua tujuan (pohon nama yang memetakan string nama ke tujuan (lihat 12.3.2.3, "Named Destinations") dan (lihat 7.7.4, "Name Dictionary")) dalam dokumen pdf. |
| [DestinationFactory](./destinationfactory/) | Mewakili kelas DestinationFactory |
| [DjvuLoadOptions](./djvuloadoptions/) | Kelas yang mendeskripsikan opsi pemuatan DJVU. |
| [DocMDPSignature](./docmdpsignature/) | Mewakili kelas tipe tanda tangan dokumen MDP (modification detection and prevention). |
| [DocSaveOptions](./docsaveoptions/) | Opsi penyimpanan untuk ekspor ke format Doc |
| [Document](./document/) | Kelas yang mewakili dokumen PDF. |
| [Document.OptimizationOptions](./document.optimizationoptions/) | Kelas yang menjelaskan algoritma optimisasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources(). @deprecated Kelas ini sudah usang. Silakan gunakan com.aspose.pdf.optimization.OptimizationOptions sebagai gantinya. |
| [Document.RepairOptions](./document.repairoptions/) | Mewakili opsi untuk memperbaiki dokumen PDF. Kelas ini menyediakan cara untuk menyesuaikan proses perbaikan dokumen PDF. |
| [DocumentActionCollection](./documentactioncollection/) | Kelas yang menjelaskan tindakan yang dilakukan pada beberapa aksi dengan dokumen |
| [DocumentExtensions](./documentextensions/) | Menyediakan kemampuan tambahan untuk kelas Document. |
| [DocumentFactory](./documentfactory/) | Kelas yang memungkinkan pembuatan/memuat dokumen dari berbagai tipe. |
| [DocumentInfo](./documentinfo/) | Mewakili metadata dokumen PDF. |
| [DocumentWeb](./documentweb/) | Mewakili kelas DocumentWeb |
| [Element](./element/) | Kelas yang mewakili elemen dasar struktur logis. |
| [ElementCollection](./elementcollection/) | Koleksi elemen dasar struktur logis. |
| [EmbeddedFileCollection](./embeddedfilecollection/) | Kelas yang mewakili koleksi file tersemat. |
| [EncryptedPayload](./encryptedpayload/) | Mewakili payload terenkripsi dalam spesifikasi file. |
| [EpubLoadOptions](./epubloadoptions/) | Berisi opsi untuk memuat/mengimpor file EPUB ke dalam dokumen PDF. |
| [EpubSaveOptions](./epubsaveoptions/) | Opsi penyimpanan untuk ekspor ke format EPUB |
| [ExcelSaveOptions](./excelsaveoptions/) | Opsi penyimpanan untuk ekspor ke format Excel |
| [ExplicitDestination](./explicitdestination/) | Mewakili kelas dasar untuk tujuan eksplisit dalam dokumen PDF. |
| [ExplicitDestinationTypeConverter](./explicitdestinationtypeconverter/) | Mewakili kelas ExplicitDestinationTypeConverter |
| [ExportFieldsOptions](./exportfieldsoptions/) | Mewakili kelas dasar opsi untuk mengekspor bidang formulir. |
| [ExportFieldsToJsonOptions](./exportfieldstojsonoptions/) | Mewakili opsi untuk mengekspor bidang formulir ke format Json. Mewarisi dari {@link ExportFieldsOptions} dan menambahkan opsi khusus untuk ekspor Json. |
| [ExportImportMessages](./exportimportmessages/) | Berisi berbagai pesan kesalahan untuk operasi ekspor dan impor bidang formulir. |
| [ExternalSignature](./externalsignature/) | Membuat tanda tangan PKCS#7Detached yang terpisah menggunakan X509Certificate2. Mendukung smartcard USB, token tanpa kunci pribadi yang dapat diekspor. |
| [FdfReader](./fdfreader/) | Kelas yang melakukan pembacaan format FDF. Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\"); |
| [Field](./field/) | Kelas dasar untuk bidang formulir acro. |
| [FieldSerializationResult](./fieldserializationresult/) | Mewakili hasil proses serialisasi bidang formulir. |
| [FieldSerializationStatus](./fieldserializationstatus/) | Mewakili status serialisasi bidang formulir. |
| [FieldValueType](./fieldvaluetype/) | Mewakili tipe nilai bidang dalam koleksi skema. |
| [FigureElement](./figureelement/) | Kelas yang mewakili gambar struktur logis. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Kelas yang menjelaskan anotasi lampiran file. |
| [FileFontSource](./filefontsource/) | Mewakili sumber file font tunggal. |
| [FileHyperlink](./filehyperlink/) | Mewakili objek hyperlink file. |
| [FileIconConverter](./fileiconconverter/) | Mewakili kelas FileIconConverter |
| [FileParams](./fileparams/) | Mendefinisikan kamus parameter file tersemat yang harus berisi informasi tambahan khusus file. |
| [FileSelectBoxField](./fileselectboxfield/) | Bidang untuk elemen kotak pilih file. |
| [FileSpecification](./filespecification/) | Kelas yang mewakili file tersemat. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan kotak pembatasnya sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan kotak pembatas dalam jendela pada dimensi lainnya. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar seluruh kotak pembatasnya dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi seluruh kotak pembatasnya dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan. |
| [FitExplicitDestination](./fitexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan seluruh halaman dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan halaman dalam jendela pada dimensi lainnya. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar seluruh halaman dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan persegi panjang yang ditentukan oleh koordinat left, bottom, right, dan top sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan persegi panjang dalam jendela pada dimensi lainnya. Nilai null untuk salah satu parameter dapat mengakibatkan perilaku yang tidak dapat diprediksi. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi seluruh halaman dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan. |
| [FixedPrint](./fixedprint/) | Mewakili data cetak tetap dari Anotasi Watermark. |
| [FloatingBox](./floatingbox/) | Mewakili FloatingBox dalam dokumen PDF. FloatingBox diposisikan secara khusus. |
| [FlowConverter](./flowconverter/) | Mengonversi Dokumen PDF ke format Flow (XLSX, ODS, XMLSpreedSheet2003, CSV) DOCX dalam mode EnchanedFlow, TableAbsorber dalam mode FlowEngine. |
| [FlowToTableAbsorber](./flowtotableabsorber/) | Menyampaikan data dari pustaka Flow ke TableAbsorber |
| [FolderFontSource](./folderfontsource/) | Mewakili folder yang berisi file font. |
| [Font](./font/) | <p> Mewakili objek font. </p> <hr> <pre> Contoh ini menunjukkan cara mencari teks pada halaman pertama dan mengubah font pada kemunculan pencarian pertama. // Buka dokumen Document doc = new Document(\"input.pdf\"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Buat font dan tandai agar disematkan Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Ubah font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Simpan dokumen doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument |
| [FontAbsorber](./fontabsorber/) | Mewakili objek absorber font. Melakukan pencarian font dan menyediakan akses ke hasil pencarian melalui koleksi {@code FontAbsorber.Fonts}. |
| [FontCollection](./fontcollection/) | <p> Mewakili koleksi font. </p> <hr> <pre> Contoh ini menunjukkan cara menjadikan semua font yang dideklarasikan pada halaman sebagai disematkan. // Buka dokumen Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // pastikan semua font yang dideklarasikan pada sumber daya halaman disematkan // catatan bahwa jika font dideklarasikan pada sumber daya formulir, mereka tidak dapat diakses dari sumber daya halaman for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); </pre> <hr> <p> Koleksi font yang diwakili oleh kelas {@code FontCollection} digunakan dalam beberapa skenario. Misalnya, dalam sumber daya dengan properti {@code Resources.Fonts}. </p> |
| [FontEmbeddingOptions](./fontembeddingoptions/) | Standar PDF/A mengharuskan semua font harus disematkan ke dalam dokumen. Kelas ini mencakup flags untuk kasus ketika tidak memungkinkan menyematkan beberapa font karena font tersebut tidak ada pada PC tujuan. |
| [FontRepository](./fontrepository/) | <p> Melakukan pencarian font. Mencari dalam font yang terpasang di sistem dan font PDF standar. Juga menyediakan fungsionalitas untuk membuka font khusus. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan font dan mengganti font teks pada halaman pertama. // Temukan font Font font = FontRepository.findFont(\"Arial\"); // Buka dokumen Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks \"hello world\" TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(absorber); // Ganti font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Simpan dokumen doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> @see TextFragmentAbsorber @see IDocument |
| [FontSource](./fontsource/) | Mewakili kelas dasar untuk sumber font. |
| [FontStyles](./fontstyles/) | Binary Flag <p> Menentukan informasi gaya yang diterapkan pada teks. </p> <hr> <p> Enumerasi ini memiliki atribut {@code FlagsAttribute} yang memungkinkan kombinasi nilai anggotanya. </p> |
| [FontSubsetStrategy](./fontsubsetstrategy/) | Binary Flag mengenumerasikan strategi untuk subsetting font |
| [FooterArtifact](./footerartifact/) | Menjelaskan artefak footer. Ini dapat digunakan untuk mengatur footer halaman. |
| [Form](./form/) | Kelas yang mewakili objek formulir. |
| [Form.FlattenSettings](./form.flattensettings/) | Kelas yang menjelaskan pengaturan untuk prosedur pelurusan Form. |
| [Form.SignDependentElementsRenderingModes](./form.signdependentelementsrenderingmodes/) | Formulir dapat berisi informasi penandatanganan dan dapat ditandatangani atau tidak. Terkadang tampilan formulir di penampil harus bergantung pada apakah formulir ditandatangani atau tidak. Enum ini mengenumerasikan mode render yang mungkin selama konversi tipe formulir terkait tanda tangan. |
| [FormattedFragment](./formattedfragment/) | Mewakili fragmen terformat abstrak. |
| [FreeTextAnnotation](./freetextannotation/) | Mewakili anotasi teks bebas yang menampilkan teks langsung pada halaman. Tidak seperti anotasi teks biasa, anotasi teks bebas tidak memiliki keadaan terbuka atau tertutup; alih-alih ditampilkan dalam jendela pop-up, teks selalu terlihat. |
| [GoToAction](./gotoaction/) | Mewakili aksi go-to yang mengubah tampilan ke tujuan yang ditentukan (halaman, lokasi, dan faktor pembesaran). |
| [GoToRemoteAction](./gotoremoteaction/) | Mewakili aksi go-to remote yang mirip dengan aksi go-to biasa tetapi melompat ke tujuan dalam file PDF lain alih-alih file saat ini. |
| [GoToURIAction](./gotouriaction/) | Mewakili aksi URI yang menyebabkan URI diresolusikan. |
| [GraphInfo](./graphinfo/) | Mewakili informasi grafis. |
| [Group](./group/) | Kelas atribut grup yang menentukan atribut grup halaman halaman untuk digunakan dalam model pencitraan transparan. |
| [Hackers](./hackers/) |  |
| [HeaderArtifact](./headerartifact/) | Kelas menjelaskan artefak Heaader. Artefak ini dapat digunakan untuk mengatur judul halaman. |
| [HeaderFooter](./headerfooter/) | Kelas mewakili header atau footer halaman PDF. |
| [Heading](./heading/) | Mewakili judul. |
| [HideAction](./hideaction/) | Mewakili aksi sembunyi yang menyembunyikan atau menampilkan satu atau lebih anotasi di layar dengan mengatur atau menghapus flag Hidden mereka. |
| [HighlightAnnotation](./highlightannotation/) | Mewakili anotasi sorotan yang menyorot rentang teks dalam dokumen. |
| [HtmlFragment](./htmlfragment/) | Mewakili fragmen HTML. |
| [HtmlLoadOptions](./htmlloadoptions/) | Mewakili opsi untuk memuat/mengimpor file HTML ke dalam dokumen PDF. |
| [HtmlPageLayoutOption](./htmlpagelayoutoption/) | Bendera Biner Menentukan bendera yang bersama dengan opsi lain menentukan ukuran dan tata letak halaman. |
| [HtmlSaveOptions](./htmlsaveoptions/) | Opsi penyimpanan untuk ekspor ke format HTML |
| [HtmlSaveOptions.AntialiasingProcessingType](./htmlsaveoptions.antialiasingprocessingtype/) | Enum ini menjelaskan langkah antialiasing yang mungkin selama konversi |
| [HtmlSaveOptions.CssSavingInfo](./htmlsaveoptions.csssavinginfo/) | Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan CSS khusus selama konversi PDF ke format HTML |
| [HtmlSaveOptions.CssSavingStrategy](./htmlsaveoptions.csssavingstrategy/) | Anda dapat menetapkan strategi khusus ke properti ini yang mengimplementasikan pemrosesan dan/atau penyimpanan bagian CSS yang dibuat selama konversi PDF ke HTML. Dalam kasus tersebut, pemrosesan (seperti penyimpanan ke aliran atau disk) harus dilakukan dalam kode khusus tersebut |
| [HtmlSaveOptions.CssUrlMakingStrategy](./htmlsaveoptions.cssurlmakingstrategy/) | Anda dapat menetapkan delegasi yang dibuat dari metode khusus ke properti ini yang mengimplementasikan pembuatan URL CSS yang direferensikan dalam dokumen HTML yang dihasilkan. Misalnya, jika Anda ingin membuat CSS direferensikan dalam HTML sebagai \"otherPage.ASPX?CssID=zjjkklj\", maka strategi khusus tersebut harus mengembalikan \"otherPage.ASPX?CssID=zjjkklj\" |
| [HtmlSaveOptions.CssUrlRequestInfo](./htmlsaveoptions.cssurlrequestinfo/) | Mewakili sekumpulan data yang terkait dengan permintaan dari konverter ke kode khusus yang bertujuan mendapatkan URL (atau templat URL) yang diinginkan untuk CSS yang bersangkutan |
| [HtmlSaveOptions.FontEncodingRules](./htmlsaveoptions.fontencodingrules/) | Enumerasi ini mendefinisikan aturan yang menyesuaikan logika enkoding |
| [HtmlSaveOptions.FontSavingModes](./htmlsaveoptions.fontsavingmodes/) | Mengenumerasikan mode yang dapat digunakan untuk menyimpan font yang direferensikan dalam PDF yang disimpan. |
| [HtmlSaveOptions.HtmlImageSavingInfo](./htmlsaveoptions.htmlimagesavinginfo/) | Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML. |
| [HtmlSaveOptions.HtmlImageType](./htmlsaveoptions.htmlimagetype/) | Mengenumerasikan tipe file gambar yang dapat disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML |
| [HtmlSaveOptions.HtmlMarkupGenerationModes](./htmlsaveoptions.htmlmarkupgenerationmodes/) | Terkadang ada persyaratan khusus untuk HTML yang dibuat. Enum ini mendefinisikan mode persiapan HTML yang dapat digunakan selama konversi PDF ke HTML untuk memenuhi persyaratan khusus tersebut. |
| [HtmlSaveOptions.HtmlPageMarkupSavingInfo](./htmlsaveoptions.htmlpagemarkupsavinginfo/) | Jika properti SplitToPages dari HtmlSaveOptions diaktifkan, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML |
| [HtmlSaveOptions.HtmlPageMarkupSavingStrategy](./htmlsaveoptions.htmlpagemarkupsavingstrategy/) | Hasil konversi dapat berisi satu atau beberapa halaman HTML (yang juga dapat merujuk ke file eksternal seperti gambar atau font). Anda dapat menetapkan delegasi yang dibuat dari metode khusus ke properti ini yang mengimplementasikan pemrosesan halaman HTML yang dihasilkan (HTML itu sendiri) yang dibuat selama konversi. Dalam kasus tersebut, pemrosesan (seperti penyimpanan ke aliran atau disk) dapat dilakukan dalam kode khusus tersebut. Semua tindakan yang diperlukan untuk menyimpan markup halaman HTML harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk kasus ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan atur flag 'CustomProcessingCancelled' pada variabel parameter 'htmlSavingInfo' dalam kode khusus: itu memberi sinyal kepada konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seperti seolah-olah tidak ada kode penyimpanan khusus eksternal. |
| [HtmlSaveOptions.ImageParentTypes](./htmlsaveoptions.imageparenttypes/) | Mengenumerasikan tipe kemungkinan induk gambar; gambar dapat terkait ke halaman HTML atau ke gambar induk SVG |
| [HtmlSaveOptions.PartsEmbeddingModes](./htmlsaveoptions.partsembeddingmodes/) | Enum ini mengenumerasikan mode kemungkinan penyematan file yang direferensikan dalam HTML. Ini memungkinkan kontrol apakah file yang direferensikan (HTML, Font, Gambar, CSS) akan disematkan ke dalam file HTML utama atau akan dihasilkan sebagai entitas biner terpisah |
| [HtmlSaveOptions.RasterImagesSavingModes](./htmlsaveoptions.rasterimagessavingmodes/) | PDF yang dikonversi dapat berisi gambar raster (.png, *.jpeg, dll.). Enum ini mendefinisikan metode bagaimana gambar raster dapat diproses selama konversi PDF ke HTML |
| [HtmlSaveOptions.ResourceSavingStrategy](./htmlsaveoptions.resourcesavingstrategy/) | Untuk properti ini Anda dapat menetapkan delegate yang dibuat dari metode khusus yang mengimplementasikan pemrosesan sumber daya eksternal (Font atau Gambar) yang diekstrak dari PDF dan harus disimpan sebagai sumber daya eksternal selama konversi PDF ke HTML. Dalam kasus seperti itu pemrosesan (seperti menyimpan ke stream atau disk) dapat dilakukan dalam kode khusus tersebut dan kode khusus tersebut harus mengembalikan path (atau string lain tanpa tanda kutip) yang kemudian akan dimasukkan ke dalam HTML yang dihasilkan alih-alih path asli yang seharusnya ke sumber daya gambar tersebut. Dalam kasus seperti itu Semua tindakan yang diperlukan untuk menyimpan gambar harus dilakukan dalam kode metode yang disediakan, karena penyimpanan hasil dalam kode konverter tidak akan digunakan. Jika pemrosesan untuk file ini atau itu karena alasan tertentu harus dilakukan oleh kode konverter sendiri, bukan dalam kode khusus, silakan set dalam kode khusus flag 'CustomProcessingCancelled' dari variabel parameter 'resourceSavingInfo'. Itu memberi sinyal ke konverter bahwa semua langkah yang diperlukan untuk memproses sumber daya tersebut harus dilakukan oleh konverter sendiri seolah-olah tidak ada kode khusus eksternal apa pun. |
| [Hyperlink](./hyperlink/) | Mewakili hyperlink abstrak. |
| [IconFit](./iconfit/) | Menjelaskan bagaimana ikon anotasi widget harus ditampilkan di dalam persegi panjang anotasinya. |
| [Id](./id/) | <p> Mewakili struktur pengidentifikasi file. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre> |
| [Image](./image/) | Mewakili gambar. |
| [ImageDeleteAction](./imagedeleteaction/) | Aksi yang dilakukan dengan objek gambar ketika gambar dihapus dari koleksi. Jika objek gambar dihapus |
| [ImagePlacement](./imageplacement/) | <p> Mewakili karakteristik gambar yang ditempatkan pada halaman dokumen Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan gambar sebagai bitmap dengan dimensi yang terlihat. // Buka dokumen Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Buat objek ImagePlacementAbsorber untuk melakukan pencarian penempatan gambar ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Terima absorber untuk halaman pertama doc.getPages().get_Item(1).accept(abs); // Ambil gambar dengan dimensi yang terlihat for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Ambil gambar dari sumber daya imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Buat bitmap baru dengan dimensi aktual scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Ketika sebuah gambar ditempatkan pada halaman, gambar tersebut mungkin memiliki dimensi yang berbeda dari dimensi fisik yang didefinisikan dalam {@code Resources}. Objek {@code ImagePlacement} dimaksudkan untuk menyediakan informasi tersebut seperti dimensi, resolusi, dan sebagainya. </p> |
| [ImagePlacementAbsorber](./imageplacementabsorber/) | <p> Mewakili objek absorber untuk objek penempatan gambar. Melakukan pencarian penggunaan gambar dan menyediakan akses ke hasil pencarian melalui koleksi {@code ImagePlacementAbsorber.ImagePlacements}. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan gambar pada halaman pertama dokumen PDF dan mendapatkan properti penempatan gambar. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println("image width:" + imagePlacement.getRectangle().getWidth()); System.out.println("image height:" + imagePlacement.getRectangle().getHeight()); System.out.println("image LLX:" + imagePlacement.getRectangle(0).getX()); System.out.println("image LLY:" + imagePlacement.getRectangle().getY()); System.out.println("image horizontal resolution:" + imagePlacement.getResolution().getX()); System.out.println("image vertical resolution:" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> Objek {@code ImagePlacementAbsorber} pada dasarnya digunakan dalam skenario pencarian gambar. Ketika pencarian selesai, kemunculan tersebut direpresentasikan dengan objek {@code ImagePlacement} yang terdapat dalam koleksi {@code ImagePlacementAbsorber.ImagePlacements}. Objek {@code ImagePlacement} menyediakan akses ke properti penempatan gambar: dimensi, resolusi, dll. </p> Rotasi gambar positif berlawanan arah jarum jam, untuk halaman, berarah jarum jam. Di sini, kita perlu merepresentasikan sudut rotasi gambar, sehingga kami mengurangkan sudut halaman dari sudut gambar. |
| [ImagePlacementCollection](./imageplacementcollection/) | Mewakili koleksi penempatan gambar |
| [ImageStamp](./imagestamp/) | Mewakili stempel grafis. |
| [ImageType](./imagetype/) | Mewakili tipe format gambar. |
| [ImportDataAction](./importdataaction/) | Saat pemanggilan aksi import-data, data Forms Data Format (FDF) akan diimpor ke dalam formulir interaktif dokumen dari file yang ditentukan. |
| [ImportFieldsOptions](./importfieldsoptions/) | Mewakili kelas dasar opsi untuk mengimpor bidang formulir. |
| [ImportFieldsToJsonOptions](./importfieldstojsonoptions/) | Mewakili opsi untuk mengimpor bidang formulir ke format Json. Mewarisi dari {@code ImportFieldsOptions} dan menambahkan opsi khusus untuk impor Json. |
| [ImportOptions](./importoptions/) | Tipe ImportOptions menahan tingkat abstraksi pada opsi impor individual. |
| [InkAnnotation](./inkannotation/) | Mewakili "coretan" bebas yang terdiri dari satu atau lebih jalur terpisah. |
| [InternalHelper](./internalhelper/) | Kelas internal |
| [InternalHelper.InternalLogic](./internalhelper.internallogic/) |  |
| [InternalHelper.InternalLogic.ForbidenFunctionalityForReleasedProduct](./internalhelper.internallogic.forbidenfunctionalityforreleasedproduct/) |  |
| [InternalHelper.InternalLogic.TestHelper](./internalhelper.internallogic.testhelper/) |  |
| [InternalHelper.InternalLogic.TestUnitFunctional](./internalhelper.internallogic.testunitfunctional/) |  |
| [InternalHelper.XfaMergeWrapper](./internalhelper.xfamergewrapper/) |  |
| [InternalPageGenerator](./internalpagegenerator/) |  |
| [InvalidFormTypeOperationException](./invalidformtypeoperationexception/) | Pengecualian yang dilemparkan ketika operasi dengan tipe formulir tidak valid. |
| [JavascriptAction](./javascriptaction/) | Kelas yang merepresentasikan aksi javascript. |
| [JavaScriptCollection](./javascriptcollection/) | Kelas ini mewakili koleksi JavaScript. |
| [LatexFragment](./latexfragment/) | Mewakili fragmen TeX. @deprecated Silakan gunakan TeXFragment sebagai gantinya |
| [LatexLoadOptions](./latexloadoptions/) | Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF. @deprecated Gunakan TeXLoadOptions sebagai gantinya. |
| [LaTeXSaveOptions](./latexsaveoptions/) | Opsi penyimpanan untuk ekspor ke format TeX. @deprecated Gunakan TeXSaveOptions sebagai gantinya |
| [LaunchAction](./launchaction/) | Mewakili aksi peluncuran yang meluncurkan aplikasi atau membuka atau mencetak dokumen. |
| [Layer](./layer/) | Mewakili lapisan dalam halaman PDF. |
| [LevelFormat](./levelformat/) | Mewakili format daftar isi. |
| [License](./license/) | Menyediakan metode untuk melisensikan komponen. Dalam contoh ini, akan dicoba menemukan file lisensi bernama MyLicense.lic di folder yang berisi komponen, di folder yang berisi assembly pemanggil, di folder assembly entri, dan kemudian di sumber daya tersemat dari assembly pemanggil. License license = new License(); license.setLicense("MyLicense.lic"); |
| [LicenseInfo](./licenseinfo/) | Mewakili informasi lisensi. |
| [LightweightOperatorCollection](./lightweightoperatorcollection/) | Koleksi operator ringan. Dimaksudkan untuk digunakan dalam skenario ketika aliran konten dasar tidak terlampir, di mana hanya koleksi operator yang diperlukan sebagai hasil. |
| [LineAnnotation](./lineannotation/) | Kelas yang merepresentasikan anotasi garis. |
| [LineEndingConverter](./lineendingconverter/) | Mewakili kelas LineEndingConverter |
| [LineEndingsDrawer](./lineendingsdrawer/) | Menggambar ujung garis untuk anotasi. Kelas internal hanya untuk penggunaan internal. |
| [LinkAnnotation](./linkannotation/) | Mewakili baik tautan hiperteks ke tujuan lain dalam dokumen maupun aksi yang akan dilakukan. |
| [ListBoxField](./listboxfield/) | Kelas mewakili bidang ListBox. |
| [LoadOptions](./loadoptions/) | Tipe LoadOptions menyimpan tingkat abstraksi pada opsi muat individu. |
| [LoadOptions.MarginsAreaUsageModes](./loadoptions.marginsareausagemodes/) | Mewakili mode penggunaan area margin selama konversi (seperti HTML, EPUB, dll), mendefinisikan penanganan instruksi format yang diimpor terkait penggunaan margin. |
| [LoadOptions.PageSizeAdjustmentModes](./loadoptions.pagesizeadjustmentmodes/) | PERHATIAN! Fitur telah diimplementasikan tetapi belum dimasukkan ke API publik karena masalah penghalang di lapisan OSHARED yang terdeteksi pada dokumen contoh. Mewakili mode penggunaan ukuran halaman selama konversi. Format (seperti HTML, EPUB, dll) biasanya memiliki desain mengambang, sehingga memungkinkan menyesuaikan ukuran halaman yang diperlukan. Namun terkadang konten menentukan posisi horizontal atau ukuran yang tidak memungkinkan menempatkan konten ke dalam ukuran halaman yang diperlukan. Dalam kasus tersebut kita dapat menentukan apa yang harus dilakukan (misalnya ketika ukuran konten tidak cocok dengan ukuran halaman awal yang diperlukan pada dokumen PDF hasil). |
| [LoadOptions.ResourceLoadingResult](./loadoptions.resourceloadingresult/) | Hasil pemuatan khusus sumber daya. |
| [LocaleOptions](./localeoptions/) | Tipe LocaleOptions menentukan konfigurasi lokal untuk Aspose.PDF. |
| [LocalHyperlink](./localhyperlink/) | Mewakili objek hyperlink lokal. |
| [MarginInfo](./margininfo/) | Kelas ini mewakili margin untuk berbagai objek. |
| [MarkupAnnotation](./markupannotation/) | Kelas abstrak yang mewakili anotasi markup. |
| [MarkupParagraph](./markupparagraph/) | Mewakili sebuah paragraf. |
| [MarkupSection](./markupsection/) | Mewakili sebuah seksi markup - wilayah persegi panjang pada halaman yang berisi teks dan dapat dipisahkan secara visual dari blok teks lainnya. |
| [Matrix](./matrix/) | Kelas mewakili matriks transformasi. |
| [Matrix3D](./matrix3d/) | Kelas mewakili matriks transformasi. |
| [MdLoadOptions](./mdloadoptions/) | Opsi muat untuk konversi format Markdown. |
| [Measure](./measure/) | Kelas yang menjelaskan sistem koordinat Measure. |
| [Measure.NumberFormat](./measure.numberformat/) | Format angka untuk pengukuran. |
| [Measure.NumberFormatList](./measure.numberformatlist/) | Mewakili daftar format angka. |
| [MediaClip](./mediaclip/) | Kelas menjelaskan objek klip media dari rendering. |
| [MediaClipData](./mediaclipdata/) | Kelas menjelaskan data klip media. |
| [MediaClipSection](./mediaclipsection/) | Kelas ini menjelaskan seksi klip Media. |
| [MediaRendition](./mediarendition/) | Kelas menjelaskan rendering media. |
| [MemoryCleaner](./memorycleaner/) | Mewakili kelas MemoryCleaner. |
| [MemoryExtender](./memoryextender/) | Mewakili kelas MemoryExtender. Menggunakan file besar pada sistem dengan memori heap terbatas, dapat diaktifkan untuk menggunakan ruang disk sebagai memori swap sementara. |
| [MemoryFontSource](./memoryfontsource/) | Mewakili sumber file font tunggal. |
| [Metadata](./metadata/) | Menyediakan akses ke aliran metadata XMP. |
| [Metered](./metered/) | <p> Menyediakan metode untuk mengatur kunci bermeter. </p> <hr> Dalam contoh ini, akan dicoba untuk mengatur kunci publik dan privat bermeter <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey(\"PublicKey\", \"PrivateKey\"); </pre> |
| [MhtLoadOptions](./mhtloadoptions/) | Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf. |
| [MobiXmlSaveOptions](./mobixmlsaveoptions/) | Simpan opsi untuk mengekspor ke format Xml |
| [MovieAnnotation](./movieannotation/) | Mewakili anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar. |
| [NamedAction](./namedaction/) | Mewakili aksi bernama yang diharapkan didukung oleh aplikasi penampil PDF. |
| [NamedDestination](./nameddestination/) | Alih-alih didefinisikan secara langsung dengan sintaks eksplisit, tujuan dapat dirujuk secara tidak langsung melalui objek nama atau string byte. |
| [Note](./note/) | Kelas ini mewakili catatan paragraf generator. |
| [NumberField](./numberfield/) | Bidang Teks dengan karakter valid yang ditentukan @see TextBoxField |
| [NumberTree](./numbertree/) | Kelas yang mewakili struktur pohon Nomor dari file PDF. 7.9.7Number Trees |
| [OcspSettings](./ocspsettings/) | Mewakili pengaturan ocsp yang digunakan selama proses penandatanganan. |
| [OfdLoadOptions](./ofdloadoptions/) | Opsi pemuatan untuk format OFD. |
| [Operator](./operator/) | Kelas abstrak yang mewakili operator. |
| [OperatorCollection](./operatorcollection/) | Kelas mewakili kumpulan operator |
| [OperatorSelector](./operatorselector/) | Kelas ini digunakan untuk memilih operator menggunakan ide template Visitor. |
| [Opi](./opi/) | Mewakili Open Prepress Interface (OPI) adalah mekanisme untuk membuat placeholder beresolusi rendah, atau proksi, untuk gambar beresolusi tinggi tersebut. |
| [OptimizedMemoryStream](./optimizedmemorystream/) | Mendefinisikan MemoryStream yang dapat berisi kapasitas standar lebih banyak |
| [Option](./option/) | Kelas mewakili opsi bidang pilihan. |
| [OptionCollection](./optioncollection/) | Kelas yang mewakili kumpulan opsi bidang pilihan. |
| [OutlineCollection](./outlinecollection/) | Mewakili hierarki garis besar dokumen. |
| [OutlineItemCollection](./outlineitemcollection/) | Mewakili entri garis besar dalam hierarki garis besar dokumen PDF. |
| [Outlines](./outlines/) | Kelas menggambarkan kumpulan garis besar. |
| [OutputIntent](./outputintent/) | Mewakili niat output yang mencocokkan karakteristik warna dokumen PDF dengan perangkat output target atau lingkungan produksi tempat dokumen akan dicetak. |
| [OutputIntents](./outputintents/) | Mewakili kumpulan {@link OutputIntent}. |
| [Page](./page/) | Kelas yang mewakili halaman dokumen PDF. |
| [Page.BeforePageGenerate](./page.beforepagegenerate/) | Prosedur untuk menyesuaikan header dan footer. |
| [PageActionCollection](./pageactioncollection/) | Kelas ini menggambarkan aksi halaman |
| [PageCollection](./pagecollection/) | Kumpulan halaman dokumen PDF. |
| [PageExtensions](./pageextensions/) | Menyediakan kemampuan tambahan untuk kelas Page. |
| [PageInfo](./pageinfo/) | Mewakili informasi halaman untuk generator pdf. |
| [PageInformationAnnotation](./pageinformationannotation/) | Mewakili anotasi Page Information dalam dokumen PDF. Anotasi ini berisi nama file, nomor halaman, serta tanggal dan waktu pembuatan anotasi. Kelas ini terutama digunakan untuk menambahkan metadata ke halaman tertentu dalam dokumen PDF, yang dapat berguna untuk tujuan pelacakan dan referensi. Misalnya, dapat digunakan untuk menandai halaman selama proses pencetakan atau untuk memberikan informasi tambahan tentang halaman saat melihat dokumen. |
| [PageLabel](./pagelabel/) | Kelas yang mewakili rentang Page Label. |
| [PageLabelCollection](./pagelabelcollection/) | Kelas yang mewakili koleksi label halaman. |
| [PageMarkup](./pagemarkup/) | Markup halaman yang direpresentasikan oleh koleksi {@code MarkupSection} dan {@code MarkupParagraph}. |
| [PageNumberStamp](./pagenumberstamp/) | Mewakili stempel nomor halaman dan digunakan untuk memberi nomor pada halaman. |
| [PageSize](./pagesize/) | Kelas yang mewakili ukuran halaman dalam dokumen PDF. |
| [PaginationArtifact](./paginationartifact/) | Mewakili kelas dasar abstrak untuk artefak paginasi dalam sebuah dokumen. |
| [ParagraphAbsorber](./paragraphabsorber/) | <p> Mewakili objek absorber dari objek struktur halaman seperti bagian dan paragraf. Melakukan pencarian untuk bagian dan paragraf teks serta menyediakan akses ke persegi panjang dan poligon yang menggambarkannya dalam ruang koordinat teks. Juga melakukan pencarian segmen teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragments} yang dikelompokkan berdasarkan elemen struktur. </p> Contoh ini menunjukkan cara menemukan segmen teks pertama dari setiap paragraf pada halaman pertama dokumen PDF dan menyorotnya. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> Ketika pencarian selesai, koleksi {@code ParagraphAbsorber.PageMarkups} akan berisi objek {@code PageMarkup} yang mewakili struktur halaman oleh koleksi {@code MarkupSection} dan {@code MarkupParagraph}. Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) | Mewakili opsi untuk {@link ParagraphAbsorber}. |
| [Paragraphs](./paragraphs/) | Kelas ini mewakili koleksi paragraf. |
| [PasswordBoxField](./passwordboxfield/) | Kelas yang menjelaskan bidang teks untuk memasukkan kata sandi. |
| [PclLoadOptions](./pclloadoptions/) | Mewakili opsi untuk memuat (import) file PCL ke dalam dokumen pdf. |
| [PclLoadOptions.ConversionEngines](./pclloadoptions.conversionengines/) | Menumerasikan mesin konversi yang dapat digunakan untuk konversi. |
| [PDF3DAnnotation](./pdf3dannotation/) | Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi. @see Annotation |
| [PDF3DArtwork](./pdf3dartwork/) | Kelas PDF3DArtwork. |
| [PDF3DContent](./pdf3dcontent/) | Kelas PDF3DContent. |
| [PDF3DCrossSection](./pdf3dcrosssection/) | Kelas PDF3DCrossSection. |
| [PDF3DCrossSectionArray](./pdf3dcrosssectionarray/) | Kelas PDF3DCrossSectionArray. |
| [PDF3DCuttingPlaneOrientation](./pdf3dcuttingplaneorientation/) | Kelas PDF3DCuttingPlaneOrientation. |
| [PDF3DLightingScheme](./pdf3dlightingscheme/) | Kelas PDF3DLightingScheme. |
| [PDF3DRenderMode](./pdf3drendermode/) | Kelas PDF3DRenderMode. |
| [PDF3DStream](./pdf3dstream/) | Kelas PDF3DStream. |
| [PDF3DView](./pdf3dview/) | Kelas PDF3DView. |
| [PDF3DViewArray](./pdf3dviewarray/) | Kelas PDF3DViewArray. |
| [PdfAction](./pdfaction/) | Mewakili Tindakan dalam dokumen PDF |
| [PdfActionCollection](./pdfactioncollection/) | Kelas menjelaskan daftar tindakan. |
| [PdfASymbolicFontEncodingStrategy](./pdfasymbolicfontencodingstrategy/) | Kelas ini menjelaskan aturan yang dapat digunakan untuk menyesuaikan proses penyalinan data enkoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu enkoding. Beberapa dokumen PDF setelah dikonversi ke format PDF/A dapat menghasilkan error "More than one encoding in symbolic TrueType font's cmap". Apa penyebab error ini? Semua font simbolik TrueType memiliki tabel khusus "cmap" dalam data internalnya. Tabel ini memetakan kode karakter ke indeks glif. Dan tabel ini dapat berisi sub‑tabel enkoding yang berbeda yang menjelaskan enkoding yang digunakan. Lihat informasi lanjutan tentang tabel cmap di https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Biasanya tabel cmap berisi beberapa sub‑tabel enkoding, tetapi standar PDF/A mengharuskan bahwa hanya satu sub‑tabel enkoding yang boleh tersisa untuk font ini dalam dokumen PDF/A atau harus ada sub‑tabel enkoding (3,0) di antara sub‑tabel font ini. Dan pertanyaan kunci di sini - data apa yang harus diambil dari sub‑tabel lain untuk disalin ke tabel enkoding tujuan (3,0)? Sebagian besar font memiliki tabel cmap yang 'well‑formed' di mana setiap sub‑tabel enkoding sepenuhnya konsisten dengan sub‑tabel lain. Namun beberapa font memiliki tabel cmap dengan tabrakan - misalnya satu sub‑tabel memiliki indeks glif 100 untuk unicode 100, tetapi sub‑tabel lain memiliki indeks glif 200 untuk unicode 100 yang sama. Untuk menyelesaikan masalah ini diperlukan strategi khusus. Secara default strategi berikut digunakan: sub‑tabel mac(1,0) dicari. Jika tabel ini ditemukan, hanya data ini yang digunakan untuk mengisi tabel tujuan (3,0). Jika sub‑tabel mac tidak ditemukan, maka semua sub‑tabel kecuali (3,0) diiterasi dan digunakan untuk menyalin data ke sub‑tabel tujuan (3,0). Juga pemetaan untuk setiap unicode (unicode, indeks glif) disalin ke tabel tujuan hanya jika tabel tujuan belum memiliki unicode tersebut pada saat ini. Jadi, misalnya jika sub‑tabel pertama memiliki indeks glif 100 untuk unicode 100, dan sub‑tabel berikutnya memiliki indeks glif 200 untuk unicode 100 yang sama, hanya data dari sub‑tabel pertama (unicode=100, indeks glif = 100) yang akan disalin. Sehingga setiap sub‑tabel sebelumnya memiliki prioritas lebih tinggi daripada yang berikutnya. Properti dari kelas ini { PdfASymbolicFontEncodingStrategy} membantu menyesuaikan perilaku default. Jika properti {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) bertipe { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} diatur, maka sub‑tabel yang relevan akan digunakan dengan prioritas di atas sub‑tabel mac(1,0). Nilai 'MacTable' dari enumerasi {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini, karena menunjuk ke sub‑tabel mac (1,0) yang sama yang akan digunakan secara default. Properti {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) mengabaikan semua prioritas untuk setiap sub‑tabel. Jika properti ini diatur, maka hanya sub‑tabel dari antrian yang dideklarasikan yang akan digunakan dalam urutan yang ditentukan. Jika sub‑tabel yang ditentukan tidak ditemukan, maka iterasi default semua sub‑tabel dan strategi penyalinan yang dijelaskan di atas akan digunakan. Objek { PdfASymbolicFontEncodingStrategy.QueueItem} menentukan sub‑tabel enkoding yang digunakan. Sub‑tabel ini dapat diatur melalui kombinasi anggota (PlatformID, PlatformSpecificId) atau melalui enumerasi { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Jika font tidak memiliki sub‑tabel (3,0), sub‑tabel lain akan digunakan untuk menjaga kompatibilitas PDF/A. Pemilihan sub‑tabel yang akan digunakan dibuat berdasarkan aturan yang sama seperti yang dijelaskan sebelumnya, sehingga properti {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) dan {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) digunakan untuk menentukan sub‑tabel hasil, dan jika font tidak memiliki sub‑tabel yang diminta, maka sub‑tabel yang ada akan digunakan. |
| [PdfASymbolicFontEncodingStrategy.QueueItem](./pdfasymbolicfontencodingstrategy.queueitem/) | Menentukan subtabel enkoding. Setiap subtabel enkoding memiliki kombinasi unik parameter (PlatformID, PlatformSpecificID). Enumerasi {@code CMapEncodingTableType} dan properti {@code CMapEncodingTable} diimplementasikan untuk mempermudah penetapan subtabel enkoding yang diperlukan. |
| [PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType](./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) | Mendeklarasikan sekumpulan beberapa subtabel enkoding yang dikenal |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/) | mewakili sekumpulan opsi untuk mengonversi dokumen PDF |
| [PdfFormatConversionOptions.PdfANonSpecificationFlags](./pdfformatconversionoptions.pdfanonspecificationflags/) | Kelas ini menyimpan flag untuk mengendalikan konversi PDF/A pada kasus ketika dokumen PDF sumber tidak sesuai dengan spesifikasi PDF. Jika flag kelas ini digunakan, kinerjanya menurun tetapi diperlukan ketika dokumen PDF sumber tidak dapat dikonversi ke format PDF/A dengan cara biasa. Secara default semua flag diatur ke false. |
| [PdfFormatConversionOptions.PuaProcessingStrategy](./pdfformatconversionoptions.puaprocessingstrategy/) | Beberapa dokumen PDF memiliki simbol unicode khusus, yang termasuk dalam Private Use Area (PUA), lihat deskripsi di https://en.wikipedia.org/wiki/Private_Use_Areas. Simbol-simbol ini menyebabkan kesalahan kepatuhan PDF/A seperti "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk menangani simbol PUA. |
| [PdfFormatConversionOptions.RemoveFontsStrategy](./pdfformatconversionoptions.removefontsstrategy/) | Beberapa dokumen memiliki ukuran besar setelah konversi ke format PDF/A. Untuk mengurangi ukuran file bagi dokumen-dokumen ini, diperlukan penetapan strategi penghapusan font. Enumerasi ini mendeklarasikan strategi yang dapat digunakan untuk mengoptimalkan penggunaan font. Setiap strategi dalam enumerasi ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur. |
| [PdfFormatConversionOptions.SegmentAlignStrategy](./pdfformatconversionoptions.segmentalignstrategy/) | Menjelaskan strategi yang digunakan untuk menyelaraskan segmen teks dokumen. Saat ini hanya strategi untuk mengembalikan segmen ke batas asli yang didukung. Di masa depan strategi lain dapat ditambahkan. |
| [PdfPageStamp](./pdfpagestamp/) | Kelas ini mewakili stempel yang menggunakan halaman PDF sebagai stempel. |
| [PdfSaveOptions](./pdfsaveoptions/) | Opsi penyimpanan untuk ekspor ke format Pdf |
| [PdfXmlLoadOptions](./pdfxmlloadoptions/) | Opsi pemuatan untuk format PdfXml. |
| [PdfXmlSaveOptions](./pdfxmlsaveoptions/) | Opsi penyimpanan untuk format PdfXml. |
| [Permissions](./permissions/) | Bendera Biner Enum ini mewakili izin pengguna untuk sebuah pdf. |
| [PKCS1](./pkcs1/) | Mewakili objek tanda tangan sesuai standar PKCS#1. Algoritma enkripsi RSA dan metode digest SHA-1 digunakan untuk penandatanganan. |
| [PKCS7](./pkcs7/) | Mewakili objek PKCS#7 yang sesuai dengan spesifikasi PKCS#7 dalam Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Versi 1.5. Digest SHA1 dari rentang byte dokumen dikapsulkan dalam bidang SignedData PKCS#7. |
| [PKCS7Detached](./pkcs7detached/) | Mewakili objek PKCS#7 yang sesuai dengan spesifikasi PKCS#7 dalam Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Versi 1.5. Digest pesan tertanda asli atas rentang byte dokumen dimasukkan sebagai bidang SignedData PKCS#7 yang normal. Tidak ada data yang dikapsulkan dalam bidang SignedData PKCS#7. |
| [Point](./point/) | Mewakili titik dengan koordinat pecahan. |
| [Point3D](./point3d/) | Mewakili titik dengan koordinat pecahan. |
| [PolyAnnotation](./polyannotation/) | Kelas dasar abstrak untuk poly-annotations. |
| [PolygonAnnotation](./polygonannotation/) | Kelas yang mewakili anotasi poligon. |
| [PolylineAnnotation](./polylineannotation/) | Mewakili anotasi polyline yang mirip dengan poligon, kecuali bahwa vertex pertama dan terakhir tidak terhubung secara implisit. |
| [PopupAnnotation](./popupannotation/) | Mewakili anotasi pop-up yang menampilkan teks dalam jendela pop-up untuk entri dan penyuntingan. |
| [Position](./position/) | Mewakili objek posisi |
| [PptxSaveOptions](./pptxsaveoptions/) | Opsi penyimpanan untuk ekspor ke format SVG |
| [PrintController](./printcontroller/) | Mewakili kontroler pencetakan. |
| [PrintDuplex](./printduplex/) | Opsi penanganan kertas yang digunakan saat mencetak file dari dialog cetak. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Kelas abstrak yang mewakili anotasi tanda printer. |
| [PrinterMarksKind](./printermarkskind/) | Menentukan jenis tanda printer yang akan ditambahkan ke dokumen. Enumerasi ini memiliki atribut {@link FlagsAttribute} yang memungkinkan kombinasi bitwise dari nilai anggota-nya. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Menyediakan metode ekstensi untuk enumerasi {@link PrinterMarksKind}. |
| [PrintScaling](./printscaling/) | Opsi skala halaman yang harus dipilih ketika dialog cetak ditampilkan untuk dokumen ini. |
| [ProgressEventType](./progresseventtype/) | Enum ini menggambarkan jenis peristiwa kemajuan yang mungkin terjadi selama konversi. |
| [PsLoadOptions](./psloadoptions/) | Mewakili opsi untuk memuat/mengimpor file .mht ke dalam dokumen pdf. |
| [PsSaveOptions](./pssaveoptions/) | Opsi penyimpanan untuk ekspor ke format PS (PostScript) atau EPS. |
| [RadioButtonField](./radiobuttonfield/) | Kelas yang merepresentasikan bidang tombol radio. |
| [RadioButtonOptionField](./radiobuttonoptionfield/) | Kelas yang merepresentasikan item bidang RadioButton. |
| [Rectangle](./rectangle/) | Kelas yang merepresentasikan persegi panjang. |
| [Redaction](./redaction/) | Hanya untuk penggunaan internal @author User |
| [RedactionAnnotation](./redactionannotation/) | Merepresentasikan anotasi Redact. |
| [RegexManager](./regexmanager/) | Menyediakan pembungkus untuk operasi ekspresi reguler dengan pengaturan batas waktu yang dapat dikonfigurasi. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Merepresentasikan anotasi Registration Mark. Tanda registrasi adalah simbol yang ditambahkan ke pelat cetak atau layar untuk memastikan penyelarasan warna yang tepat selama proses pencetakan. |
| [RenderingOptions](./renderingoptions/) | Merepresentasikan opsi rendering |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: sekumpulan tipe mode render |
| [Rendition](./rendition/) | Kelas yang menggambarkan objek rendition dari RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Aksi rendition yang mengontrol pemutaran konten multimedia. |
| [RenditionOperation](./renditionoperation/) | Operasi yang akan dilakukan ketika aksi dipicu. |
| [RenditionType](./renditiontype/) | Enumerasi yang menggambarkan tipe-tipe Rendition yang mungkin. |
| [Resources](./resources/) | Kelas yang merepresentasikan sumber daya halaman. |
| [Resources.ExtGStateValue](./resources.extgstatevalue/) | Merepresentasikan ExtGStates dengan beberapa nilai. |
| [RgbToDeviceGrayConversionStrategy](./rgbtodevicegrayconversionstrategy/) | Merepresentasikan strategi konversi ruang warna rgb ke device gray. |
| [RichMediaAnnotation](./richmediaannotation/) | Kelas yang menggambarkan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF. |
| [RichMediaAnnotation.ActivationEvent](./richmediaannotation.activationevent/) | Peristiwa yang mengaktifkan anotasi. |
| [RichMediaAnnotation.ContentType](./richmediaannotation.contenttype/) | Tipe multimedia. |
| [RichTextBoxField](./richtextboxfield/) | Kelas yang menggambarkan komponen editor teks kaya. |
| [RichTextFontStyles](./richtextfontstyles/) | Opsi untuk menata fragmen teks dalam RichText. |
| [RootElement](./rootelement/) | Elemen struktur akar. |
| [Row](./row/) | Mewakili baris tabel. |
| [Rows](./rows/) | Mewakili koleksi baris tabel. |
| [RtfLoadOptions](./rtfloadoptions/) | Opsi pemuatan untuk format RTF. |
| [SaveOptions](./saveoptions/) | Tipe SaveOptions menyimpan tingkat abstraksi pada opsi penyimpanan individu |
| [SaveOptions.BorderInfo](./saveoptions.borderinfo/) | Instansi kelas ini mewakili informasi tentang batas yang dapat digambar pada dokumen hasil. |
| [SaveOptions.BorderPartStyle](./saveoptions.borderpartstyle/) | Mewakili informasi tentang satu bagian batas (atas, bawah, sisi kiri, atau sisi kanan) |
| [SaveOptions.MarginInfo](./saveoptions.margininfo/) | Instansi kelas ini mewakili informasi tentang margin halaman yang dapat digambar pada dokumen hasil. |
| [SaveOptions.MarginPartStyle](./saveoptions.marginpartstyle/) | Mewakili informasi tentang satu bagian margin (atas, bawah, sisi kiri, atau sisi kanan) |
| [SaveOptions.ResourceSavingInfo](./saveoptions.resourcesavinginfo/) | Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file sumber eksternal yang terjadi selama konversi PDF ke format lain (mis. HTML). |
| [ScalingMode](./scalingmode/) | Jenis skala yang akan digunakan. |
| [ScalingReason](./scalingreason/) | Kondisi di mana ikon akan diubah skalanya di dalam persegi anotasi. |
| [ScreenAnnotation](./screenannotation/) | Anotasi layar yang menentukan wilayah halaman tempat klip media dapat diputar. |
| [SelectorRendition](./selectorrendition/) | Kelas yang menggambarkan render selector. |
| [Signature](./signature/) | Kelas abstrak yang mewakili objek tanda tangan dalam dokumen pdf. Tanda tangan adalah bidang dengan nilai objek tanda tangan, yang terakhir berisi data yang digunakan untuk memverifikasi keabsahan dokumen. |
| [SignatureCustomAppearance](./signaturecustomappearance/) | Kelas abstrak yang mewakili objek tampilan khusus tanda tangan. |
| [SignatureField](./signaturefield/) | Mewakili bidang formulir tanda tangan. |
| [SignHash](./signhash/) | Delegasi untuk menandatangani hash dokumen secara khusus (Beta). |
| [SoundAnnotation](./soundannotation/) | Mewakili anotasi suara yang berisi suara yang direkam dari mikrofon komputer atau diimpor dari file. |
| [SoundData](./sounddata/) | Mewakili data suara yang menentukan suara yang akan diputar saat anotasi diaktifkan. |
| [SoundEncoding](./soundencoding/) | Format enkoding untuk data sampel. |
| [SoundIcon](./soundicon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |
| [SoundIconConverter](./soundiconconverter/) | Mewakili kelas SoundIconConverter |
| [SoundSampleData](./soundsampledata/) | Mewakili entri tambahan yang spesifik untuk objek suara (Bagian 9.2 PDF1-7). |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Format enkoding untuk data sampel suara. |
| [SquareAnnotation](./squareannotation/) | Kelas yang mewakili anotasi persegi. |
| [SquigglyAnnotation](./squigglyannotation/) | Mewakili anotasi bergelombang yang muncul sebagai garis bawah bergerigi dalam teks dokumen. |
| [Stamp](./stamp/) | Kelas abstrak untuk berbagai jenis stempel yang muncul sebagai turunan. |
| [StampAnnotation](./stampannotation/) | <p> Mewakili anotasi stempel karet. Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan agar terlihat seolah-olah mereka dicap pada halaman dengan stempel karet. </p> <hr> <pre> Potongan kode berikut menunjukkan cara menambahkan 2 stempel ke halaman pertama dokumen pdf. Dokumen input berasal dari inFile dan perubahan disimpan ke outFile. Stempel pertama memiliki ikon NotForPublicRelease dan yang kedua menggunakan gambar dari rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre> |
| [StampIconConverter](./stampiconconverter/) | Mewakili kelas StampIconConverter. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Mewakili anotasi coret yang muncul sebagai coretan dalam teks dokumen. |
| [StructElement](./structelement/) | Elemen struktur umum. |
| [SubjectNameElements](./subjectnameelements/) | Enumerasi yang menjelaskan elemen dalam string subjek tanda tangan. |
| [SubmitFormAction](./submitformaction/) | Kelas yang menjelaskan aksi submit-form. |
| [SvgLoadOptions](./svgloadoptions/) | Mewakili opsi untuk memuat/mengimpor file SVG ke dalam dokumen pdf. |
| [SvgLoadOptions.ConversionEngines](./svgloadoptions.conversionengines/) | Menumerasikan mesin konversi yang dapat digunakan untuk konversi. |
| [SvgSaveOptions](./svgsaveoptions/) | Opsi penyimpanan untuk ekspor ke format SVG |
| [SvgSaveOptions.SvgImageSavingInfo](./svgsaveoptions.svgimagesavinginfo/) | Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML. |
| [Symbology](./symbology/) | Sebuah (Barcode) Simbologi mendefinisikan detail teknis dari jenis barcode tertentu: lebar bar, set karakter, metode enkoding, spesifikasi checksum, dll. |
| [SystemFontSource](./systemfontsource/) | Mewakili semua font yang terpasang di sistem. |
| [TabAlignmentType](./tabalignmenttype/) | Menumerasikan tipe perataan tab. |
| [Table](./table/) | Mewakili tabel yang dapat ditambahkan ke halaman. |
| [TableAbsorber](./tableabsorber/) | <p> Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi {@code TableAbsorber.TableList}. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan tabel pada halaman pertama dokumen PDF dan mengganti teks dalam sel tabel. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [TabLeaderType](./tableadertype/) | Menumerasikan tipe pemimpin tab. |
| [TableBroken](./tablebroken/) | Menumerasikan tabel yang rusak. |
| [TabOrder](./taborder/) | Urutan tab pada halaman. |
| [TabStop](./tabstop/) | Mewakili posisi henti Tab khusus dalam paragraf. |
| [TabStops](./tabstops/) | Mewakili koleksi objek {@code TabStop}. |
| [TeXFragment](./texfragment/) | Mewakili fragmen LaTeX. |
| [TeXLoadOptions](./texloadoptions/) | Mewakili opsi untuk memuat/mengimpor file TeX ke dalam dokumen PDF. |
| [TeXMemoryOutputDirectory](./texmemoryoutputdirectory/) | Mengimplementasikan pengambilan aliran output dari memori. Anda dapat menggunakannya, misalnya, ketika Anda tidak ingin output yang menyertainya (seperti file log) ditulis ke disk tetapi ingin membacanya nanti dari memori. |
| [TeXSaveOptions](./texsaveoptions/) | Opsi penyimpanan untuk ekspor ke format TeX. |
| [TextAbsorber](./textabsorber/) | <p> Mewakili objek absorber teks. Melakukan ekstraksi teks dan menyediakan akses ke hasil melalui objek {@code TextAbsorber.Text}. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak teks pada halaman pertama dokumen PDF. // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> Objek {@code TextAbsorber} digunakan untuk mengekstrak teks dari dokumen Pdf atau halaman dokumen tersebut. </p> |
| [TextAnnotation](./textannotation/) | Mewakili anotasi teks yang berupa "sticky note" yang terpasang pada suatu titik dalam dokumen PDF. |
| [TextBoxField](./textboxfield/) | Kelas yang mewakili bidang kotak teks. |
| [TextBuilder](./textbuilder/) | Menambahkan objek teks ke halaman Pdf. |
| [TextDefaults](./textdefaults/) | Mendefinisikan nilai default subsistem teks |
| [TextDefaults.DefaultFontStrategy](./textdefaults.defaultfontstrategy/) | Menentukan jenis nilai default subsistem teks |
| [TextEditOptions](./texteditoptions/) | Menjelaskan opsi operasi penyuntingan teks. |
| [TextElement](./textelement/) | Elemen teks umum dari struktur logis dokumen. |
| [TextEncodingInternal](./textencodinginternal/) |  |
| [TextExtractionError](./textextractionerror/) | Menjelaskan bahwa kesalahan ekstraksi teks telah muncul dalam dokumen PDF. |
| [TextExtractionErrorLocation](./textextractionerrorlocation/) | Mewakili lokasi dalam dokumen PDF di mana kesalahan ekstraksi teks telah muncul. |
| [TextExtractionOptions](./textextractionoptions/) | Mewakili opsi ekstraksi teks |
| [TextExtractionOptions.TextFormattingMode](./textextractionoptions.textformattingmode/) | Mendefinisikan mode berbeda yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas {@code TextDevice}. |
| [TextFormattingOptions](./textformattingoptions/) | Mewakili opsi pemformatan teks |
| [TextFormattingOptions.LineSpacingMode](./textformattingoptions.linespacingmode/) | Mendefinisikan spesifikasi spasi baris |
| [TextFormattingOptions.WordWrapMode](./textformattingoptions.wordwrapmode/) | Mendefinisikan strategi pembungkus kata |
| [TextFragment](./textfragment/) | <p> Mewakili fragmen teks Pdf. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya. // Buka dokumen Document doc = new Document("input.pdf"); // Temukan font yang akan digunakan untuk mengubah font teks dokumen Font font = FontRepository.findFont("Arial"); // Buat objek TextFragmentAbsorber untuk menemukan semua kemunculan teks "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Terima absorber untuk halaman pertama doc.getPages().get(1).accept(absorber); // Ubah teks dan font pada kemunculan teks pertama absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Simpan dokumen doc.save("output.pdf"); </pre> <hr> <pre> Secara singkat, objek {@code TextFragment} berisi daftar objek {@code TextSegment}. Secara rinci: Teks dokumen pdf dalam {@code com.aspose.pdf} direpresentasikan oleh dua objek dasar: {@code TextFragment} dan {@code TextSegment} Perbedaan di antara keduanya sebagian besar bergantung pada konteks. Mari pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk beroperasi dengannya, mengubah propertinya, melihat dll. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.Pdf pada dasarnya menetapkan bahwa objek {@code TextFragment} menyediakan satu set operasi logika atas kumpulan objek {@code TextSegment} fisik yang mewakili kueri pengguna. Dalam skenario pencarian teks, {@code TextFragment} adalah representasi teks "hello world" secara logis, dan koleksi objek {@code TextSegment} mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, {@code TextFragment} mendekati representasi teks logis. Dan {@code TextSegment} mendekati representasi teks fisik. Jelas setiap objek {@code TextSegment} dapat memiliki font, warna, properti penempatan masing-masing. {@code TextFragment} menyediakan cara sederhana untuk mengubah teks beserta propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara itu, objek {@code TextSegment} dapat diakses dan pengguna dapat beroperasi dengan objek {@code TextSegment} secara independen. <p> Perhatikan bahwa mengubah properti TextFragment dapat mengubah koleksi {@code Segments} internal karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi {@code Segments} tidak berubah, silakan ubah segmen internal satu per satu. </p> |
| [TextFragmentAbsorber](./textfragmentabsorber/) | <p> Mewakili objek absorber dari fragmen teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextFragmentAbsorber.TextFragments}. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan teks pada halaman pertama dokumen PDF dan mengganti teks serta fontnya. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Objek {@code TextFragmentAbsorber} pada dasarnya digunakan dalam skenario pencarian teks. Ketika pencarian selesai, kemunculan tersebut direpresentasikan dengan objek {@code TextFragment} yang terdapat dalam koleksi {@code TextFragmentAbsorber.TextFragments}. Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). </p> |
| [TextFragmentCollection](./textfragmentcollection/) | Mewakili koleksi fragmen teks |
| [TextFragmentRemovedEventArgs](./textfragmentremovedeventargs/) |  |
| [TextFragmentState](./textfragmentstate/) | <p> Mewakili keadaan teks dari sebuah fragmen teks. </p> <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks menggunakan objek {@code TextState}. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.TgetextFragments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <p> Menyediakan cara untuk mengubah properti berikut dari teks: font (properti {@code TextFragmentState.Font}) ukuran font (properti {@code TextFragmentState.FontSize}) gaya font (properti {@code TextFragmentState.FontStyle}) warna latar depan (properti {@code TextFragmentState.ForegroundColor}) warna latar belakang (properti {@code TextFragmentState.BackgroundColor}) </p> <p> Perhatikan bahwa mengubah properti {@code TextFragmentState} dapat mengubah koleksi {@code TextFragment.Segments} internal karena TextFragment adalah objek agregat dan dapat menyusun ulang segmen internal atau menggabungkannya menjadi satu segmen. Jika kebutuhan Anda adalah membiarkan koleksi {@code TextFragment.Segments} tidak berubah, silakan ubah segmen internal secara individual. </p> @see TextFragmentAbsorber @see IDocument |
| [TextIcon](./texticon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |
| [TextIconConverter](./texticonconverter/) | Mewakili kelas TextIconConverter |
| [TextMarkupAnnotation](./textmarkupannotation/) | Kelas dasar abstrak untuk anotasi markup teks. |
| [TextOptions](./textoptions/) | Mewakili opsi pemrosesan teks |
| [TextParagraph](./textparagraph/) | <p> Mewakili paragraf teks sebagai objek teks multiline. </p> <hr> <pre> Contoh ini menunjukkan cara membuat objek paragraf teks dan menambahkannya ke halaman Pdf. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // buat paragraf teks TextParagraph paragraph = new TextParagraph(); // atur persegi panjang paragraf paragraph.setRectangle ( new Rectangle(100, 600, 200, 700)); // atur opsi pembungkus kata paragraph.getFormattingOptions().setWrapMode ( TextFormattingOptions.WordWrapMode.ByWords); // tambahkan baris string paragraph.appendLine("the quick brown fox jumps over the lazy dog"); paragraph.appendLine("line2"); paragraph.appendLine("line3"); // tambahkan paragraf ke halaman Pdf dengan TextBuilder TextBuilder textBuilder = new TextBuilder(page); textBuilder.appendParagraph(paragraph); // simpan dokumen Pdf doc.save(outFile); </pre> |
| [TextParagraph.TextBackgroundMode](./textparagraph.textbackgroundmode/) | Mode latar belakang untuk TextParagraph |
| [TextParagraphAbsorber](./textparagraphabsorber/) | Mewakili objek absorber dari paragraf teks. Melakukan pencarian teks dan menyediakan akses ke hasil pencarian melalui koleksi {@code TextParagraphAbsorber.TextParagraphs}. |
| [TextParagraphCollection](./textparagraphcollection/) | Mewakili koleksi paragraf teks |
| [TextReplaceOptions](./textreplaceoptions/) | Mewakili opsi penggantian teks |
| [TextReplaceOptions.ReplaceAdjustment](./textreplaceoptions.replaceadjustment/) | Menentukan aksi yang akan dilakukan setelah mengganti fragmen teks menjadi lebih pendek. None - tidak ada aksi, teks yang diganti dapat tumpang tindih dengan sisa baris; AdjustSpaceWidth - mencoba menyesuaikan spasi antar kata untuk mempertahankan panjang baris; WholeWordsHyphenation - mencoba mendistribusikan kata antar baris paragraf untuk mempertahankan bidang kanan paragraf; ShiftRestOfLine - menggeser sisa baris sesuai dengan perubahan panjang teks, panjang baris dapat diubah; Nilai default adalah ShiftRestOfLine. |
| [TextSearchOptions](./textsearchoptions/) | Mewakili opsi pencarian teks |
| [TextSegment](./textsegment/) | <p> Mewakili segmen teks PDF. </p> <hr> <pre> Contoh ini menunjukkan cara mengubah warna teks dan ukuran font teks dengan objek {@code TextState} dari objek {@code TextSegment}. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> <hr> <pre> Dalam beberapa kata, objek {@code TextSegment} adalah anak dari objek {@code TextFragment}. Secara detail: Teks dokumen pdf dalam {@code Aspose.Pdf} direpresentasikan oleh dua objek dasar: {@code TextFragment} dan {@code TextSegment}. Perbedaan di antara keduanya sebagian besar bergantung pada konteks. Mari pertimbangkan skenario berikut. Pengguna mencari teks "hello world" untuk dioperasikan, mengubah propertinya, melihat dll. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> Representasi fisik teks pdf sangat kompleks. Teks "hello world" dapat terdiri dari beberapa segmen teks yang secara fisik independen. Model teks Aspose.PDF pada dasarnya menetapkan bahwa objek {@code TextFragment} menyediakan satu set operasi logika atas kumpulan objek {@code TextSegment} fisik yang mewakili kueri pengguna. Dalam skenario pencarian teks, {@code TextFragment} adalah representasi logis teks "hello world", dan kumpulan objek {@code TextSegment} mewakili semua segmen fisik yang membentuk objek teks "hello world". Jadi, {@code TextFragment} mendekati representasi teks logis. Dan {@code TextSegment} mendekati representasi teks fisik. Jelas setiap objek {@code TextSegment} dapat memiliki font, warna, properti penempatan sendiri. {@code TextFragment} menyediakan cara sederhana untuk mengubah teks beserta propertinya: mengatur font, mengatur ukuran font, mengatur warna font, dll. Sementara objek {@code TextSegment} dapat diakses dan pengguna dapat beroperasi dengan objek {@code TextSegment} secara independen. </p> |
| [TextSegmentCollection](./textsegmentcollection/) | Mewakili koleksi segmen teks |
| [TextStamp](./textstamp/) | Mewakili cap teks. |
| [TextStamp.NoCharacterAction](./textstamp.nocharacteraction/) | Aksi yang akan dilakukan jika font tidak mengandung karakter yang diperlukan. |
| [TextState](./textstate/) | Mewakili keadaan teks dari sebuah teks |
| [TextStyle](./textstyle/) | Kelas yang mewakili bidang kotak centang |
| [TimestampSettings](./timestampsettings/) | Mewakili pengaturan ocsp yang digunakan selama proses penandatanganan. |
| [TocInfo](./tocinfo/) | Mewakili informasi daftar isi. |
| [ToUnicodeProcessingRules](./tounicodeprocessingrules/) | Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight "Text cannot be mapped to Unicode". |
| [TrimMarkAnnotation](./trimmarkannotation/) | Mewakili anotasi Trim Mark. Trim mark ditempatkan di sudut-sudut halaman cetak untuk menunjukkan di mana halaman harus dipotong. |
| [TxtLoadOptions](./txtloadoptions/) | Opsi pemuatan untuk konversi TXT ke PDF. |
| [UnderlineAnnotation](./underlineannotation/) | Mewakili anotasi underline yang muncul sebagai garis bawah dalam teks dokumen. |
| [UnifiedSaveOptions](./unifiedsaveoptions/) | Kelas ini mewakili opsi penyimpanan untuk penyimpanan yang menggunakan cara konversi terpadu (dengan model dokumen internal terpadu). |
| [UnifiedSaveOptions.ConversionProgressEventHandler](./unifiedsaveoptions.conversionprogresseventhandler/) | Mewakili kelas dengan metode abstrak yang biasanya disediakan oleh pihak pemanggil dan menangani peristiwa kemajuan yang berasal dari konverter. Biasanya penangan pelanggan yang disediakan dapat digunakan untuk menampilkan kemajuan total konversi di konsol atau pada bilah kemajuan. |
| [UnifiedSaveOptions.ProgressEventHandlerInfo](./unifiedsaveoptions.progresseventhandlerinfo/) | Kelas ini mewakili informasi tentang kemajuan konversi yang dapat digunakan dalam aplikasi eksternal untuk menampilkan kemajuan konversi kepada pengguna akhir. |
| [WarningCallback](./warningcallback/) | Antarmuka untuk dukungan mekanisme callback pengguna. |
| [WarningInfo](./warninginfo/) | Objek tidak dapat diubah untuk mengenkapsulasi informasi peringatan. |
| [WarningType](./warningtype/) | / * Enum yang mewakili tipe peringatan. / * / |
| [Watermark](./watermark/) | Mewakili watermark halaman. |
| [WatermarkAnnotation](./watermarkannotation/) | Kelas menjelaskan objek anotasi Watermark. |
| [WatermarkArtifact](./watermarkartifact/) | Kelas menjelaskan artefak watermark. Ini dapat digunakan untuk |
| [WebHyperlink](./webhyperlink/) | Mewakili objek hyperlink web. |
| [WidgetAnnotation](./widgetannotation/) | Kelas yang mewakili anotasi widget. |
| [XFA](./xfa/) | Mewakili formulir XML terkait XML Forms Architecture (XFA). |
| [XfaParserOptions](./xfaparseroptions/) | kelas untuk menangani enkapsulasi data terkait |
| [XfdfReader](./xfdfreader/) | <p> Kelas yang melakukan pembacaan format XFDF. </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p> |
| [XfdfWriter](./xfdfwriter/) | Menggabungkan metode penulisan anotasi dan bidang ke format file XFDF |
| [XForm](./xform/) | Kelas mewakili XForm |
| [XFormCollection](./xformcollection/) | Kelas mewakili koleksi XFormCollection. |
| [XImage](./ximage/) | Kelas yang mewakili X-Object gambar. |
| [XImage.RawParameters](./ximage.rawparameters/) | Kelas yang mewakili parameter XImage mentah gambar. |
| [XImageCollection](./ximagecollection/) | Kelas yang mewakili koleksi XImage. |
| [XmlLoadOptions](./xmlloadoptions/) | Mewakili opsi untuk memuat/mengimpor file XML ke dalam dokumen pdf. |
| [XmlSaveOptions](./xmlsaveoptions/) | Simpan opsi untuk mengekspor ke format Xml |
| [XmpField](./xmpfield/) | Mewakili bidang XMP. |
| [XmpFieldType](./xmpfieldtype/) | Enum ini mewakili tipe-tipe bidang XMP. |
| [XmpPdfAExtensionCategoryType](./xmppdfaextensioncategorytype/) | Kategori properti: internal atau eksternal. |
| [XmpPdfAExtensionField](./xmppdfaextensionfield/) | Skema ini menggambarkan sebuah bidang dalam tipe terstruktur. Ini sangat mirip dengan skema PDF/A Property Value Type, tetapi mendefinisikan sebuah bidang dalam struktur alih-alih properti. Schema namespace URI: http://www.aiim.org/pdfa/ns/field# Required schema namespace prefix: pdfaField. |
| [XmpPdfAExtensionObject](./xmppdfaextensionobject/) | Mewakili kelas dasar untuk instance bidang, properti, tipe nilai. |
| [XmpPdfAExtensionProperty](./xmppdfaextensionproperty/) | Menjelaskan satu properti. Schema namespace URI: http://www.aiim.org/pdfa/ns/property# Required schema namespace prefix: pdfaProperty |
| [XmpPdfAExtensionSchema](./xmppdfaextensionschema/) | Menjelaskan skema ekstensi XMP yang disediakan oleh PDF/A-1. |
| [XmpPdfAExtensionSchemaDescription](./xmppdfaextensionschemadescription/) | Mewakili deskripsi skema ekstensi XMP yang disediakan oleh PDF/A-1. |
| [XmpPdfAExtensionValueType](./xmppdfaextensionvaluetype/) | Skema PDF/A ValueType diperlukan untuk semua tipe nilai properti yang tidak didefinisikan dalam spesifikasi XMP 2004, yaitu untuk tipe nilai di luar daftar berikut: - Tipe array (ini adalah tipe kontainer yang dapat berisi satu atau lebih bidang): Alt, Bag, Seq - Tipe nilai dasar: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipe nilai Manajemen Media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipe nilai Job/Workflow dasar: Job - Tipe nilai skema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType |
| [XmpValue](./xmpvalue/) | Mewakili nilai XMP |
| [XpsLoadOptions](./xpsloadoptions/) | Mewakili opsi untuk memuat/mengimpor file xps ke dalam dokumen pdf. |
| [XpsSaveOptions](./xpssaveoptions/) | Opsi penyimpanan untuk ekspor ke format Xps |
| [XslFoLoadOptions](./xslfoloadoptions/) | Mewakili opsi untuk memuat/mengimpor file XSL-FO ke dalam dokumen pdf. |
| [XslFoLoadOptions.ParsingErrorsHandlingTypes](./xslfoloadoptions.parsingerrorshandlingtypes/) | Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini mencantumkan strategi yang mungkin untuk menangani kesalahan pemformatan tersebut. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | <p> Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p> |
## Enums

| Enum | Deskripsi |
| --- | --- |
| [AFRelationship](./afrelationship/) | Enumerasi menjelaskan hubungan file terkait. |
| [AnnotationState](./annotationstate/) | Enumerasi status yang dapat ditetapkan pada anotasi asli. |
| [AnnotationStateModel](./annotationstatemodel/) | Model status yang sesuai dengan status anotasi. |
| [AnnotationType](./annotationtype/) | Enumerasi tipe anotasi. |
| [Artifact.ArtifactSubtype](./artifact.artifactsubtype/) | Enumerasi subtipe artefak yang mungkin. |
| [Artifact.ArtifactType](./artifact.artifacttype/) | Enumerasi tipe artefak yang mungkin. |
| [BlendMode](./blendmode/) | Enumerasi mode pencampuran. |
| [BorderCornerStyle](./bordercornerstyle/) | Menumerasikan gaya sudut border. |
| [BorderEffect](./bordereffect/) | Menjelaskan efek yang harus diterapkan pada border anotasi. |
| [BorderStyle](./borderstyle/) | Menjelaskan gaya border anotasi. |
| [BoxStyle](./boxstyle/) | Mewakili gaya untuk menggambar centang dalam kotak centang. |
| [CapStyle](./capstyle/) | Gaya ujung garis pada garis anotasi Ink. |
| [CaptionPosition](./captionposition/) | Enumerasi penempatan caption anotasi. |
| [CaretSymbol](./caretsymbol/) | Simbol yang akan dikaitkan dengan caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Warna yang termasuk dalam model warna CMYK. |
| [ColorSpace](./colorspace/) | Enumerasi ruang warna. |
| [ColorType](./colortype/) | Menentukan tipe warna elemen pada halaman. |
| [ColumnAdjustment](./columnadjustment/) | Menumerasikan tipe penyesuaian kolom. |
| [ContentDisposition](./contentdisposition/) | Header Content-Disposition protokol MIME. |
| [ConvertErrorAction](./converterroraction/) | Kelas ini mewakili aksi untuk kesalahan konversi. |
| [ConvertSoftMaskAction](./convertsoftmaskaction/) | Aksi ini mewakili tindakan untuk konversi gambar dengan soft mask. |
| [ConvertTransparencyAction](./converttransparencyaction/) | Kelas ini mewakili aksi untuk konversi transparansi. |
| [CoordinateOrigin](./coordinateorigin/) |  |
| [CryptoAlgorithm](./cryptoalgorithm/) | Mewakili tipe algoritma kriptografi yang digunakan dalam rutin enkripsi/dekripsi. |
| [CryptographicStandard](./cryptographicstandard/) | / * / * Namespace {@code Aspose.Pdf.Security } berisi kelas yang digunakan untuk enkripsi dan penandatanganan digital. / * / |
| [DefaultState](./defaultstate/) | Mewakili keadaan default dari lapisan PDF. |
| [DigestHashAlgorithm](./digesthashalgorithm/) | Mewakili tipe algoritma yang memetakan data ke sebuah "hash" |
| [Direction](./direction/) | Arah teks. |
| [DocMDPAccessPermissions](./docmdpaccesspermissions/) | Izin akses yang diberikan untuk dokumen ini. Nilai yang valid adalah: 1 - Tidak ada perubahan pada dokumen yang diizinkan; setiap perubahan pada dokumen akan membatalkan tanda tangan. 2 - Perubahan yang diizinkan meliputi mengisi formulir, menginstansiasi templat halaman, dan menandatangani; perubahan lain akan membatalkan tanda tangan. 3 - Perubahan yang diizinkan sama dengan nomor 2, serta pembuatan, penghapusan, dan modifikasi anotasi; perubahan lain akan membatalkan tanda tangan. |
| [DocSaveOptions.DocFormat](./docsaveoptions.docformat/) | Memungkinkan untuk menentukan format file .doc atau .docx. |
| [DocSaveOptions.RecognitionMode](./docsaveoptions.recognitionmode/) | Memungkinkan mengontrol bagaimana dokumen PDF dikonversi menjadi dokumen pengolah kata. Gunakan mode RecognitionMode.Textbox ketika dokumen hasil tidak akan banyak diedit lebih lanjut. Kotak teks mudah dimodifikasi ketika tidak banyak yang harus dilakukan. Gunakan mode RecognitionMode.Flow ketika dokumen output memerlukan penyuntingan lebih lanjut. Paragraf dan baris teks dalam mode aliran memungkinkan modifikasi teks yang mudah, tetapi objek pemformatan yang tidak didukung akan terlihat lebih buruk dibandingkan mode RecognitionMode.Textbox. |
| [EpubLoadOptions.EngineType](./epubloadoptions.enginetype/) |  |
| [EpubSaveOptions.RecognitionMode](./epubsaveoptions.recognitionmode/) | Ketika file PDF (yang biasanya memiliki tata letak tetap) dikonversi, mesin konversi berusaha melakukan pengelompokan dan analisis multi‑tingkat untuk mengembalikan maksud penulis dokumen asli dan menghasilkan hasil dalam tata letak aliran. Properti ini menyesuaikan konversi tersebut untuk metode pengenalan konten yang diinginkan. |
| [ExcelSaveOptions.ExcelFormat](./excelsaveoptions.excelformat/) |  |
| [ExplicitDestinationType](./explicitdestinationtype/) | Menumerasikan tipe tujuan eksplisit. |
| [ExtendedBoolean](./extendedboolean/) | Mewakili tipe boolean yang mendukung nilai Undefined. |
| [ExtractImageMode](./extractimagemode/) | Mendefinisikan mode berbeda yang dapat digunakan saat mengekstrak gambar dari dokumen. |
| [FileEncoding](./fileencoding/) | Pengkodean file terlampir. Nilai yang mungkin: Zip - file dikompresi dengan ZIP, None - file tidak dikompresi. |
| [FileIcon](./fileicon/) | Ikon yang akan digunakan untuk menampilkan anotasi. |
| [Fixup](./fixup/) | Enum ini mewakili tipe Fixup. |
| [FormType](./formtype/) | Enumerasi tipe kemungkinan Acro Form. |
| [FreeTextIntent](./freetextintent/) | Menumerasikan maksud anotasi teks bebas. |
| [HighlightingMode](./highlightingmode/) | Menumerasikan mode penyorotan anotasi, efek visual yang akan digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya. |
| [HorizontalAlignment](./horizontalalignment/) | Menjelaskan perataan horizontal. |
| [HtmlDocumentType](./htmldocumenttype/) | Mewakili enumerasi tipe dokumen Html. |
| [HtmlMediaType](./htmlmediatype/) | Menentukan tipe media yang mungkin digunakan selama rendering. |
| [IconCaptionPosition](./iconcaptionposition/) | Menjelaskan posisi ikon. |
| [ImageFileType](./imagefiletype/) | Menumerasikan tipe file gambar. |
| [ImageFilterType](./imagefiltertype/) | Enumerasi yang mewakili tipe filter gambar. |
| [ImageFormat](./imageformat/) | Enum ini mewakili format gambar. |
| [ImportFormat](./importformat/) | Menentukan format impor. |
| [Justification](./justification/) | Menumerasikan bentuk quadding (justifikasi) yang akan digunakan dalam menampilkan teks anotasi. |
| [LaunchActionOperation](./launchactionoperation/) | Menumerasikan operasi yang harus dilakukan dengan dokumen selama aksi peluncuran dijalankan. |
| [LettersPositioningMethods](./letterspositioningmethods/) | Ini menenumerasikan mode penempatan huruf dalam kata pada HTML hasil. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: kumpulan tipe skema pencahayaan. |
| [LineEnding](./lineending/) | Menumerasikan gaya akhir garis yang akan digunakan dalam menggambar garis. |
| [LineIntent](./lineintent/) | Menumerasikan maksud anotasi garis. |
| [LoadFormat](./loadformat/) | Menentukan format pemuatan. |
| [Measure.NumberFormat.FractionStyle](./measure.numberformat.fractionstyle/) | Nilai yang menunjukkan cara nilai pecahan ditampilkan. |
| [NumberingStyle](./numberingstyle/) | Enumerasi gaya penomoran halaman yang didukung untuk kelas PageLabel. |
| [OptimizedMemoryStream.SeekOrigin](./optimizedmemorystream.seekorigin/) | Menentukan posisi dalam aliran yang akan digunakan untuk pencarian. |
| [PageCoordinateType](./pagecoordinatetype/) | Menjelaskan tipe koordinat halaman. MediaBox = 0 CropBox = 1 |
| [PageLayout](./pagelayout/) | Menjelaskan tata letak halaman. |
| [PageMode](./pagemode/) | Kelas menjelaskan komponen yang digunakan pada halaman dokumen. |
| [ParagraphPositioningMode](./paragraphpositioningmode/) | Menentukan varian untuk menentukan lokasi elemen pada halaman. |
| [PasswordType](./passwordtype/) | Enum ini mewakili tipe kata sandi yang dikenal yang digunakan untuk dokumen PDF yang dilindungi kata sandi. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: kumpulan mode aktivasi anotasi 3D. |
| [PdfFormat](./pdfformat/) | Kelas ini mewakili format PDF. |
| [PdfVersion](./pdfversion/) | Enum ini mewakili versi file PDF. |
| [PolyIntent](./polyintent/) | Menumerasikan maksud anotasi poligon atau polyline. |
| [PredefinedAction](./predefinedaction/) | Mendefinisikan berbagai aksi yang dapat dipicu dari file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Mewakili posisi tanda di sudut halaman. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Mewakili posisi tanda registrasi pada halaman. |
| [ReplyType](./replytype/) | Menumerasikan jenis hubungan ("tipe balasan") antara anotasi dan yang ditentukan oleh InReplyTo. |
| [ReturnAction](./returnaction/) | Enum mewakili aksi alur kerja program dalam kasus pemanggilan metode {@code IWarningCallback.Warning(WarningInfo)}. |
| [Rotation](./rotation/) | Enumerasi nilai rotasi yang mungkin. |
| [SaveFormat](./saveformat/) | Menentukan format |
| [SaveOptions.HtmlBorderLineType](./saveoptions.htmlborderlinetype/) | Mewakili jenis garis yang dapat digunakan dalam dokumen hasil untuk menggambar batas atau garis lainnya |
| [SaveOptions.NodeLevelResourceType](./saveoptions.nodelevelresourcetype/) | menyebutkan jenis-jenis yang mungkin dari sumber eksternal yang disimpan |
| [StampIcon](./stampicon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |
| [SvgSaveOptions.SvgExternalImageType](./svgsaveoptions.svgexternalimagetype/) | menyebutkan jenis-jenis file gambar yang dapat disimpan sebagai sumber eksternal selama konversi PDF ke SVG |
| [TextAlignment](./textalignment/) | Penjajaran teks dalam anotasi. |
| [TextEditOptions.ClippingPathsProcessingMode](./texteditoptions.clippingpathsprocessingmode/) | Mode pemrosesan jalur pemotongan |
| [TextEditOptions.FontReplace](./texteditoptions.fontreplace/) | Perilaku penggantian font. |
| [TextEditOptions.LanguageTransformation](./texteditoptions.languagetransformation/) | Mode transformasi bahasa |
| [TextEditOptions.NoCharacterAction](./texteditoptions.nocharacteraction/) | Tindakan yang harus dilakukan jika font tidak mengandung karakter yang diperlukan |
| [TextRenderingMode](./textrenderingmode/) | Mode perenderan teks, Tmode, menentukan apakah menampilkan teks akan menyebabkan kontur glif digambar, diisi, digunakan sebagai batas pemotongan, atau kombinasi dari ketiganya. |
| [TextReplaceOptions.FontSizeAdjustment](./textreplaceoptions.fontsizeadjustment/) | Menentukan kebijakan tentang bagaimana ukuran font teks harus disesuaikan agar muat dalam area yang menampungnya. |
| [TextReplaceOptions.Scope](./textreplaceoptions.scope/) | Lingkup di mana operasi ganti teks diterapkan REPLACE_FIRST secara default. Opsi usang ini dipertahankan untuk kompatibilitas. Ini memengaruhi PdfContentEditor dan tidak berpengaruh pada TextFragmentAbsorber. |
| [VerticalAlignment](./verticalalignment/) | Enumerasi nilai-nilai penjajaran vertikal yang mungkin. |
| [WarningCallback.ReturnAction](./warningcallback.returnaction/) |  |
