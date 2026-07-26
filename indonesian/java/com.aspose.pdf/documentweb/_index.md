---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas DocumentWeb"
type: docs
weight: 1170
url: /id/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

Mewakili kelas DocumentWeb

## Fields

| Field | Deskripsi |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Ini terjadi ketika font menggantikan font lain dalam dokumen. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | Menginisialisasi DocumentWeb kosong. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | Menginisialisasi DocumentWeb kosong. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [afterImport](#afterImport--) | Enumerasi semua anotasi yang terdaftar dan panggil AfterImport untuk masing-masing. |
| [bindXml](#bindXml-java.io.InputStream-) | Mengikat xml ke dokumen |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Mengikat xml/xsl ke dokumen |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Mengikat xml/xsl ke dokumen |
| [bindXml](#bindXml-java.lang.String-) | Mengikat xml ke dokumen |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Mengikat xml/xsl ke dokumen |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Mengubah kata sandi dokumen. |
| [check](#check-boolean-) | Memvalidasi dokumen. |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Mengonversi dokumen dengan menerapkan Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Mengonversi dokumen dengan menerapkan Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Mengonversi dokumen dengan menerapkan Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Mengonversi dokumen dengan menerapkan Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Mengonversi aliran dalam format sumber menjadi aliran dalam format tujuan. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Mengonversi aliran dalam format sumber menjadi berkas tujuan dalam format tujuan. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Mengonversi dokumen dan menyimpan kesalahan ke aliran yang ditentukan. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Mengonversi dokumen menggunakan opsi konversi yang ditentukan |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Mengonversi berkas sumber dalam format sumber menjadi aliran dalam format tujuan. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Mengonversi berkas sumber dalam format sumber menjadi berkas tujuan dalam format tujuan. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Mengonversi dokumen dan menyimpan kesalahan ke aliran yang ditentukan. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi. |
| [decrypt](#decrypt--) | Mendekripsi dokumen. |
| [dispose](#dispose--) | Usang. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Mengenkripsi dokumen. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Mengekspor semua anotasi dokumen ke aliran. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Mengekspor semua anotasi dokumen ke file XFDF |
| [flatten](#flatten--) | Menghapus semua bidang (dan anotasi) dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Menghapus semua bidang dari dokumen dan menempatkan nilainya sebagai gantinya. |
| [flattenTransparency](#flattenTransparency--) | Mengganti konten transparan dengan grafik raster dan vektor yang tidak transparan. |
| [freeMemory](#freeMemory--) | Menghapus memori |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Pemberitahuan tentang font yang hilang saat memproses dokumen. |
| [getActions](#getActions--) | Mendapatkan tindakan dokumen. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Memungkinkan menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen. |
| [getBackground](#getBackground--) | Mendapatkan warna latar belakang dokumen. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Mengembalikan nilai item dari kamus katalog. |
| [getCollection](#getCollection--) | Mendapatkan koleksi dokumen. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Mendapatkan pengaturan keamanan jika dokumen dienkripsi. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Mendapatkan penangan keamanan khusus. |
| [getDefaultCopier](#getDefaultCopier--) | Mengembalikan penyalin yang digunakan untuk menyalin halaman ke dokumen ini. |
| [getDestinations](#getDestinations--) | Usang. |
| [getDirection](#getDirection--) | Mendapatkan urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [getDuplex](#getDuplex--) | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Mendapatkan koleksi file yang disematkan ke dokumen. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. |
| [getEngineDoc](#getEngineDoc--) | Instansi IPdfDocument yang digunakan untuk mengakses struktur internal dokumen. |
| [getFileName](#getFileName--) | Nama file PDF yang menyebabkan dokumen ini |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Mendapatkan dan mengatur batas ukuran berkas untuk memuat seluruh berkas ke dalam memori. |
| [getForm](#getForm--) | Mendapatkan Acro Form dokumen. |
| [getId](#getId--) | Mendapatkan ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. |
| [getInfo](#getInfo--) | Mendapatkan info dokumen. |
| [getJavaScript](#getJavaScript--) | Koleksi JavaScript tingkat dokumen. |
| [getLogicalStructure](#getLogicalStructure--) | Mendapatkan struktur logis dokumen. |
| [getMetadata](#getMetadata--) | Metadata dokumen. |
| [getMetadataStream](#getMetadataStream--) | Hanya untuk penggunaan internal! |
| [getNamedDestinations](#getNamedDestinations--) | Koleksi Named Destination dalam dokumen. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Mendapatkan mode halaman, yang menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
| [getObjectById](#getObjectById-java.lang.String-) | Mendapatkan objek dengan ID yang ditentukan dalam dokumen. |
| [getOpenAction](#getOpenAction--) | Mendapatkan aksi yang dilakukan saat pembukaan dokumen. |
| [getOptimizeSize](#getOptimizeSize--) | Mendapatkan flag optimisasi. |
| [getOutlines](#getOutlines--) | Mendapatkan outline dokumen. |
| [getOutputIntents](#getOutputIntents--) | Mendapatkan koleksi Output intents dalam dokumen. |
| [getPageInfo](#getPageInfo--) | Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [getPageLabels](#getPageLabels--) | Mendapatkan label halaman dalam dokumen. |
| [getPageLayout](#getPageLayout--) | Mendapatkan tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [getPageMode](#getPageMode--) | Mendapatkan mode halaman, yang menentukan cara dokumen ditampilkan saat dibuka. |
| [getPages](#getPages--) | Mendapatkan koleksi halaman dokumen. |
| [getPdfFormat](#getPdfFormat--) | Mendapatkan format PDF. |
| [getPermissions](#getPermissions--) | Mendapatkan izin dokumen. |
| [getPrintScaling](#getPrintScaling--) | Mendapatkan opsi penanganan skala cetak yang digunakan saat mencetak file dari dialog cetak. |
| [getTaggedContent](#getTaggedContent--) | Mendapatkan akses ke konten TaggedPdf. |
| [getVersion](#getVersion--) | Mendapatkan versi PDF dari header file PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Dapatkan metadata XMP dari dokumen. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Memeriksa apakah dokumen PDF saat ini telah disimpan dengan pembaruan inkremental. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Mengimpor anotasi dari aliran ke dokumen. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Mengimpor anotasi dari file XFDF ke dokumen. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flag yang memberi tahu tentang penggantian font yang hilang. |
| [isCenterWindow](#isCenterWindow--) | Mendapatkan flag yang menentukan apakah posisi jendela dokumen akan dipusatkan pada layar. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Mendapatkan flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengaktifkan pencatatan notifikasi. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori. |
| [isEncrypted](#isEncrypted--) | Mendapatkan status enkripsi dokumen. |
| [isFitWindow](#isFitWindow--) | Mendapatkan flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Melempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan |
| [isHideMenubar](#isHideMenubar--) | Mendapatkan flag yang menentukan apakah menu bar harus disembunyikan ketika dokumen aktif. |
| [isHideToolBar](#isHideToolBar--) | Mendapatkan flag yang menentukan apakah toolbar harus disembunyikan ketika dokumen aktif. |
| [isHideWindowUI](#isHideWindowUI--) | Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. |
| [isLicensed](#isLicensed--) | Mendapatkan status lisensi sistem. |
| [isLinearized](#isLinearized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Secara default metode save menutup aliran internal dan melepaskan sumber daya memori. |
| [isPdfaCompliant](#isPdfaCompliant--) | Mendapatkan status kepatuhan dokumen pdfa. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Mendapatkan apakah dokumen mematuhi pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Mendapatkan flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Memeriksa apakah dokumen memerlukan pemanggilan metode Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Secara default proses validasi pdfa diperlukan untuk memperbarui atau menghapus data yang mematuhi pdfa jika beberapa aturan dilanggar. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Mendapatkan atau mengatur apakah dokumen mematuhi pdfa. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Memuat sebuah file, mengkonversinya menjadi PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Menggabungkan dokumen. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Menggabungkan dokumen. |
| [merge](#merge-com.aspose.pdf.Document...-) | Menggabungkan dokumen. |
| [merge](#merge-java.lang.String...-) | Menggabungkan file pdf. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Menggabungkan dokumen. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Menggabungkan dokumen. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Menggabungkan dokumen. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Menggabungkan file pdf. |
| [optimize](#optimize--) | Linearize dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data halaman tiba ketika data untuk sebuah halaman dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. |
| [optimizeResources](#optimizeResources--) | Optimalkan sumber daya dalam dokumen: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Metode internal |
| [processParagraphs](#processParagraphs--) | Menyimpan dokumen ke dalam generator. |
| [removeMetadata](#removeMetadata--) | Menghapus metadata dari dokumen. |
| [removePdfaCompliance](#removePdfaCompliance--) | Hapus kepatuhan pdfa dari dokumen |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Hapus kepatuhan pdfUa dari dokumen |
| [repair](#repair--) | Memperbaiki dokumen yang rusak. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Memperbaiki dokumen yang rusak. |
| [resumeUpdate](#resumeUpdate--) | melanjutkan pembaruan dokumen |
| [save](#save--) | Simpan dokumen secara inkremental (misalnya. |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen ke aliran respons dengan opsi penyimpanan. |
| [save](#save-java.io.OutputStream-) | Menyimpan dokumen ke dalam stream. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Menyimpan dokumen dengan nama baru beserta format file. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [save](#save-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen dengan opsi penyimpanan. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | Hanya untuk penggunaan internal |
| [save](#save-java.lang.String-) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Menyimpan dokumen dengan nama baru beserta format file. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveXml](#saveXml-java.lang.String-) | Simpan dokumen ke XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Pemberitahuan tentang font yang hilang saat memproses dokumen. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Mengatur flag untuk mengganti font yang hilang. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Memungkinkan menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen. |
| [setBackground](#setBackground-java.awt.Color-) | Mengatur warna latar belakang dokumen. |
| [setCenterWindow](#setCenterWindow-boolean-) | Mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Mengatur koleksi dokumen. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Mendapatkan parameter konversi untuk konverter pdf/ua (Hanya konversi Metadata dan Katalog Dokumen jika diatur true). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Mengatur batas ukuran file untuk memuat seluruh file ke memori ke nilai default sebesar 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [setDuplex](#setDuplex-int-) | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah mengaktifkan pencatatan notifikasi. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Mendapatkan dan mengatur batas ukuran berkas untuk memuat seluruh berkas ke dalam memori. |
| [setFitWindow](#setFitWindow-boolean-) | Mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Melempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan |
| [setHideMenubar](#setHideMenubar-boolean-) | Mengatur flag yang menentukan apakah bilah menu harus disembunyikan saat dokumen aktif. |
| [setHideToolBar](#setHideToolBar-boolean-) | Mengatur flag yang menentukan apakah bilah alat harus disembunyikan saat dokumen aktif. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. |
| [setLinearized](#setLinearized-boolean-) | Mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Secara default metode save menutup aliran internal dan melepaskan sumber daya memori. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Mengatur mode halaman, menentukan bagaimana menampilkan dokumen saat keluar dari mode layar penuh. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Mengatur aksi yang dilakukan saat membuka dokumen. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Mengatur flag optimisasi. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Mengatur informasi halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Mengatur mode halaman, menentukan bagaimana dokumen harus ditampilkan saat dibuka. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Mengatur flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input. |
| [setPrintScaling](#setPrintScaling-int-) | Mengatur opsi penanganan skala cetak yang akan digunakan saat mencetak file dari dialog cetak. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Secara default proses validasi pdfa diperlukan untuk memperbarui atau menghapus pdfa jika beberapa aturan dilanggar. |
| [setTitle](#setTitle-java.lang.String-) | Atur Judul untuk Dokumen Pdf |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Atur metadata XMP dokumen. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Mendapatkan atau mengatur apakah dokumen mematuhi pdfa. |
| [suppressUpdate](#suppressUpdate--) | Menekan pembaruan data konten untuk semua halaman. Konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validasi dokumen ke dalam file yang ditentukan. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Validasi dokumen ke dalam file yang ditentukan. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validasi dokumen ke dalam file yang ditentukan. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Ini terjadi ketika font menggantikan font lain dalam dokumen.

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.lang.String-}
Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
Menginisialisasi DocumentWeb kosong.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
Menginisialisasi DocumentWeb kosong.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumerasi semua anotasi yang terdaftar dan panggil AfterImport untuk masing-masing.

### bindXml {#bindXml-java.io.InputStream-}
Mengikat xml ke dokumen

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Mengikat xml/xsl ke dokumen

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Mengikat xml/xsl ke dokumen

### bindXml {#bindXml-java.lang.String-}
Mengikat xml ke dokumen

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Mengikat xml/xsl ke dokumen

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Mengubah kata sandi dokumen.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Memvalidasi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| doRepair |  | Jika true, masalah yang ditemukan akan diperbaiki. |

**Returns:**
nilai boolean True - jika dokumen diperbaiki; jika tidak, false.

### close {#close--}
```
public void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Mengonversi dokumen dengan menerapkan Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Mengonversi dokumen dengan menerapkan Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Mengonversi dokumen dengan menerapkan Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Mengonversi dokumen dengan menerapkan Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Mengonversi aliran dalam format sumber menjadi aliran dalam format tujuan.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Mengonversi aliran dalam format sumber menjadi berkas tujuan dalam format tujuan.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Mengonversi dokumen dan menyimpan kesalahan ke aliran yang ditentukan.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Mengonversi dokumen menggunakan opsi konversi yang ditentukan

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Mengonversi berkas sumber dalam format sumber menjadi aliran dalam format tujuan.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Mengonversi berkas sumber dalam format sumber menjadi berkas tujuan dalam format tujuan.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Mengonversi dokumen dan menyimpan kesalahan ke aliran yang ditentukan.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Mengonversi halaman ke PNG untuk aliran gambar DSR, OMR, OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi.

### decrypt {#decrypt--}
```
public void decrypt()
```

Mendekripsi dokumen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Usang.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Mengenkripsi dokumen.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Mengekspor semua anotasi dokumen ke aliran.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Mengekspor semua anotasi dokumen ke file XFDF

### flatten {#flatten--}
```
public void flatten()
```

Menghapus semua bidang (dan anotasi) dari dokumen dan menempatkan nilai mereka sebagai gantinya.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Menghapus semua bidang dari dokumen dan menempatkan nilainya sebagai gantinya.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Mengganti konten transparan dengan grafik raster dan vektor yang tidak transparan.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Menghapus memori

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Pemberitahuan tentang font yang hilang saat memproses dokumen.

**Returns:**
ADocument.AbsentFontHandler instance

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

Mendapatkan tindakan dokumen.

**Returns:**
DocumentActionCollection objek

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Memungkinkan menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen.

**Returns:**
nilai boolean

### getBackground {#getBackground--}
```
public Color getBackground()
```

Mendapatkan warna latar belakang dokumen.

**Returns:**
java.awt.Color objek

### getCatalogValue {#getCatalogValue-java.lang.String-}
Mengembalikan nilai item dari kamus katalog.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Mendapatkan koleksi dokumen.

**Returns:**
Collection objek

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Mendapatkan pengaturan keamanan jika dokumen dienkripsi.

**Returns:**
CryptoAlgorithm elemen atau null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Mendapatkan penangan keamanan khusus.

**Returns:**
ICustomSecurityHandler instansi

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Mengembalikan penyalin yang digunakan untuk menyalin halaman ke dokumen ini.

**Returns:**
Copier objek

### getDestinations {#getDestinations--}
```
@Deprecated public DestinationCollection getDestinations()
```

Usang.

**Returns:**
DestinationCollection objek

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Mendapatkan urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri).

**Returns:**
Direction elemen

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak.

**Returns:**
PrintDuplex elemen

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Mendapatkan koleksi file yang disematkan ke dokumen.

**Returns:**
EmbeddedFileCollection objek

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true.

**Returns:**
nilai boolean

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan.

**Returns:**
nilai boolean

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instansi IPdfDocument yang digunakan untuk mengakses struktur internal dokumen.

**Returns:**
IPdfDocument objek

### getFileName {#getFileName--}
```
public String getFileName()
```

Nama file PDF yang menyebabkan dokumen ini

**Returns:**
nilai String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Mendapatkan dan mengatur batas ukuran berkas untuk memuat seluruh berkas ke dalam memori.

**Returns:**
nilai int

### getForm {#getForm--}
```
public Form getForm()
```

Mendapatkan Acro Form dokumen.

**Returns:**
Form objek

### getId {#getId--}
```
public Id getId()
```

Mendapatkan ID.

**Returns:**
Id objek

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber.

**Returns:**
nilai boolean

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Mendapatkan info dokumen.

**Returns:**
DocumentInfo objek

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Koleksi JavaScript tingkat dokumen.

**Returns:**
Objek JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Mendapatkan struktur logis dokumen.

**Returns:**
RootElement objek

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Metadata dokumen.

**Returns:**
Metadata objek

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Hanya untuk penggunaan internal!

**Returns:**
IPdfStreamAccessor objek

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Koleksi Named Destination dalam dokumen.

**Returns:**
NamedDestinationCollection instansi

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Mendapatkan mode halaman, yang menentukan cara menampilkan dokumen saat keluar dari mode layar penuh.

**Returns:**
PageMode elemen

### getObjectById {#getObjectById-java.lang.String-}
Mendapatkan objek dengan ID yang ditentukan dalam dokumen.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

Mendapatkan aksi yang dilakukan saat pembukaan dokumen.

**Returns:**
IAppointment objek

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Mendapatkan flag optimisasi.

**Returns:**
nilai boolean

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Mendapatkan outline dokumen.

**Returns:**
objek OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Mendapatkan koleksi Output intents dalam dokumen.

**Returns:**
Instansi OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen)

**Returns:**
Informasi halaman.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Mendapatkan label halaman dalam dokumen.

**Returns:**
objek PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Mendapatkan tata letak halaman yang akan digunakan saat dokumen dibuka.

**Returns:**
elemen PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Mendapatkan mode halaman, yang menentukan cara dokumen ditampilkan saat dibuka.

**Returns:**
PageMode elemen

### getPages {#getPages--}
```
public PageCollection getPages()
```

Mendapatkan koleksi halaman dokumen.

**Returns:**
nilai boolean

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Mendapatkan format PDF.

**Returns:**
PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Mendapatkan izin dokumen.

**Returns:**
nilai int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Mendapatkan opsi penanganan skala cetak yang digunakan saat mencetak file dari dialog cetak.

**Returns:**
elemen PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public ITaggedContent getTaggedContent()
```

Mendapatkan akses ke konten TaggedPdf.

**Returns:**
instance ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Mendapatkan versi PDF dari header file PDF.

**Returns:**
Objek String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Dapatkan metadata XMP dari dokumen.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Memeriksa apakah dokumen PDF saat ini telah disimpan dengan pembaruan inkremental.

**Returns:**
true jika dokumen PDF memiliki pembaruan inkremental; jika tidak, false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Mengimpor anotasi dari aliran ke dokumen.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Mengimpor anotasi dari file XFDF ke dokumen.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Flag yang memberi tahu tentang penggantian font yang hilang.

**Returns:**
nilai boolean

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

Mendapatkan flag yang menentukan apakah posisi jendela dokumen akan dipusatkan pada layar.

**Returns:**
nilai boolean

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.

**Returns:**
nilai boolean secara default false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

Mendapatkan flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen.

**Returns:**
nilai boolean

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah mengaktifkan pencatatan notifikasi.

**Returns:**
nilai boolean

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori.

**Returns:**
nilai boolean

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Mendapatkan status enkripsi dokumen.

**Returns:**
nilai boolean

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

Mendapatkan flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan.

**Returns:**
nilai boolean

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Melempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan

**Returns:**
nilai boolean

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

Mendapatkan flag yang menentukan apakah menu bar harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

Mendapatkan flag yang menentukan apakah toolbar harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Mendapatkan status lisensi sistem.

**Returns:**
nilai boolean

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier.

**Returns:**
nilai boolean

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Secara default metode save menutup aliran internal dan melepaskan sumber daya memori.

**Returns:**
nilai boolean. (Nilai default == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Mendapatkan status kepatuhan dokumen pdfa.

**Returns:**
nilai boolean

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Mendapatkan apakah dokumen mematuhi pdfua.

**Returns:**
nilai boolean

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Mendapatkan flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input.

**Returns:**
nilai boolean

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Memeriksa apakah dokumen memerlukan pemanggilan metode Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Secara default proses validasi pdfa diperlukan untuk memperbarui atau menghapus data yang mematuhi pdfa jika beberapa aturan dilanggar.

**Returns:**
nilai boolean

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Mendapatkan atau mengatur apakah dokumen mematuhi pdfa.

**Returns:**
nilai boolean

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Memuat sebuah file, mengkonversinya menjadi PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Menggabungkan dokumen.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Menggabungkan dokumen.

### merge {#merge-com.aspose.pdf.Document...-}
Menggabungkan dokumen.

### merge {#merge-java.lang.String...-}
Menggabungkan file pdf.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Menggabungkan dokumen.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Menggabungkan dokumen.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Menggabungkan dokumen.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Menggabungkan file pdf.

### optimize {#optimize--}
```
public void optimize()
```

Linearize dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data halaman tiba ketika data untuk sebuah halaman dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimalkan sumber daya dalam dokumen: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodesNumInSubtrees |  | Jumlah subnode yang diinginkan. Nilai default adalah sepuluh. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Metode internal

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Menyimpan dokumen ke dalam generator.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Menghapus metadata dari dokumen.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Hapus kepatuhan pdfa dari dokumen

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Hapus kepatuhan pdfUa dari dokumen

### repair {#repair--}
```
public void repair()
```

Memperbaiki dokumen yang rusak.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Memperbaiki dokumen yang rusak.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

melanjutkan pembaruan dokumen

### save {#save--}
```
public void save()
```

Simpan dokumen secara inkremental (misalnya.

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
Menyimpan dokumen ke aliran respons dengan opsi penyimpanan.

### save {#save-java.io.OutputStream-}
Menyimpan dokumen ke dalam stream.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Menyimpan dokumen dengan nama baru beserta format file.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya.

### save {#save-com.aspose.pdf.SaveOptions-}
Menyimpan dokumen dengan opsi penyimpanan.

### save {#save-com.aspose.ms.System.IO.Stream-}
Hanya untuk penggunaan internal

### save {#save-java.lang.String-}
Menyimpan dokumen ke dalam file yang ditentukan.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
Menyimpan dokumen dengan nama baru beserta format file.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan.

### saveXml {#saveXml-java.lang.String-}
Simpan dokumen ke XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Mengirim seluruh dokumen ke perangkat dokumen untuk diproses.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Mengirim seluruh dokumen ke perangkat dokumen untuk diproses.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Mengirim seluruh dokumen ke perangkat dokumen untuk diproses.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Pemberitahuan tentang font yang hilang saat memproses dokumen.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean substitute)
```

Mengatur flag untuk mengganti font yang hilang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| substitusi |  | nilai boolean |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Memungkinkan menggabungkan konten halaman untuk mengoptimalkan ukuran dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBackground {#setBackground-java.awt.Color-}
Mengatur warna latar belakang dokumen.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan di layar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Mengatur koleksi dokumen.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Mendapatkan parameter konversi untuk konverter pdf/ua (Hanya konversi Metadata dan Katalog Dokumen jika diatur true).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Mengatur batas ukuran file untuk memuat seluruh file ke memori ke nilai default sebesar 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean secara default false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | PrintDuplex elemen |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah mengaktifkan pencatatan notifikasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Mendapatkan atau mengatur flag yang memungkinkan dokumen sebagian dibongkar dari memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Mendapatkan dan mengatur batas ukuran berkas untuk memuat seluruh berkas ke dalam memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Melempar Exception jika dokumen akan disimpan dengan perubahan dan memiliki tanda tangan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Mengatur flag yang menentukan apakah bilah menu harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Mengatur flag yang menentukan apakah bilah alat harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Mengatur nilai yang menunjukkan apakah dokumen terlinier.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Secara default metode save menutup aliran internal dan melepaskan sumber daya memori.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| manualDisposeEnabled |  | nilai boolean. (Nilai default == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Mengatur mode halaman, menentukan bagaimana menampilkan dokumen saat keluar dari mode layar penuh.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Mengatur aksi yang dilakukan saat membuka dokumen.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Mengatur flag optimisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Mengatur informasi halaman. (hanya untuk generator, tidak diisi saat membaca dokumen)

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Mengatur mode halaman, menentukan bagaimana dokumen harus ditampilkan saat dibuka.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Mengatur flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Mengatur opsi penanganan skala cetak yang akan digunakan saat mencetak file dari dialog cetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | PrintDuplex elemen |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Secara default proses validasi pdfa diperlukan untuk memperbarui atau menghapus pdfa jika beberapa aturan dilanggar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | nilai boolean |

### setTitle {#setTitle-java.lang.String-}
Atur Judul untuk Dokumen Pdf

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Atur metadata XMP dokumen.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Mendapatkan atau mengatur apakah dokumen mematuhi pdfa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Menekan pembaruan data konten untuk semua halaman. Konten tidak diperbarui sampai ResumeUpdate dipanggil.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validasi dokumen ke dalam file yang ditentukan.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Validasi dokumen ke dalam file yang ditentukan.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validasi dokumen ke dalam file yang ditentukan.
