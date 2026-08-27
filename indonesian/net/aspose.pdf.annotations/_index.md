---
title: "Aspose.Pdf.Annotations"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Namespace Aspose.Pdf.Annotations menyediakan kelas untuk bekerja dengan berbagai jenis tujuan aksi dan fitur lain dari dokumen yang secara tradisional disebut interaktif, menyediakan cara bagi pengguna untuk berinteraksi dengannya."
type: docs
weight: 50
url: /id/net/aspose.pdf.annotations/
---
**Aspose.Pdf.Annotations** namespace menyediakan kelas untuk bekerja dengan berbagai jenis aksi, tujuan, dan fitur lain dari dokumen yang secara tradisional disebut interaktif, memberikan cara bagi pengguna untuk berinteraksi dengannya.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [ActionCollection](./actioncollection/) | Koleksi aksi |
| [Annotation](./annotation/) | Kelas yang merepresentasikan objek anotasi. |
| [AnnotationActionCollection](./annotationactioncollection/) | Mewakili koleksi aksi anotasi. |
| [AnnotationCollection](./annotationcollection/) | Kelas yang merepresentasikan koleksi anotasi. |
| [AnnotationSelector](./annotationselector/) | Kelas ini digunakan untuk memilih anotasi menggunakan ide template Visitor. |
| [AppearanceDictionary](./appearancedictionary/) | Kamus tampilan anotasi yang menentukan bagaimana anotasi akan ditampilkan secara visual pada halaman. |
| [BleedMarkAnnotation](./bleedmarkannotation/) | Mewakili anotasi Bleed Mark. |
| [Border](./border/) | Kelas yang merepresentasikan karakteristik batas anotasi. |
| [CaretAnnotation](./caretannotation/) | Kelas yang merepresentasikan anotasi Caret. |
| [Characteristics](./characteristics/) | Mewakili karakteristik anotasi |
| [CircleAnnotation](./circleannotation/) | Kelas yang merepresentasikan anotasi Lingkaran. |
| [ColorBarAnnotation](./colorbarannotation/) | Kelas yang merepresentasikan anotasi ColorBarAnnotation. Properti Color diabaikan, sebagai gantinya digunakan warna ColorsOfCMYK. Pada pembuatan, rasio lebar dan tinggi menentukan orientasi anotasi - horizontal atau vertikal. Selanjutnya, diperiksa apakah persegi panjang anotasi berada di luar TrimBox, dan jika tidak, maka dipindahkan ke lokasi terdekat di luar TrimBox, dengan mempertimbangkan orientasi anotasi. Dimungkinkan untuk mengurangi lebar (tinggi) sehingga anotasi muat di luar TrimBox. Jika tidak ada ruang untuk tata letak, lebar/tinggi dapat diatur menjadi nol (dalam kasus ini, anotasi tetap ada di halaman, tetapi tidak ditampilkan). |
| [CommonFigureAnnotation](./commonfigureannotation/) | Kelas abstrak yang merepresentasikan anotasi gambar umum. |
| [CornerPrinterMarkAnnotation](./cornerprintermarkannotation/) | Mewakili jenis anotasi yang ditempatkan di sudut-sudut halaman yang dicetak. |
| [CustomExplicitDestination](./customexplicitdestination/) | Mewakili tujuan eksplisit khusus. |
| [Dash](./dash/) | Kelas yang merepresentasikan pola garis putus-putus. |
| [DefaultAppearance](./defaultappearance/) | Menjelaskan tampilan default bidang (font, ukuran teks, dan warna). |
| [DocumentActionCollection](./documentactioncollection/) | Kelas yang menjelaskan aksi yang dilakukan pada beberapa aksi dengan dokumen. |
| [ExplicitDestination](./explicitdestination/) | Merepresentasikan kelas dasar untuk tujuan eksplisit dalam dokumen PDF. |
| [FdfReader](./fdfreader/) | Kelas yang melakukan pembacaan format FDF. |
| [FileAttachmentAnnotation](./fileattachmentannotation/) | Kelas yang menjelaskan anotasi lampiran file. |
| [FitBExplicitDestination](./fitbexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan kotak pembatasnya sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan kotak pembatas dalam jendela pada dimensi lainnya. |
| [FitBHExplicitDestination](./fitbhexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar penuh kotak pembatasnya dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut tetap dipertahankan tanpa perubahan. |
| [FitBVExplicitDestination](./fitbvexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi penuh kotak pembatasnya dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut tetap dipertahankan tanpa perubahan. |
| [FitExplicitDestination](./fitexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan seluruh halaman dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan halaman dalam jendela pada dimensi lainnya. |
| [FitHExplicitDestination](./fithexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar penuh halaman dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut tetap dipertahankan tanpa perubahan. |
| [FitRExplicitDestination](./fitrexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan persegi panjang yang ditentukan oleh koordinat kiri, bawah, kanan, dan atas sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan persegi panjang dalam jendela pada dimensi lainnya. Nilai null untuk salah satu parameter dapat menghasilkan perilaku yang tidak dapat diprediksi. |
| [FitVExplicitDestination](./fitvexplicitdestination/) | Merepresentasikan tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi penuh halaman dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut tetap dipertahankan tanpa perubahan. |
| [FixedPrint](./fixedprint/) | Merepresentasikan data cetak tetap dari Anotasi Watermark. |
| [FreeTextAnnotation](./freetextannotation/) | Merepresentasikan anotasi teks bebas yang menampilkan teks secara langsung pada halaman. Tidak seperti anotasi teks biasa, anotasi teks bebas tidak memiliki keadaan terbuka atau tertutup; alih-alih ditampilkan dalam jendela pop-up, teks selalu terlihat. |
| [GoToAction](./gotoaction/) | Merepresentasikan aksi pergi-ke yang mengubah tampilan ke tujuan yang ditentukan (halaman, lokasi, dan faktor pembesaran). |
| [GoToRemoteAction](./gotoremoteaction/) | Merepresentasikan aksi pergi-ke remote yang mirip dengan aksi pergi-ke biasa tetapi melompat ke tujuan dalam file PDF lain alih-alih file saat ini. |
| [GoToURIAction](./gotouriaction/) | Merepresentasikan aksi URI yang menyebabkan URI diselesaikan. |
| [HideAction](./hideaction/) | Merepresentasikan aksi sembunyikan yang menyembunyikan atau menampilkan satu atau lebih anotasi di layar dengan mengatur atau menghapus flag Hidden mereka. |
| [HighlightAnnotation](./highlightannotation/) | Merepresentasikan anotasi sorot yang menyorot rentang teks dalam dokumen. |
| [ImportDataAction](./importdataaction/) | Saat pemanggilan aksi import-data, data Forms Data Format (FDF) akan diimpor ke dalam formulir interaktif dokumen dari file yang ditentukan. |
| [InkAnnotation](./inkannotation/) | Merepresentasikan "scribble" tangan bebas yang terdiri dari satu atau lebih jalur terpisah. |
| [JavascriptAction](./javascriptaction/) | Kelas yang merepresentasikan aksi javascript. |
| [LaunchAction](./launchaction/) | Mewakili aksi peluncuran yang meluncurkan aplikasi atau membuka atau mencetak dokumen. |
| [LineAnnotation](./lineannotation/) | Kelas yang mewakili anotasi garis. |
| [LinkAnnotation](./linkannotation/) | Mewakili baik tautan hiperteks ke tujuan di tempat lain dalam dokumen atau aksi yang harus dilakukan. |
| [MarkupAnnotation](./markupannotation/) | Kelas abstrak yang mewakili anotasi markup. |
| [Measure](./measure/) | Kelas yang menjelaskan sistem koordinat Measure. |
| [MediaClip](./mediaclip/) | Kelas yang menjelaskan objek klip media dari rendering. |
| [MediaClipData](./mediaclipdata/) | Kelas yang menjelaskan data klip media. |
| [MediaClipSection](./mediaclipsection/) | Kelas ini menjelaskan bagian klip Media. |
| [MediaRendition](./mediarendition/) | Kelas yang menjelaskan rendering media. |
| [MovieAnnotation](./movieannotation/) | Mewakili anotasi film yang berisi grafik animasi dan suara yang akan ditampilkan di layar komputer dan melalui speaker. Ketika anotasi diaktifkan, film diputar. |
| [NamedAction](./namedaction/) | Mewakili aksi bernama yang diharapkan didukung oleh aplikasi penampil PDF. |
| [NamedDestination](./nameddestination/) | Alih-alih didefinisikan secara langsung dengan sintaks eksplisit, sebuah tujuan dapat dirujuk secara tidak langsung melalui objek nama atau string byte. |
| [PageInformationAnnotation](./pageinformationannotation/) | Mewakili anotasi Informasi Halaman dalam dokumen PDF. Anotasi ini berisi nama file, nomor halaman, serta tanggal dan waktu pembuatan anotasi. |
| [PDF3DAnnotation](./pdf3dannotation/) | Kelas PDF3DAnnotation. Kelas ini tidak dapat diwariskan. |
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
| [PdfAction](./pdfaction/) | Mewakili Aksi dalam dokumen PDF |
| [PdfActionCollection](./pdfactioncollection/) | Kelas menjelaskan daftar tindakan. |
| [PolyAnnotation](./polyannotation/) | Kelas dasar abstrak untuk anotasi poly-. |
| [PolygonAnnotation](./polygonannotation/) | Kelas yang mewakili anotasi poligon. |
| [PolylineAnnotation](./polylineannotation/) | Mewakili anotasi polyline yang mirip dengan poligon, kecuali bahwa vertex pertama dan terakhir tidak terhubung secara implisit. |
| [PopupAnnotation](./popupannotation/) | Mewakili anotasi pop-up yang menampilkan teks dalam jendela pop-up untuk entri dan penyuntingan. |
| [PrinterMarkAnnotation](./printermarkannotation/) | Kelas abstrak yang mewakili anotasi tanda printer. |
| [PrinterMarksKindExtensions](./printermarkskindextensions/) | Menyediakan metode ekstensi untuk enumerasi [`PrinterMarksKind`](../aspose.pdf.annotations/printermarkskind/). |
| [RedactionAnnotation](./redactionannotation/) | Mewakili anotasi Redact. |
| [RegistrationMarkAnnotation](./registrationmarkannotation/) | Mewakili anotasi Tanda Registrasi. |
| [Rendition](./rendition/) | Kelas yang menjelaskan objek rendition dari RendtionAnnotation. |
| [RenditionAction](./renditionaction/) | Aksi rendition yang mengontrol pemutaran konten multimedia. |
| [RichMediaAnnotation](./richmediaannotation/) | Kelas menjelaskan RichMediaAnnotation yang memungkinkan penyematan data video/audio ke dalam dokumen PDF. |
| [ScreenAnnotation](./screenannotation/) | Anotasi layar yang menentukan wilayah halaman tempat klip media dapat diputar. |
| [SelectorRendition](./selectorrendition/) | Kelas menjelaskan selector rendition. |
| [SoundAnnotation](./soundannotation/) | Mewakili anotasi suara yang berisi suara yang direkam dari mikrofon komputer atau diimpor dari file. |
| [SoundData](./sounddata/) | Mewakili data suara yang mendefinisikan suara yang akan diputar ketika anotasi diaktifkan. |
| [SoundSampleData](./soundsampledata/) | Mewakili entri tambahan yang spesifik untuk objek suara (Bagian 9.2 PDF1-7) |
| [SquareAnnotation](./squareannotation/) | Kelas yang mewakili anotasi kotak. |
| [SquigglyAnnotation](./squigglyannotation/) | Mewakili anotasi squiggly yang muncul sebagai garis bawah bergerigi dalam teks dokumen. |
| [StampAnnotation](./stampannotation/) | Mewakili anotasi stempel karet. Jenis anotasi ini menampilkan teks atau grafik yang dimaksudkan terlihat seolah-olah dicap pada halaman dengan stempel karet. |
| [StrikeOutAnnotation](./strikeoutannotation/) | Mewakili anotasi coret yang muncul sebagai coretan dalam teks dokumen. |
| [SubmitFormAction](./submitformaction/) | Kelas yang menjelaskan aksi submit-form. |
| [TextAnnotation](./textannotation/) | Mewakili anotasi teks yang merupakan 'catatan tempel' yang terpasang pada suatu titik dalam dokumen PDF. |
| [TextMarkupAnnotation](./textmarkupannotation/) | Kelas dasar abstrak untuk anotasi markup teks. |
| [TextStyle](./textstyle/) | Kelas yang mewakili gaya teks dalam anotasi |
| [TrimMarkAnnotation](./trimmarkannotation/) | Mewakili anotasi Trim Mark. |
| [UnderlineAnnotation](./underlineannotation/) | Mewakili anotasi garis bawah yang muncul sebagai garis bawah dalam teks dokumen. |
| [WatermarkAnnotation](./watermarkannotation/) | Kelas yang menjelaskan objek anotasi Watermark. |
| [WidgetAnnotation](./widgetannotation/) | Kelas yang mewakili anotasi widget. |
| [XfdfReader](./xfdfreader/) | Kelas yang melakukan pembacaan format XFDF. |
| [XYZExplicitDestination](./xyzexplicitdestination/) | Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan isi halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null. |
## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [IAnnotationVisitor](./iannotationvisitor/) | Mendefinisikan Visitor untuk mengunjungi berbagai anotasi dokumen. |
| [IAppointment](./iappointment/) | Mewakili antarmuka umum untuk aksi dan tujuan. |
## Enumerasi

| Enumerasi | Deskripsi |
| --- | --- |
| [AnnotationFlags](./annotationflags/) | Sekumpulan flag yang menentukan berbagai karakteristik anotasi. |
| [AnnotationState](./annotationstate/) | Enumerasi status yang dapat ditetapkan pada anotasi asli. |
| [AnnotationStateModel](./annotationstatemodel/) | Model status yang sesuai dengan status anotasi. |
| [AnnotationType](./annotationtype/) | Enumerasi tipe anotasi. |
| [BorderEffect](./bordereffect/) | Menjelaskan efek yang harus diterapkan pada batas anotasi. |
| [BorderStyle](./borderstyle/) | Menjelaskan gaya batas anotasi. |
| [CapStyle](./capstyle/) | Gaya akhir garis pada anotasi Ink. |
| [CaptionPosition](./captionposition/) | Enumerasi posisi keterangan anotasi. |
| [CaretSymbol](./caretsymbol/) | Simbol yang akan dikaitkan dengan caret. |
| [ColorsOfCMYK](./colorsofcmyk/) | Warna yang termasuk dalam model warna CMYK. |
| [ExplicitDestinationType](./explicitdestinationtype/) | Menumerasikan tipe-tipe tujuan eksplisit. |
| [FileIcon](./fileicon/) | Ikon yang akan digunakan untuk menampilkan anotasi. |
| [FreeTextIntent](./freetextintent/) | Menumerasikan maksud anotasi teks bebas. |
| [HighlightingMode](./highlightingmode/) | Menumerasikan mode penyorotan anotasi, efek visual yang digunakan ketika tombol mouse ditekan atau ditahan di dalam area aktifnya. |
| [Justification](./justification/) | Menumerasikan bentuk quadding (perataan) yang akan digunakan dalam menampilkan teks anotasi. |
| [LaunchActionOperation](./launchactionoperation/) | Menumerasikan operasi yang akan dilakukan pada dokumen selama eksekusi aksi peluncuran. |
| [LightingSchemeType](./lightingschemetype/) | Enum LightingSchemeType: sekumpulan tipe skema pencahayaan. |
| [LineEnding](./lineending/) | Menumerasikan gaya akhir baris yang akan digunakan saat menggambar garis. |
| [LineIntent](./lineintent/) | Menumerasikan maksud anotasi garis. |
| [PDF3DActivation](./pdf3dactivation/) | Enum PDF3DActivation: sekumpulan mode aktivasi anotasi 3D. |
| [PolyIntent](./polyintent/) | Menumerasikan maksud anotasi poligon atau polyline. |
| [PredefinedAction](./predefinedaction/) | Mendefinisikan berbagai tindakan yang dapat dipicu dari file PDF. |
| [PrinterMarkCornerPosition](./printermarkcornerposition/) | Mewakili posisi tanda di sudut halaman. |
| [PrinterMarkSidePosition](./printermarksideposition/) | Mewakili posisi tanda registrasi pada halaman. |
| [PrinterMarksKind](./printermarkskind/) | Menentukan jenis tanda printer yang akan ditambahkan ke dokumen. |
| [RenderModeType](./rendermodetype/) | Enum RenderModeType: sekumpulan jenis mode render |
| [RenditionOperation](./renditionoperation/) | Operasi yang akan dilakukan ketika tindakan dipicu. |
| [RenditionType](./renditiontype/) | Enumerasi menjelaskan jenis-jenis Rendition yang mungkin. |
| [ReplyType](./replytype/) | Menumerasikan jenis hubungan ("tipe balasan") antara anotasi dan yang ditentukan oleh InReplyTo. |
| [RichTextFontStyles](./richtextfontstyles/) | Opsi untuk menata fragmen teks dalam RichText. |
| [SoundEncoding](./soundencoding/) | Format enkoding untuk data contoh. |
| [SoundIcon](./soundicon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |
| [SoundSampleDataEncodingFormat](./soundsampledataencodingformat/) | Format enkoding untuk data contoh suara. |
| [StampIcon](./stampicon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |
| [TextIcon](./texticon/) | Menumerasikan ikon yang akan digunakan dalam menampilkan anotasi. |


