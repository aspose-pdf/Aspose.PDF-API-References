---
title: Aspose.Pdf.Annotations
second_title: Aspose.PDF for .NET API Reference
description: Namespace Aspose.Pdf.Annotations menyediakan kelas untuk bekerja dengan berbagai jenis tindakan, tujuan, dan fitur lain dari dokumen yang secara tradisional disebut interaktif yang menyediakan cara bagi pengguna untuk berkomunikasi satu sama lain.
type: docs
weight: 50
url: /id/net/aspose.pdf.annotations/
---
Namespace **Aspose.Pdf.Annotations** menyediakan kelas untuk bekerja dengan berbagai jenis tindakan, tujuan, dan fitur lain dari dokumen yang secara tradisional disebut interaktif yang menyediakan cara bagi pengguna untuk berkomunikasi satu sama lain.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [ActionCollection](./actioncollection/) | Koleksi tindakan |
| [Annotation](./annotation/) | Kelas yang mewakili objek anotasi. |
| [AnnotationActionCollection](./annotationactioncollection/) | Mewakili koleksi tindakan anotasi. |
| [AnnotationCollection](./annotationcollection/) | Kelas yang mewakili koleksi anotasi. |
| [AnnotationSelector](./annotationselector/) | Kelas ini digunakan untuk memilih anotasi menggunakan ide template Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Kamus penampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual di halaman. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Mewakili anotasi Bleed Mark. |
| [Border](./border/) | Kelas yang mewakili karakteristik batas anotasi. |
| [CaretAnnotation](./caretannotation/) | Kelas yang mewakili anotasi Caret. |
| [Characteristics](./characteristics/) | Mewakili karakteristik anotasi |
| [CircleAnnotation](./circleannotation/) | Kelas yang mewakili anotasi Lingkaran. |
| [ColorBarAnnotation](./colorbarannotation/) | Kelas yang mewakili anotasi ColorBarAnnotation. Properti Color diabaikan, sebaliknya digunakan ColorsOfCMYK. Saat dibuat, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa bahwa persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) agar anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam hal ini, anotasi ada di halaman, tetapi tidak ditampilkan). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Kelas abstrak yang mewakili anotasi figur umum. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Mewakili jenis anotasi yang ditempatkan di sudut halaman cetak. |
| [CustomExplicitDestination](./customexplicitdestination/) | Mewakili tujuan eksplisit kustom. |
| [Dash](./dash/) | Kelas yang mewakili pola garis putus-putus. |
| [DefaultAppearance](./defaultappearance/) | Menggambarkan penampilan default dari bidang (font, ukuran teks, dan warna). |
| [DocumentActionCollection](./documentactioncollection/) | Kelas yang menggambarkan tindakan yang dilakukan pada beberapa tindakan dengan dokumen |
| [ExplicitDestination](./explicitdestination/) | Mewakili kelas dasar untuk tujuan eksplisit dalam dokumen PDF. |
| [FdfReader](./fdfreader/) | Kelas yang melakukan pembacaan format FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Kelas yang menggambarkan anotasi lampiran file. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan kontennya diperbesar cukup untuk muat sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan kotak pembatas dalam jendela di dimensi lainnya. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas yang diposisikan di tepi atas jendela dan konten halaman diperbesar cukup untuk muat seluruh lebar kotak pembatasnya dalam jendela. Nilai null untuk atas menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri yang diposisikan di tepi kiri jendela dan konten halaman diperbesar cukup untuk muat seluruh tinggi kotak pembatasnya dalam jendela. Nilai null untuk kiri menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| [FitExplicitDestination](./fitexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan kontennya diperbesar cukup untuk muat seluruh halaman dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan halaman dalam jendela di dimensi lainnya. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas yang diposisikan di tepi atas jendela dan konten halaman diperbesar cukup untuk muat seluruh lebar halaman dalam jendela. Nilai null untuk atas menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan kontennya diperbesar cukup untuk muat persegi panjang yang ditentukan oleh koordinat kiri, bawah, kanan, dan atas sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil dari keduanya, memusatkan persegi panjang dalam jendela di dimensi lainnya. Nilai null untuk salah satu parameter dapat menghasilkan perilaku yang tidak terduga. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri yang diposisikan di tepi kiri jendela dan konten halaman diperbesar cukup untuk muat seluruh tinggi halaman dalam jendela. Nilai null untuk kiri menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. |
| [FixedPrint](./fixedprint/) | Mewakili data cetak tetap dari Anotasi Watermark. |
| [FreeTextAnnotation](./freetextannotation/) | Mewakili anotasi teks bebas yang menampilkan teks langsung di halaman. Berbeda dengan anotasi teks biasa, anotasi teks bebas tidak memiliki keadaan terbuka atau tertutup; alih-alih ditampilkan dalam jendela pop-up, teks selalu terlihat. |
| [GoToAction](./gotoaction/) | Mewakili tindakan go-to yang mengubah tampilan ke tujuan tertentu (halaman, lokasi, dan faktor pembesaran). |
| [GoToRemoteAction](./gotoremoteaction/) | Mewakili tindakan go-to jarak jauh yang mirip dengan tindakan go-to biasa tetapi melompat ke tujuan di file PDF lain alih-alih file saat ini. |
| [GoToURIAction](./gotouriaction/) | Mewakili tindakan URI yang menyebabkan URI diselesaikan. |
| [HideAction](./hideaction/) | Mewakili tindakan sembunyi yang menyembunyikan atau menampilkan satu atau lebih anotasi di layar dengan mengatur atau menghapus bendera Tersembunyi mereka. |
| [HighlightAnnotation](./highlightannotation/) | Mewakili anotasi sorotan yang menyoroti rentang teks dalam dokumen. |
| [ImportDataAction](./importdataaction/) | Setelah pemanggilan tindakan impor-data, data Format Data Formulir (FDF) akan diimpor ke dalam formulir interaktif dokumen dari file yang ditentukan. |
| [InkAnnotation](./inkannotation/) | Mewakili "coretan" bebas yang terdiri dari satu atau lebih jalur terputus. |
| [JavascriptAction](./javascriptaction/) | Kelas yang mewakili tindakan javascript. |
| [LaunchAction](./launchaction/) | Mewakili tindakan peluncuran yang meluncurkan aplikasi atau membuka atau mencetak dokumen. |
| [LineAnnotation](./lineannotation/) | Kelas yang mewakili anotasi garis. |
| [LinkAnnotation](./linkannotation/) | Mewakili baik tautan hypertext ke tujuan lain dalam dokumen atau tindakan yang akan dilakukan. |
| [MarkupAnnotation](./markupannotation/) | Kelas abstrak yang mewakili anotasi markup. |
| [Measure](./measure/) | Kelas yang menggambarkan sistem koordinat Measure. |
| [MediaClip](./mediaclip/) | Kelas yang menggambarkan objek klip media dari rendisi. |
| [MediaClipData](./mediaclipdata/) | Kelas yang menggambarkan data klip media. |
| [MediaClipSection](./mediaclipsection/) | Kelas ini menggambarkan bagian klip media. |
| [MediaRendition](./mediarendition/) | Kelas yang menggambarkan rendisi media. |
| [MovieAnnotation](./movieannotation/) | Mewakili anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar. |
| [NamedAction](./namedaction/) | Mewakili tindakan bernama yang diharapkan didukung oleh aplikasi penampil PDF. |
| [NamedDestination](./nameddestination/) | Alih-alih didefinisikan langsung dengan sintaks eksplisit, tujuan dapat dirujuk secara tidak langsung melalui objek nama atau string byte. |
| [PageInformationAnnotation](./pageinformationannotation/) | Mewakili anotasi Informasi Halaman dalam dokumen PDF. Anotasi ini berisi nama file, nomor halaman, dan tanggal serta waktu pembuatan anotasi. |
| [PDF3DAnnotation](./pdf3dannotation/) | Kelas PDF3DAnnotation. Kelas ini tidak dapat diwarisi. |
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
| [PdfActionCollection](./pdfactioncollection/) | Kelas yang menggambarkan daftar tindakan. |
| [PolyAnnotation](./polyannotation/) | Kelas dasar abstrak untuk anotasi poli. |
| [PolygonAnnotation](./polygonannotation/) | Kelas yang mewakili anotasi poligon. |
| [PolylineAnnotation](./polylineannotation/) | Mewakili anotasi poligon yang mirip dengan poligon, kecuali bahwa titik pertama dan terakhir tidak terhubung secara implisit. |
| [PopupAnnotation](./popupannotation/) | Mewakili anotasi pop-up yang menampilkan teks dalam jendela pop-up untuk entri dan pengeditan. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Kelas abstrak yang mewakili anotasi tanda printer. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Menyediakan metode ekstensi untuk enumerasi [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Mewakili anotasi Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Mewakili anotasi Tanda Pendaftaran. |
| [Rendition](./rendition/) | Kelas yang menggambarkan objek rendisi dari RenditionAnnotation. |
| [RenditionAction](./renditionaction/) | Tindakan rendisi yang mengontrol pemutaran konten multimedia. |
| [RichMediaAnnotation](./richmediaannotation/) | Kelas yang menggambarkan RichMediaAnnotation yang memungkinkan menyematkan data video/audio ke dalam dokumen PDF. |
| [ScreenAnnotation](./screenannotation/) | Anotasi layar yang menentukan area halaman di mana klip media dapat diputar. |
| [SelectorRendition](./selectorrendition/) | Kelas yang menggambarkan rendisi pemilih. |
| [SoundAnnotation](./soundannotation/) | Mewakili anotasi suara yang berisi suara yang direkam dari mikrofon komputer atau diimpor dari file. |
| [SoundData](./sounddata/) | Mewakili data suara yang mendefinisikan suara yang akan diputar saat anotasi diaktifkan. |
| [SoundSampleData](./soundsampledata/) | Mewakili entri tambahan yang spesifik untuk objek suara (Bagian 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Kelas yang mewakili anotasi persegi. |
| [SquigglyAnnotation](./squigglyannotation/) | Mewakili anotasi squiggly yang muncul sebagai garis bawah bergerigi dalam teks dokumen. |
| [StampAnnotation](./stampannotation/) | Mewakili anotasi cap karet. Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan untuk terlihat seolah-olah dicap di halaman dengan cap karet. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Mewakili anotasi coret yang muncul sebagai coretan dalam teks dokumen. |
| [SubmitFormAction](./submitformaction/) | Kelas yang menggambarkan tindakan kirim-form. |
| [TextAnnotation](./textannotation/) | Mewakili anotasi teks yang merupakan 'catatan tempel' yang terpasang pada titik dalam dokumen PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Kelas dasar abstrak untuk anotasi markup teks. |
| [TextStyle](./textstyle/) | Kelas yang mewakili gaya teks dalam anotasi |
| [TrimMarkAnnotation](./trimmarkannotation/) | Mewakili anotasi Trim Mark. |
| [UnderlineAnnotation](./underlineannotation/) | Mewakili anotasi garis bawah yang muncul sebagai garis bawah dalam teks dokumen. |
| [WatermarkAnnotation](./watermarkannotation/) | Kelas yang menggambarkan objek anotasi Watermark. |
| [WidgetAnnotation](./widgetannotation/) | Kelas yang mewakili anotasi widget. |
| [XfdfReader](./xfdfreader/) | Kelas yang melakukan pembacaan format XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tanpa perubahan. Nilai zoom 0 memiliki arti yang sama dengan nilai null. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Mendefinisikan Visitor untuk mengunjungi berbagai anotasi dokumen. |
| [IAppointment](./iappointment/) | Mewakili antarmuka umum untuk tindakan dan tujuan. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Sekumpulan bendera yang menentukan berbagai karakteristik anotasi. |
| [AnnotationState](./annotationstate/) | Enumerasi status yang dapat diatur pada anotasi asli. |
| [AnnotationStateModel](./annotationstatemodel/) | Model status yang sesuai dengan status anotasi. |
| [AnnotationType](./annotationtype/) | Enumerasi jenis anotasi. |
| [BorderEffect](./bordereffect/) | Menggambarkan efek yang harus diterapkan pada batas anotasi. |
| [BorderStyle](./borderstyle/) | Menggambarkan gaya batas anotasi. |
| [CapStyle](./capstyle/) | Gaya akhir garis dari garis anotasi Ink. |
| [CaptionPosition](./captionposition/) | Enumerasi posisi keterangan anotasi. |
| [CaretSymbol](./caretsymbol/) | Simbol yang akan diasosiasikan dengan caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Warna yang termasuk dalam model warna CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Mengenumerasi jenis tujuan eksplisit. |
| [FileIcon](./fileicon/) | Ikon yang akan digunakan dalam menampilkan anotasi. |
| [FreeTextIntent](./freetextintent/) | Mengenumerasi niat dari anotasi teks bebas. |
| [HighlightingMode](./highlightingmode/) | Mengenumerasi mode penyorotan anotasi, efek visual yang akan digunakan saat tombol mouse ditekan atau ditahan di dalam area aktifnya. |
| [Justification](./justification/) | Mengenumerasi bentuk quadding (justifikasi) yang akan digunakan dalam menampilkan teks anotasi. |
| [LaunchActionOperation](./launchactionoperation/) | Mengenumerasi operasi yang dilakukan dengan dokumen selama eksekusi tindakan peluncuran. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: sekumpulan jenis skema pencahayaan. |
| [LineEnding](./lineending/) | Mengenumerasi gaya akhir garis yang akan digunakan dalam menggambar garis. |
| [LineIntent](./lineintent/) | Mengenumerasi niat dari anotasi garis. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: sekumpulan mode aktivasi anotasi 3D. |
| [PolyIntent](./polyintent/) | Mengenumerasi niat dari anotasi poligon atau polilin. |
| [PredefinedAction](./predefinedaction/) | Mendefinisikan berbagai tindakan yang dapat dipicu dari file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Mewakili posisi tanda di sudut halaman. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Mewakili posisi tanda pendaftaran di halaman. |
| [PrinterMarksKind](./printermarkskind/) | Menentukan jenis tanda printer yang akan ditambahkan ke dokumen. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: sekumpulan jenis mode render |
| [RenditionOperation](./renditionoperation/) | Operasi yang dilakukan saat tindakan dipicu. |
| [RenditionType](./renditiontype/) | Enumerasi yang menggambarkan kemungkinan jenis Rendisi. |
| [ReplyType](./replytype/) | Mengenumerasi jenis hubungan (jenis "balasan") antara anotasi dan satu yang ditentukan oleh InReplyTo. |
| [SoundEncoding](./soundencoding/) | Format pengkodean untuk data sampel suara. |
| [SoundIcon](./soundicon/) | Mengenumerasi ikon yang akan digunakan dalam menampilkan anotasi. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Format pengkodean untuk data sampel suara. |
| [StampIcon](./stampicon/) | Mengenumerasi ikon yang akan digunakan dalam menampilkan anotasi. |
| [TextIcon](./texticon/) | Mengenumerasi ikon yang akan digunakan dalam menampilkan anotasi. |