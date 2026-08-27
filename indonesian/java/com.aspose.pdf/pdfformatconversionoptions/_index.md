---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "mewakili sekumpulan opsi untuk mengonversi dokumen PDF"
type: docs
weight: 3730
url: /id/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

mewakili sekumpulan opsi untuk mengonversi dokumen PDF

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Konstruktor |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag {@code AlignText} diatur ke true. |
| [getAlignText](#getAlignText--) | Flag ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen tidak mempengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika flag ini diaktifkan, operasi perataan khusus akan dilakukan. Flag ini hanya harus diaktifkan untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan flag ini dapat menurunkan kinerja dan dalam beberapa kasus dapat merusak isi teks. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | Mendapatkan atau mengatur pengaturan untuk penandaan otomatis selama konversi format PDF. Pengaturan penandaan otomatis digunakan untuk mengkonfigurasi perilaku proses auto-tagging, yang biasanya digunakan untuk meningkatkan aksesibilitas dan struktur dokumen PDF selama konversi ke format PDF tertentu. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Aksi untuk gambar dengan soft mask. |
| [getDefault](#getDefault--) | Mendapatkan objek PdfFormatConversionOptions dengan parameter default. |
| [getErrorAction](#getErrorAction--) | Aksi untuk objek yang tidak dapat dikonversi. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. Parameter ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur ke true. Secara default kombinasi strategi {@code SubsetFonts} dan {@code RemoveDuplicatedFonts} digunakan. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Opsi untuk kasus ketika tidak memungkinkan menyematkan beberapa font ke dalam dokumen PDF. |
| [getFormat](#getFormat--) | Format PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | Mendapatkan nama file profil icc. Jika null, profil icc default yang digunakan. |
| [getLogFileName](#getLogFileName--) | Jalur ke file tempat komentar akan disimpan. |
| [getLogStream](#getLogStream--) | Stream tempat komentar akan disimpan. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Menyimpan flag untuk mengontrol proses konversi PDF/A pada kasus ketika dokumen sumber tidak sesuai dengan spesifikasi PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Properti ini adalah out-property. Ini menyimpan semua font (nama font) yang tidak ditemukan di komputer pada konversi PDF/A terakhir. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | Mendapatkan flag yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil. Saat ini flag ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, dan kemungkinan di masa depan flag ini juga akan digunakan untuk mengaktifkan optimisasi struktur data lain, seperti grafik. Kombinasi flag dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan menurunkan kinerja konversi. |
| [getOutputIntent](#getOutputIntent--) | Mendapatkan atau mengatur {@link OutputIntent} untuk konversi format PDF. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) menentukan perangkat output atau kondisi yang dimaksudkan untuk mana dokumen PDF disiapkan. Ini digunakan untuk memastikan bahwa warna dalam dokumen ditampilkan dengan benar pada perangkat target. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Strategi untuk memproses simbol dari Unicode Private Use Area (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable enkoding. |
| [getTransparencyAction](#getTransparencyAction--) | Tindakan untuk objek gambar yang dimask. |
| [getTransparencyResolution](#getTransparencyResolution--) | Mengatur resolusi selama mengonversi gambar transparan. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Bisa bernilai null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Mendapatkan/mengatur jalannya stream gambar dalam mode async. |
| [isLowMemoryMode](#isLowMemoryMode--) | Apakah mode konversi memori rendah diaktifkan |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Apakah analisis font per halaman diaktifkan. Nilai default = false |
| [isTransferInfo](#isTransferInfo--) | Mendapatkan atau mengatur apakah data dari Info diteruskan ke Metadata saat dikonversi ke PDF 2.0. True secara default. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Nilai default FALSE dan warna transparansi akan diproses untuk mempertahankan tampilan dokumen. Dengan nilai TRUE warna transparansi akan dikonversi menjadi non-transparansi, beberapa objek dapat tertutup. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag {@code AlignText} diatur ke true. |
| [setAlignText](#setAlignText-boolean-) | Flag ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen tidak mempengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika flag ini diaktifkan, operasi perataan khusus akan dilakukan. Flag ini hanya harus diaktifkan untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan flag ini dapat menurunkan kinerja dan dalam beberapa kasus dapat merusak isi teks. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Mendapatkan/mengatur jalannya stream gambar dalam mode async. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | Mendapatkan atau mengatur pengaturan untuk penandaan otomatis selama konversi format PDF. Pengaturan penandaan otomatis digunakan untuk mengkonfigurasi perilaku proses auto-tagging, yang biasanya digunakan untuk meningkatkan aksesibilitas dan struktur dokumen PDF selama konversi ke format PDF tertentu. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Aksi untuk gambar dengan soft mask. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Aksi untuk objek yang tidak dapat dikonversi. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. Parameter ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur ke true. Secara default kombinasi strategi {@code SubsetFonts} dan {@code RemoveDuplicatedFonts} digunakan. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | Format PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | Mengatur nama file profil icc. Jika null, profil icc default yang digunakan. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Jalur ke file tempat komentar akan disimpan. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Stream tempat komentar akan disimpan. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Apakah mode konversi memori rendah diaktifkan |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | Mengatur flag yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil. Saat ini flag ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, dan kemungkinan di masa depan flag ini juga akan digunakan untuk mengaktifkan optimisasi struktur data lain, seperti grafik. Kombinasi flag dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan menurunkan kinerja konversi. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | Mendapatkan atau mengatur {@link OutputIntent} untuk konversi format PDF. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) menentukan perangkat output atau kondisi yang dimaksudkan untuk mana dokumen PDF disiapkan. Ini digunakan untuk memastikan bahwa warna dalam dokumen ditampilkan dengan benar pada perangkat target. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Mengatur analisis font per halaman diaktifkan. Nilai default = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Strategi untuk memproses simbol dari Unicode Private Use Area (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable enkoding. |
| [setTransferInfo](#setTransferInfo-boolean-) | Mendapatkan atau mengatur apakah data dari Info diteruskan ke Metadata saat dikonversi ke PDF 2.0. True secara default. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Tindakan untuk objek gambar yang dimask. |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Nilai default FALSE dan warna transparansi akan diproses untuk mempertahankan tampilan dokumen. Dengan nilai TRUE warna transparansi akan dikonversi menjadi non-transparansi, beberapa objek dapat tertutup. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Mengatur resolusi selama mengonversi gambar transparan. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Bisa bernilai null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Konstruktor

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Konstruktor

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag {@code AlignText} diatur ke true.

**Returns:**
Elemen SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Flag ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen tidak mempengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika flag ini diaktifkan, operasi perataan khusus akan dilakukan. Flag ini hanya harus diaktifkan untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan flag ini dapat menurunkan kinerja dan dalam beberapa kasus dapat merusak isi teks.

**Returns:**
nilai boolean

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

Mendapatkan atau mengatur pengaturan untuk penandaan otomatis selama konversi format PDF. Pengaturan penandaan otomatis digunakan untuk mengkonfigurasi perilaku proses auto-tagging, yang biasanya digunakan untuk meningkatkan aksesibilitas dan struktur dokumen PDF selama konversi ke format PDF tertentu.

**Returns:**
Instansi AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Aksi untuk gambar dengan soft mask.

**Returns:**
nilai int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Mendapatkan objek PdfFormatConversionOptions dengan parameter default.

**Returns:**
Objek PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Aksi untuk objek yang tidak dapat dikonversi.

**Returns:**
Elemen ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. Parameter ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur ke true. Secara default kombinasi strategi {@code SubsetFonts} dan {@code RemoveDuplicatedFonts} digunakan.

**Returns:**
Nilai byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Opsi untuk kasus ketika tidak memungkinkan menyematkan beberapa font ke dalam dokumen PDF.

**Returns:**
Objek FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

Format PDF.

**Returns:**
Elemen PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

Mendapatkan nama file profil icc. Jika null, profil icc default yang digunakan.

**Returns:**
Objek String

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Jalur ke file tempat komentar akan disimpan.

**Returns:**
Objek String

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Stream tempat komentar akan disimpan.

**Returns:**
objek OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Menyimpan flag untuk mengontrol proses konversi PDF/A pada kasus ketika dokumen sumber tidak sesuai dengan spesifikasi PDF/A.

**Returns:**
objek PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Properti ini adalah out-property. Ini menyimpan semua font (nama font) yang tidak ditemukan di komputer pada konversi PDF/A terakhir.

**Returns:**
Array of Strings

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

Mendapatkan flag yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil. Saat ini flag ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, dan kemungkinan di masa depan flag ini juga akan digunakan untuk mengaktifkan optimisasi struktur data lain, seperti grafik. Kombinasi flag dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan menurunkan kinerja konversi.

**Returns:**
nilai boolean

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

Mendapatkan atau mengatur {@link OutputIntent} untuk konversi format PDF. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) menentukan perangkat output atau kondisi yang dimaksudkan untuk mana dokumen PDF disiapkan. Ini digunakan untuk memastikan bahwa warna dalam dokumen ditampilkan dengan benar pada perangkat target.

**Returns:**
instance OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Strategi untuk memproses simbol dari Unicode Private Use Area (PUA).

**Returns:**
elemen PuaProcessingStrategy @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable enkoding.

**Returns:**
objek PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Tindakan untuk objek gambar yang dimask.

**Returns:**
elemen ConvertTransparencyAction @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Mengatur resolusi selama mengonversi gambar transparan. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 300.

**Returns:**
nilai Resolusi

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Bisa bernilai null.

**Returns:**
objek ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Mendapatkan/mengatur jalannya stream gambar dalam mode async.

**Returns:**
nilai boolean

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Apakah mode konversi memori rendah diaktifkan

**Returns:**
nilai boolean

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Apakah analisis font per halaman diaktifkan. Nilai default = false

**Returns:**
nilai boolean

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

Mendapatkan atau mengatur apakah data dari Info diteruskan ke Metadata saat dikonversi ke PDF 2.0. True secara default.

**Returns:**
nilai boolean

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Nilai default FALSE dan warna transparansi akan diproses untuk mempertahankan tampilan dokumen. Dengan nilai TRUE warna transparansi akan dikonversi menjadi non-transparansi, beberapa objek dapat tertutup.

**Returns:**
nilai boolean

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Strategi untuk meratakan teks. Parameter ini hanya bermakna ketika flag {@code AlignText} diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alignStrategy |  | Elemen SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Flag ini mengontrol perataan teks dalam dokumen yang dikonversi. Secara default konversi dokumen tidak mempengaruhi perataan teks dan membiarkan teks apa adanya. Namun dalam beberapa kasus substitusi font menyebabkan teks saling tumpang tindih atau spasi ekstra dalam dokumen yang dikonversi. Ketika flag ini diaktifkan, operasi perataan khusus akan dilakukan. Flag ini hanya harus diaktifkan untuk dokumen yang memiliki masalah dengan teks yang tumpang tindih atau spasi teks ekstra karena penggunaan flag ini dapat menurunkan kinerja dan dalam beberapa kasus dapat merusak isi teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Mendapatkan/mengatur jalannya stream gambar dalam mode async.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
Mendapatkan atau mengatur pengaturan untuk penandaan otomatis selama konversi format PDF. Pengaturan penandaan otomatis digunakan untuk mengkonfigurasi perilaku proses auto-tagging, yang biasanya digunakan untuk meningkatkan aksesibilitas dan struktur dokumen PDF selama konversi ke format PDF tertentu.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Aksi untuk gambar dengan soft mask.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Aksi untuk objek yang tidak dapat dikonversi.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Strategi untuk mengecualikan font yang berlebih dan mengurangi ukuran file dokumen. Parameter ini hanya bermakna ketika flag {@code OptimizeFileSize} diatur ke true. Secara default kombinasi strategi {@code SubsetFonts} dan {@code RemoveDuplicatedFonts} digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
Format PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
Mengatur nama file profil icc. Jika null, profil icc default yang digunakan.

### setLogFileName {#setLogFileName-java.lang.String-}
Jalur ke file tempat komentar akan disimpan.

### setLogStream {#setLogStream-java.io.OutputStream-}
Stream tempat komentar akan disimpan.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Apakah mode konversi memori rendah diaktifkan

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

Mengatur flag yang mengaktifkan/menonaktifkan mode konversi khusus untuk menghasilkan dokumen PDF/A dengan ukuran file yang lebih kecil. Saat ini flag ini memengaruhi optimisasi font yang digunakan dalam dokumen PDF, dan kemungkinan di masa depan flag ini juga akan digunakan untuk mengaktifkan optimisasi struktur data lain, seperti grafik. Kombinasi flag dan mode ini dapat secara signifikan mengurangi ukuran file tetapi pada saat yang sama dapat secara signifikan menurunkan kinerja konversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
Mendapatkan atau mengatur {@link OutputIntent} untuk konversi format PDF. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) menentukan perangkat output atau kondisi yang dimaksudkan untuk mana dokumen PDF disiapkan. Ini digunakan untuk memastikan bahwa warna dalam dokumen ditampilkan dengan benar pada perangkat target.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Mengatur analisis font per halaman diaktifkan. Nilai default = false

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| b |  | nilai boolean |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Strategi untuk memproses simbol dari Unicode Private Use Area (PUA).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen PuaProcessingStrategy @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Strategi untuk menyalin data enkoding untuk font simbolik jika font TrueType simbolik memiliki lebih dari satu subtable enkoding.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

Mendapatkan atau mengatur apakah data dari Info diteruskan ke Metadata saat dikonversi ke PDF 2.0. True secara default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Tindakan untuk objek gambar yang dimask.

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Nilai default FALSE dan warna transparansi akan diproses untuk mempertahankan tampilan dokumen. Dengan nilai TRUE warna transparansi akan dikonversi menjadi non-transparansi, beberapa objek dapat tertutup.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Mengatur resolusi selama mengonversi gambar transparan. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 300.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpi |  | nilai Resolusi |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Aturan untuk menyelesaikan masalah dengan pemetaan unicode. Bisa bernilai null.
