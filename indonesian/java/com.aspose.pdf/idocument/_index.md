---
title: "IDocument"
linktitle: "IDocument"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "antarmuka yang mewakili dokumen PDF"
type: docs
weight: 2230
url: /id/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

antarmuka yang mewakili dokumen PDF

## Metode

| Metode | Deskripsi |
| --- | --- |
| [afterImport](#afterImport--) | Enumerasi semua anotasi yang terdaftar dan panggil AfterImport untuk masing-masing. |
| [bindXml](#bindXml-java.io.InputStream-) | Mengikat xml ke dokumen |
| [bindXml](#bindXml-java.lang.String-) | Mengikat xml ke dokumen |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Mengikat xml/xsl ke dokumen |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Mengubah kata sandi dokumen. |
| [check](#check-boolean-) | Memvalidasi dokumen. |
| [close](#close--) | Menutup semua sumber daya yang digunakan oleh dokumen ini. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. <p> Ini memungkinkan untuk menampilkan/menyembunyikan teks yang dapat dicari pada halaman. Nilai default adalah FALSE. Ini memungkinkan untuk mendapatkan gambar asli dari pdf. Nilai default adalah FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. <p> Ini memungkinkan untuk menampilkan/menyembunyikan teks yang dapat dicari pada halaman. Nilai default adalah FALSE. Ini memungkinkan untuk mendapatkan gambar asli dari pdf. Nilai default adalah FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Mengonversi dokumen menggunakan opsi konversi yang ditentukan |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Metode internal |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi. |
| [decrypt](#decrypt--) | Mendekripsi dokumen. |
| [dispose](#dispose--) | Usang. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Mengenkripsi dokumen. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Mengenkripsi dokumen. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Mengekspor semua anotasi dokumen ke file XFDF |
| [flatten](#flatten--) | Menghapus semua bidang (dan anotasi) dari dokumen dan menempatkan nilai mereka sebagai gantinya. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Menghapus semua bidang dari dokumen dan menempatkan nilainya sebagai gantinya. |
| [flattenTransparency](#flattenTransparency--) | Mengganti konten transparan dengan grafik raster dan vektor yang tidak transparan. |
| [freeMemory](#freeMemory--) | Menghapus memori |
| [getActions](#getActions--) | Mendapatkan tindakan dokumen. |
| [getBackground](#getBackground--) | Mendapatkan warna latar belakang dokumen. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Mengembalikan nilai item dari kamus katalog. |
| [getCollection](#getCollection--) | Mendapatkan koleksi dokumen. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Mendapatkan pengaturan keamanan jika dokumen dienkripsi. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Mendapatkan penangan keamanan khusus. |
| [getDefaultCopier](#getDefaultCopier--) | Mengembalikan penyalin yang digunakan untuk menyalin halaman ke dokumen ini. |
| [getDestinations](#getDestinations--) | Mendapatkan koleksi tujuan. |
| [getDirection](#getDirection--) | Mendapatkan urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [getDuplex](#getDuplex--) | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Mendapatkan koleksi file yang disematkan ke dokumen. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. |
| [getEngineDoc](#getEngineDoc--) | Instansi IPdfDocument yang digunakan untuk mengakses struktur internal dokumen. |
| [getFileName](#getFileName--) | Nama file PDF yang menyebabkan dokumen ini |
| [getForm](#getForm--) | Mendapatkan Acro Form dokumen. |
| [getId](#getId--) | Mendapatkan ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber. |
| [getInfo](#getInfo--) | Mendapatkan info dokumen. |
| [getLogicalStructure](#getLogicalStructure--) | Mendapatkan struktur logis dokumen. |
| [getMetadata](#getMetadata--) | Metadata dokumen. |
| [getMetadataStream](#getMetadataStream--) | Mengembalikan aliran metadata mentah |
| [getNamedDestinations](#getNamedDestinations--) | Koleksi Named Destination dalam dokumen. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Mendapatkan mode halaman, yang menentukan cara menampilkan dokumen saat keluar dari mode layar penuh. |
| [getObjectById](#getObjectById-java.lang.String-) | Mendapatkan objek dengan ID yang ditentukan dalam dokumen. |
| [getOpenAction](#getOpenAction--) | Mendapatkan aksi yang dilakukan saat pembukaan dokumen. |
| [getOptimizeSize](#getOptimizeSize--) | Mendapatkan flag optimisasi. |
| [getOutlines](#getOutlines--) | Mendapatkan outline dokumen. |
| [getPageInfo](#getPageInfo--) | Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [getPageLabels](#getPageLabels--) | Mendapatkan label halaman dalam dokumen. |
| [getPageLayout](#getPageLayout--) | Mendapatkan tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [getPageMode](#getPageMode--) | Mendapatkan mode halaman, yang menentukan cara dokumen ditampilkan saat dibuka. |
| [getPages](#getPages--) | Mendapatkan koleksi halaman dokumen. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Mendapatkan izin dokumen. |
| [getPrintScaling](#getPrintScaling--) | Mendapatkan opsi penanganan skala cetak yang digunakan saat mencetak file dari dialog cetak. |
| [getTaggedContent](#getTaggedContent--) | Mendapatkan akses ke konten TaggedPdf. |
| [getVersion](#getVersion--) | Mendapatkan versi PDF dari header file PDF. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Dapatkan metadata XMP dari dokumen. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Mengimpor anotasi dari file XFDF ke dokumen. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Pemberitahuan tentang font yang hilang saat memproses dokumen |
| [isCenterWindow](#isCenterWindow--) | Mendapatkan flag yang menentukan apakah posisi jendela dokumen akan dipusatkan pada layar. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Mendapatkan flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [isEncrypted](#isEncrypted--) | Mendapatkan status enkripsi dokumen. |
| [isFitWindow](#isFitWindow--) | Mendapatkan flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [isHideMenubar](#isHideMenubar--) | Mendapatkan flag yang menentukan apakah menu bar harus disembunyikan ketika dokumen aktif. |
| [isHideToolBar](#isHideToolBar--) | Mendapatkan flag yang menentukan apakah toolbar harus disembunyikan ketika dokumen aktif. |
| [isHideWindowUI](#isHideWindowUI--) | Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif. |
| [isLinearized](#isLinearized--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Secara default, metode save menutup aliran internal dan melepaskan sumber daya memori. Kita dapat melakukan beberapa operasi dan melanjutkan pekerjaan dengan dokumen setelah metode save jika parameter ManualDispose ini diaktifkan. |
| [isPdfaCompliant](#isPdfaCompliant--) | Mendapatkan apakah dokumen mematuhi pdf/a. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Mendapatkan apakah dokumen mematuhi pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Mendapatkan flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Mendapatkan atau mengatur apakah dokumen mematuhi pdfa. |
| [optimize](#optimize--) | Linierkan dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data halaman tiba ketika data dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan. |
| [optimizeResources](#optimizeResources--) | Optimalkan sumber daya dalam dokumen: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang. |
| [processParagraphs](#processParagraphs--) | Menyimpan dokumen ke dalam stream. |
| [removeMetadata](#removeMetadata--) | Menghapus metadata dari dokumen. |
| [removePdfaCompliance](#removePdfaCompliance--) | Hapus kepatuhan pdfa dari dokumen |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Hapus kepatuhan pdfUa dari dokumen |
| [repair](#repair--) | Memperbaiki dokumen yang rusak. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Simpan dokumen secara inkremental (misalnya. |
| [save](#save-java.io.OutputStream-) | Menyimpan dokumen ke dalam stream. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Simpan dokumen |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [save](#save-java.lang.String-) | Menyimpan dokumen ke dalam file yang ditentukan. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Menyimpan secara inkremental Dokumen PDF ke stream yang ditentukan. |
| [saveXml](#saveXml-java.lang.String-) | Simpan dokumen ke XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Mengirim halaman tertentu dari dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Mengirim seluruh dokumen ke perangkat dokumen untuk diproses. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Mengatur flag untuk menetapkan font yang ditentukan program bila font tidak ada. |
| [setBackground](#setBackground-java.awt.Color-) | Mengatur warna latar belakang dokumen. |
| [setCenterWindow](#setCenterWindow-boolean-) | Mengatur flag yang menentukan apakah posisi jendela dokumen akan dipusatkan di layar. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Mengatur koleksi dokumen. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Mendapatkan parameter konversi untuk konverter pdf/ua (Hanya konversi Metadata dan Katalog Dokumen jika diatur true). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen. |
| [setDuplex](#setDuplex-int-) | Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan. |
| [setFitWindow](#setFitWindow-boolean-) | Mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan. |
| [setHideMenubar](#setHideMenubar-boolean-) | Mengatur flag yang menentukan apakah bilah menu harus disembunyikan saat dokumen aktif. |
| [setHideToolBar](#setHideToolBar-boolean-) | Mengatur flag yang menentukan apakah bilah alat harus disembunyikan saat dokumen aktif. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Mengatur nilai yang menunjukkan apakah dokumen terlinier. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Secara default metode save menutup aliran internal dan melepaskan sumber daya memori. Kita dapat melakukan beberapa operasi dan melanjutkan kerja dengan dokumen setelah metode save dipanggil jika parameter ManualDispose ini diaktifkan. Namun sangat disarankan untuk memanggil metode dispose ketika instance Document tidak lagi diperlukan. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Mengatur mode halaman, menentukan bagaimana menampilkan dokumen saat keluar dari mode layar penuh. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Mengatur aksi yang dilakukan saat membuka dokumen. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Mengatur flag optimisasi. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Mengatur informasi halaman. (hanya untuk generator, tidak diisi saat membaca dokumen) |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Mengatur tata letak halaman yang akan digunakan saat dokumen dibuka. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Mengatur mode halaman, menentukan bagaimana dokumen harus ditampilkan saat dibuka. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Mengatur flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input. |
| [setPrintScaling](#setPrintScaling-int-) | Mengatur opsi penanganan skala cetak yang akan digunakan saat mencetak file dari dialog cetak. |
| [setTitle](#setTitle-java.lang.String-) | Atur Judul untuk Dokumen Pdf |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Atur metadata XMP dokumen. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Mendapatkan atau mengatur apakah dokumen mematuhi pdfa. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Validasi dokumen ke dalam file yang ditentukan. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Validasi dokumen ke dalam file yang ditentukan. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumerasi semua anotasi yang terdaftar dan panggil AfterImport untuk masing-masing.

### bindXml {#bindXml-java.io.InputStream-}
Mengikat xml ke dokumen

### bindXml {#bindXml-java.lang.String-}
Mengikat xml ke dokumen

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Mengikat xml/xsl ke dokumen

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Mengubah kata sandi dokumen.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Memvalidasi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| doRepair |  | Jika true, masalah yang ditemukan akan diperbaiki. |

**Returns:**
nilai boolean

### close {#close--}
```
void close()
```

Menutup semua sumber daya yang digunakan oleh dokumen ini.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. <p> Ini memungkinkan untuk menampilkan/menyembunyikan teks yang dapat dicari pada halaman. Nilai default adalah FALSE. Ini memungkinkan untuk mendapatkan gambar asli dari pdf. Nilai default adalah FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan. <p> Ini memungkinkan untuk menampilkan/menyembunyikan teks yang dapat dicari pada halaman. Nilai default adalah FALSE. Ini memungkinkan untuk mendapatkan gambar asli dari pdf. Nilai default adalah FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Mengonversi dokumen menggunakan opsi konversi yang ditentukan

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Mengonversi dokumen dan menyimpan kesalahan ke file yang ditentukan.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Metode internal

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Mengonversi dokumen menjadi dokumen yang dapat dicari dan melewati kesalahan hochr yang tidak dapat dikonversi.

### decrypt {#decrypt--}
```
void decrypt()
```

Mendekripsi dokumen.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Usang.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Mengenkripsi dokumen.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Mengenkripsi dokumen.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Mengekspor semua anotasi dokumen ke file XFDF

### flatten {#flatten--}
```
void flatten()
```

Menghapus semua bidang (dan anotasi) dari dokumen dan menempatkan nilai mereka sebagai gantinya.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Menghapus semua bidang dari dokumen dan menempatkan nilainya sebagai gantinya.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Mengganti konten transparan dengan grafik raster dan vektor yang tidak transparan.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Menghapus memori

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Mendapatkan tindakan dokumen.

**Returns:**
DocumentActionCollection objek

### getBackground {#getBackground--}
```
Color getBackground()
```

Mendapatkan warna latar belakang dokumen.

**Returns:**
java.awt.Color objek

### getCatalogValue {#getCatalogValue-java.lang.String-}
Mengembalikan nilai item dari kamus katalog.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Mendapatkan koleksi dokumen.

**Returns:**
Collection objek

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Mendapatkan pengaturan keamanan jika dokumen dienkripsi.

**Returns:**
CryptoAlgorithm elemen atau null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Mendapatkan penangan keamanan khusus.

**Returns:**
ICustomSecurityHandler instansi

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Mengembalikan penyalin yang digunakan untuk menyalin halaman ke dokumen ini.

**Returns:**
Copier objek

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Mendapatkan koleksi tujuan.

**Returns:**
DestinationCollection objek

### getDirection {#getDirection--}
```
Direction getDirection()
```

Mendapatkan urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri).

**Returns:**
Direction elemen

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak.

**Returns:**
PrintDuplex elemen

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Mendapatkan koleksi file yang disematkan ke dokumen.

**Returns:**
EmbeddedFileCollection objek

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true.

**Returns:**
nilai boolean

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan.

**Returns:**
nilai boolean

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instansi IPdfDocument yang digunakan untuk mengakses struktur internal dokumen.

**Returns:**
IPdfDocument objek

### getFileName {#getFileName--}
```
String getFileName()
```

Nama file PDF yang menyebabkan dokumen ini

**Returns:**
Objek String

### getForm {#getForm--}
```
Form getForm()
```

Mendapatkan Acro Form dokumen.

**Returns:**
Form objek

### getId {#getId--}
```
Id getId()
```

Mendapatkan ID.

**Returns:**
Id objek

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Mendapatkan atau mengatur flag untuk mengabaikan kesalahan dalam file sumber.

**Returns:**
nilai boolean

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Mendapatkan info dokumen.

**Returns:**
DocumentInfo objek

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Mendapatkan struktur logis dokumen.

**Returns:**
RootElement objek

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Metadata dokumen.

**Returns:**
Metadata objek

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Mengembalikan aliran metadata mentah

**Returns:**
IPdfStreamAccessor objek

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Koleksi Named Destination dalam dokumen.

**Returns:**
NamedDestinationCollection instansi

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Mendapatkan mode halaman, yang menentukan cara menampilkan dokumen saat keluar dari mode layar penuh.

**Returns:**
PageMode elemen

### getObjectById {#getObjectById-java.lang.String-}
Mendapatkan objek dengan ID yang ditentukan dalam dokumen.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Mendapatkan aksi yang dilakukan saat pembukaan dokumen.

**Returns:**
IAppointment objek

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Mendapatkan flag optimisasi.

**Returns:**
nilai boolean

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Mendapatkan outline dokumen.

**Returns:**
objek OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Mendapatkan info halaman. (hanya untuk generator, tidak diisi saat membaca dokumen)

**Returns:**
Informasi halaman.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Mendapatkan label halaman dalam dokumen.

**Returns:**
objek PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Mendapatkan tata letak halaman yang akan digunakan saat dokumen dibuka.

**Returns:**
elemen PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Mendapatkan mode halaman, yang menentukan cara dokumen ditampilkan saat dibuka.

**Returns:**
PageMode elemen

### getPages {#getPages--}
```
PageCollection getPages()
```

Mendapatkan koleksi halaman dokumen.

**Returns:**
nilai boolean

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
elemen PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Mendapatkan izin dokumen.

**Returns:**
nilai int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Mendapatkan opsi penanganan skala cetak yang digunakan saat mencetak file dari dialog cetak.

**Returns:**
elemen PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Mendapatkan akses ke konten TaggedPdf.

**Returns:**
instance ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

Mendapatkan versi PDF dari header file PDF.

**Returns:**
Objek String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Dapatkan metadata XMP dari dokumen.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Mengimpor anotasi dari file XFDF ke dokumen.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Pemberitahuan tentang font yang hilang saat memproses dokumen

**Returns:**
nilai boolean

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Mendapatkan flag yang menentukan apakah posisi jendela dokumen akan dipusatkan pada layar.

**Returns:**
nilai boolean

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.

**Returns:**
nilai boolean secara default false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Mendapatkan flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen.

**Returns:**
nilai boolean

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Mendapatkan status enkripsi dokumen.

**Returns:**
nilai boolean

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Mendapatkan flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan.

**Returns:**
nilai boolean

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Mendapatkan flag yang menentukan apakah menu bar harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Mendapatkan flag yang menentukan apakah toolbar harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Mendapatkan atau mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan ketika dokumen aktif.

**Returns:**
nilai boolean

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen terlinier.

**Returns:**
nilai boolean

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Secara default, metode save menutup aliran internal dan melepaskan sumber daya memori. Kita dapat melakukan beberapa operasi dan melanjutkan pekerjaan dengan dokumen setelah metode save jika parameter ManualDispose ini diaktifkan.

**Returns:**
nilai boolean. (Nilai default == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Mendapatkan apakah dokumen mematuhi pdf/a.

**Returns:**
nilai boolean

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Mendapatkan apakah dokumen mematuhi pdfua.

**Returns:**
nilai boolean

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Mendapatkan flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input.

**Returns:**
nilai boolean

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Mendapatkan atau mengatur apakah dokumen mematuhi pdfa.

**Returns:**
nilai boolean

### optimize {#optimize--}
```
void optimize()
```

Linierkan dokumen untuk - membuka halaman pertama secepat mungkin; - menampilkan halaman berikutnya atau mengikuti tautan ke halaman berikutnya secepat mungkin; - menampilkan halaman secara bertahap saat data halaman tiba ketika data dikirim melalui saluran lambat (menampilkan data yang paling berguna terlebih dahulu); - memungkinkan interaksi pengguna, seperti mengikuti tautan, dilakukan bahkan sebelum seluruh halaman diterima dan ditampilkan.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Optimalkan sumber daya dalam dokumen: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimalkan sumber daya dalam dokumen sesuai dengan strategi optimasi yang ditentukan.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Mengatur node pohon halaman dalam dokumen menjadi pohon seimbang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodesNumInSubtrees |  | Jumlah subnode yang diinginkan. Nilai default adalah sepuluh. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Menyimpan dokumen ke dalam stream.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Menghapus metadata dari dokumen.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Hapus kepatuhan pdfa dari dokumen

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Hapus kepatuhan pdfUa dari dokumen

### repair {#repair--}
```
void repair()
```

Memperbaiki dokumen yang rusak.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Simpan dokumen secara inkremental (misalnya.

### save {#save-java.io.OutputStream-}
Menyimpan dokumen ke dalam stream.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Simpan dokumen

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Menyimpan dokumen dengan nama baru sambil mengatur opsi penyimpanannya.

### save {#save-java.lang.String-}
Menyimpan dokumen ke dalam file yang ditentukan.

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Mengatur flag untuk menetapkan font yang ditentukan program bila font tidak ada.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | nilai boolean |

### setBackground {#setBackground-java.awt.Color-}
Mengatur warna latar belakang dokumen.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
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
void setConvertMetadataAndCatalogOnly(boolean value)
```

Mendapatkan parameter konversi untuk konverter pdf/ua (Hanya konversi Metadata dan Katalog Dokumen jika diatur true).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Mengatur urutan baca teks: L2R (kiri ke kanan) atau R2L (kanan ke kiri).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Banyak operasi dengan font tidak dapat dijalankan jika operasi tersebut dilarang oleh lisensi font ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean secara default false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Mengatur flag yang menentukan apakah bilah judul jendela dokumen harus menampilkan judul dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Mendapatkan atau mengatur opsi penanganan mode duplex cetak yang digunakan saat mencetak file dari dialog cetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | PrintDuplex elemen |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Properti yang menyatakan bahwa dokumen harus menyematkan semua font Type1 standar yang memiliki flag IsEmbedded disetel ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Mendapatkan atau mengatur flag untuk mengelola sanitasi bidang tanda tangan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Mengatur flag yang menentukan apakah jendela dokumen harus diubah ukurannya agar sesuai dengan halaman pertama yang ditampilkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Mengatur flag yang menentukan apakah bilah menu harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Mengatur flag yang menentukan apakah bilah alat harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Mengatur flag yang menentukan apakah elemen antarmuka pengguna harus disembunyikan saat dokumen aktif.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Mengatur nilai yang menunjukkan apakah dokumen terlinier.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Secara default metode save menutup aliran internal dan melepaskan sumber daya memori. Kita dapat melakukan beberapa operasi dan melanjutkan kerja dengan dokumen setelah metode save dipanggil jika parameter ManualDispose ini diaktifkan. Namun sangat disarankan untuk memanggil metode dispose ketika instance Document tidak lagi diperlukan.

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
void setOptimizeSize(boolean value)
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
void setPickTrayByPdfSize(boolean value)
```

Mengatur flag yang menentukan apakah ukuran halaman PDF akan digunakan untuk memilih baki kertas input.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Mengatur opsi penanganan skala cetak yang akan digunakan saat mencetak file dari dialog cetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | PrintDuplex elemen |

### setTitle {#setTitle-java.lang.String-}
Atur Judul untuk Dokumen Pdf

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Atur metadata XMP dokumen.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Mendapatkan atau mengatur apakah dokumen mematuhi pdfa.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Validasi dokumen ke dalam file yang ditentukan.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Validasi dokumen ke dalam file yang ditentukan.
