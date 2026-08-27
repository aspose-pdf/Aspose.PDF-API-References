---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Merepresentasikan opsi rendering"
type: docs
weight: 4150
url: /id/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Merepresentasikan opsi rendering

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Menginisialisasi instance baru dari objek {@code RenderingOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui {@code FontRepository.Sources}. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Mendapatkan mode optimasi barcode. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Menunjukkan bahwa semua font akan dikonversi ke versi unicode TTF. Hal ini berguna untuk alasan kompatibilitas dan mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, melainkan hanya simbol yang digunakan dalam teks. |
| [getDefaultFontName](#getDefaultFontName--) | Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Jumlah maksimum font dalam cache font. Nilai default adalah 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Mendapatkan atau mengatur mode optimasi dimensi. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Mendapatkan atau mengatur nilai yang digunakan untuk mengubah skala semua gambar pada halaman agar sesuai dengan lebar halaman. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Mendapatkan mode di mana font sistem dirender secara native |
| [getUseFontHinting](#getUseFontHinting--) | Penggunaan flag ini mengaktifkan mekanisme font hinting. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus mengaktifkan flag ini dapat menyelesaikan masalah keterbacaan teks. Pada saat ini penggunaan flag ini hanya berpengaruh pada font TTF, jika font tersebut digunakan dalam dokumen sumber. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Mendapatkan flag yang menentukan apakah mesin imaging baru digunakan atau tidak. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | Mendapatkan nilai yang digunakan untuk melewati kesalahan selama pemrosesan file PDF |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui {@code FontRepository.Sources}. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Mengatur mode optimasi barcode. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Menunjukkan bahwa semua font akan dikonversi ke versi unicode TTF. Hal ini berguna untuk alasan kompatibilitas dan mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, melainkan hanya simbol yang digunakan dalam teks. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Jumlah maksimum font dalam cache font. Nilai default adalah 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Mendapatkan atau mengatur mode optimasi dimensi. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Mendapatkan atau mengatur nilai yang digunakan untuk mengubah skala semua gambar pada halaman agar sesuai dengan lebar halaman. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Mengatur mode di mana font sistem dirender secara native |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | Mengatur nilai yang digunakan untuk melewati kesalahan selama pemrosesan file PDF |
| [setUseFontHinting](#setUseFontHinting-boolean-) | Penggunaan flag ini mengaktifkan mekanisme font hinting. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus mengaktifkan flag ini dapat menyelesaikan masalah keterbacaan teks. Pada saat ini penggunaan flag ini hanya berpengaruh pada font TTF, jika font tersebut digunakan dalam dokumen sumber. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Mengatur flag yang menentukan apakah mesin imaging baru digunakan atau tidak. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Menginisialisasi instance baru dari objek {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui {@code FontRepository.Sources}. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan.

**Returns:**
nilai boolean

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Mendapatkan mode optimasi barcode.

**Returns:**
nilai boolean

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Menunjukkan bahwa semua font akan dikonversi ke versi unicode TTF. Hal ini berguna untuk alasan kompatibilitas dan mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, melainkan hanya simbol yang digunakan dalam teks.

**Returns:**
nilai boolean

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang.

**Returns:**
nilai String

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle.

**Returns:**
nilai float

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default

**Returns:**
nilai boolean

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi.

**Returns:**
nilai boolean

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Jumlah maksimum font dalam cache font. Nilai default adalah 10.

**Returns:**
nilai int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100.

**Returns:**
nilai int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Mendapatkan atau mengatur mode optimasi dimensi.

**Returns:**
nilai boolean

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Mendapatkan atau mengatur nilai yang digunakan untuk mengubah skala semua gambar pada halaman agar sesuai dengan lebar halaman.

**Returns:**
nilai boolean @deprecated ScaleImagesToFitPageWidth sudah tidak dipakai lagi.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Mendapatkan mode di mana font sistem dirender secara native

**Returns:**
nilai boolean

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

Penggunaan flag ini mengaktifkan mekanisme font hinting. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus mengaktifkan flag ini dapat menyelesaikan masalah keterbacaan teks. Pada saat ini penggunaan flag ini hanya berpengaruh pada font TTF, jika font tersebut digunakan dalam dokumen sumber.

**Returns:**
nilai boolean

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Mendapatkan flag yang menentukan apakah mesin imaging baru digunakan atau tidak.

**Returns:**
nilai boolean @deprecated UseNewImagingEngine sudah tidak dipakai lagi

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle.

**Returns:**
nilai float

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

Mendapatkan nilai yang digunakan untuk melewati kesalahan selama pemrosesan file PDF

**Returns:**
nilai boolean

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Mengganti font bila diperlukan untuk memastikan semua karakter dalam teks dapat ditampilkan. Algoritma substitusi font mengikuti langkah-langkah berikut: 1. Jika pengguna secara eksplisit mengatur properti DefaultFontName, periksa apakah font yang ditentukan dapat menampilkan karakter yang diinginkan. 2. Jika tidak ada font yang ditetapkan pengguna, cari font yang ditambahkan melalui {@code FontRepository.Sources}. 3. Analisis teks untuk mengidentifikasi alfabet atau skripnya dan sarankan nama font yang sesuai. Coba temukan dan gunakan font tersebut dari sistem. 4. Sebagai cadangan, cari di sistem font apa pun yang dapat menampilkan karakter yang diperlukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Mengatur mode optimasi barcode.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Menunjukkan bahwa semua font akan dikonversi ke versi unicode TTF. Hal ini berguna untuk alasan kompatibilitas dan mengoptimalkan penggunaan font, karena setiap font TTF baru tidak akan memiliki semua simbol dari font sumber, melainkan hanya simbol yang digunakan dalam teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Mendapatkan/mengatur nama default font yang digunakan untuk menggantikan font yang hilang.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Mendapatkan atau mengatur indikasi bahwa kesalahan terkait ketidakhadiran font akan diabaikan. true - berarti kesalahan ketidakhadiran font akan diabaikan. Segmen teks yang merujuk ke sumber daya yang salah akan dilewati selama pemrosesan. false secara default

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Mendapatkan atau mengatur mode kualitas tinggi untuk interpolasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Jumlah maksimum font dalam cache font. Nilai default adalah 10.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Jumlah maksimum simbol dalam cache simbol. Nilai default adalah 100.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Mendapatkan atau mengatur mode optimasi dimensi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Mendapatkan atau mengatur nilai yang digunakan untuk mengubah skala semua gambar pada halaman agar sesuai dengan lebar halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated ScaleImagesToFitPageWidth sudah tidak dipakai lagi. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Mengatur mode di mana font sistem dirender secara native

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

Mengatur nilai yang digunakan untuk melewati kesalahan selama pemrosesan file PDF

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

Penggunaan flag ini mengaktifkan mekanisme font hinting. Font hinting adalah penggunaan instruksi matematis untuk menyesuaikan tampilan font outline. Dalam beberapa kasus mengaktifkan flag ini dapat menyelesaikan masalah keterbacaan teks. Pada saat ini penggunaan flag ini hanya berpengaruh pada font TTF, jika font tersebut digunakan dalam dokumen sumber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Mengatur flag yang menentukan apakah mesin imaging baru digunakan atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated UseNewImagingEngine sudah tidak dipakai lagi |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

Mendapatkan atau mengatur nilai yang digunakan untuk memperbesar atau memperkecil lebar persegi panjang untuk operator AppendRectangle.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |
