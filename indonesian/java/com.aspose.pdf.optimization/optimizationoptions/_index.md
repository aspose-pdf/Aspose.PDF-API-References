---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang menjelaskan algoritma optimisasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources()."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Kelas yang menjelaskan algoritma optimisasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources().

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [all](#all--) | Membuat strategi optimasi dengan semua opsi diaktifkan. Harap perhatikan bahwa hanya opsi yang tidak mengubah fungsi dokumen yang diaktifkan. Misalnya, kompresi gambar dan pelepasan font tidak akan diaktifkan (dan dapat disematkan secara manual). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Jika disetel ke {@link}, semua aliran konten halaman yang tidak terkompresi akan dikompresi menggunakan filter FlateDecode selama {@code Document#OptimizeResources()}. Defaultnya adalah {@link} untuk mempertahankan kompatibilitas mundur. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Sekumpulan opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya. |
| [getImageEncoding](#getImageEncoding--) | Enkode gambar yang akan digunakan. |
| [getImageQuality](#getImageQuality--) | Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan. |
| [getMaxResoultion](#getMaxResoultion--) | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, akan diubah ukurannya. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama. |
| [isCompressImages](#isCompressImages--) | Jika flag ini diatur ke true gambar akan dikompresi dalam dokumen. tingkat kompresi ditentukan dengan properti ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Jika flag ini diatur ke {@code }, objek Pdf akan dipaketkan ke dalam Objest Streams dan dikompresi untuk mengurangi ukuran file pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Jika flag ini diatur ke true, aliran Resource akan dianalisis. Jika aliran duplikat ditemukan (yaitu jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. Hal ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Hapus informasi pribadi (info potongan halaman). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (yaitu objek yang tidak memiliki referensi apa pun) akan dihapus dari dokumen. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Jika flag ini diatur ke true, setiap sumber daya akan diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut akan dihapus. Hal ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen. |
| [isResizeImages](#isResizeImages--) | Jika flag ini diatur ke true dan CompressImages adalah true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan. |
| [isSubsetFonts](#isSubsetFonts--) | Font akan dikonversi menjadi subset jika diatur ke true. |
| [isUnembedFonts](#isUnembedFonts--) | Jadikan font tidak tertanam jika diatur ke true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Jika disetel ke {@link}, semua aliran konten halaman yang tidak terkompresi akan dikompresi menggunakan filter FlateDecode selama {@code Document#OptimizeResources()}. Defaultnya adalah {@link} untuk mempertahankan kompatibilitas mundur. |
| [setCompressImages](#setCompressImages-boolean-) | Jika flag ini diatur ke true gambar akan dikompresi dalam dokumen. tingkat kompresi ditentukan dengan properti ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Jika flag ini diatur ke {@code }, objek Pdf akan dipaketkan ke dalam Objest Streams dan dikompresi untuk mengurangi ukuran file pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Sekumpulan opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya. |
| [setImageEncoding](#setImageEncoding-int-) | Enkode gambar yang akan digunakan. |
| [setImageQuality](#setImageQuality-int-) | Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Jika flag ini diatur ke true, aliran Resource akan dianalisis. Jika aliran duplikat ditemukan (yaitu jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. Hal ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali). |
| [setMaxResoultion](#setMaxResoultion-int-) | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, akan diubah ukurannya. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Hapus informasi pribadi (info potongan halaman). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (yaitu objek yang tidak memiliki referensi apa pun) akan dihapus dari dokumen. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Jika flag ini diatur ke true, setiap sumber daya akan diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut akan dihapus. Hal ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen. |
| [setResizeImages](#setResizeImages-boolean-) | Jika flag ini diatur ke true dan CompressImages adalah true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Font akan dikonversi menjadi subset jika diatur ke true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Jadikan font tidak tertanam jika diatur ke true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Membuat strategi optimasi dengan semua opsi diaktifkan. Harap perhatikan bahwa hanya opsi yang tidak mengubah fungsi dokumen yang diaktifkan. Misalnya, kompresi gambar dan pelepasan font tidak akan diaktifkan (dan dapat disematkan secara manual).

**Returns:**
Objek OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Jika disetel ke {@link}, semua aliran konten halaman yang tidak terkompresi akan dikompresi menggunakan filter FlateDecode selama {@code Document#OptimizeResources()}. Defaultnya adalah {@link} untuk mempertahankan kompatibilitas mundur.

**Returns:**
nilai boolean

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Sekumpulan opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya.

**Returns:**
Instansi ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Enkode gambar yang akan digunakan.

**Returns:**
Elemen ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan.

**Returns:**
nilai int @deprecated Silakan gunakan ImageCompressionOptions.ImageQuality sebagai gantinya.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, akan diubah ukurannya.

**Returns:**
nilai int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama.

**Returns:**
nilai boolean

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Jika flag ini diatur ke true gambar akan dikompresi dalam dokumen. tingkat kompresi ditentukan dengan properti ImageQuality.

**Returns:**
nilai boolean @deprecated Silakan gunakan ImageCompressionOptions.CompressImages sebagai gantinya.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Jika flag ini diatur ke {@code }, objek Pdf akan dipaketkan ke dalam Objest Streams dan dikompresi untuk mengurangi ukuran file pdf.

**Returns:**
nilai boolean

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Jika flag ini diatur ke true, aliran Resource akan dianalisis. Jika aliran duplikat ditemukan (yaitu jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. Hal ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali).

**Returns:**
nilai boolean

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Hapus informasi pribadi (info potongan halaman).

**Returns:**
nilai boolean

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (yaitu objek yang tidak memiliki referensi apa pun) akan dihapus dari dokumen.

**Returns:**
nilai boolean

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Jika flag ini diatur ke true, setiap sumber daya akan diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut akan dihapus. Hal ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen.

**Returns:**
nilai boolean

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Jika flag ini diatur ke true dan CompressImages adalah true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan.

**Returns:**
nilai boolean @deprecated Silakan gunakan ImageCompressionOptions.ResizeImages sebagai gantinya.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Font akan dikonversi menjadi subset jika diatur ke true.

**Returns:**
nilai boolean

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Jadikan font tidak tertanam jika diatur ke true.

**Returns:**
nilai boolean

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Jika disetel ke {@link}, semua aliran konten halaman yang tidak terkompresi akan dikompresi menggunakan filter FlateDecode selama {@code Document#OptimizeResources()}. Defaultnya adalah {@link} untuk mempertahankan kompatibilitas mundur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Jika flag ini diatur ke true gambar akan dikompresi dalam dokumen. tingkat kompresi ditentukan dengan properti ImageQuality.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated Silakan gunakan ImageCompressionOptions.CompressImages sebagai gantinya. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Jika flag ini diatur ke {@code }, objek Pdf akan dipaketkan ke dalam Objest Streams dan dikompresi untuk mengurangi ukuran file pdf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Sekumpulan opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Enkode gambar yang akan digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @deprecated Silakan gunakan ImageCompressionOptions.ImageQuality sebagai gantinya. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Jika flag ini diatur ke true, aliran Resource akan dianalisis. Jika aliran duplikat ditemukan (yaitu jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. Hal ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, akan diubah ukurannya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Hapus informasi pribadi (info potongan halaman).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (yaitu objek yang tidak memiliki referensi apa pun) akan dihapus dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Jika flag ini diatur ke true, setiap sumber daya akan diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut akan dihapus. Hal ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Jika flag ini diatur ke true dan CompressImages adalah true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated Silakan gunakan ImageCompressionOptions.ResizeImages sebagai gantinya. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Font akan dikonversi menjadi subset jika diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Jadikan font tidak tertanam jika diatur ke true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
