---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas berisi opsi yang ditetapkan untuk kompresi gambar."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

Kelas berisi opsi yang ditetapkan untuk kompresi gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEncoding](#getEncoding--) | Mendapatkan atau mengatur enkoding yang digunakan untuk menyimpan gambar. |
| [getImageQuality](#getImageQuality--) | Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan. |
| [getMaxResolution](#getMaxResolution--) | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya |
| [getResizeImages](#getResizeImages--) | Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan. |
| [getVersion](#getVersion--) | Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\".) |
| [isCompressImages](#isCompressImages--) | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality. |
| [setEncoding](#setEncoding-int-) | Mendapatkan atau mengatur enkoding yang digunakan untuk menyimpan gambar. |
| [setImageQuality](#setImageQuality-int-) | Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan. |
| [setMaxResolution](#setMaxResolution-int-) | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya |
| [setResizeImages](#setResizeImages-boolean-) | Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan. |
| [setVersion](#setVersion-int-) | Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\".) |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Mendapatkan atau mengatur enkoding yang digunakan untuk menyimpan gambar.

**Returns:**
Elemen ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan.

**Returns:**
nilai int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya

**Returns:**
nilai int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan.

**Returns:**
nilai boolean

### getVersion {#getVersion--}
```
public final int getVersion()
```

Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\".)

**Returns:**
nilai int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality.

**Returns:**
nilai boolean

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Mendapatkan atau mengatur enkoding yang digunakan untuk menyimpan gambar.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Menentukan tingkat kompresi gambar ketika flag CompressImages digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar dari parameter MaxResolution yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Versi algoritma kompresi. Nilai yang mungkin adalah: 1. kompresi standar, 2. cepat (kompresi yang ditingkatkan yang lebih cepat daripada standar tetapi mungkin tidak berlaku untuk semua gambar), 3. campuran (kompresi standar diterapkan pada gambar yang tidak dapat dikompresi oleh algoritma yang lebih cepat, ini dapat memberikan kompresi terbaik tetapi lebih lambat daripada algoritma \"fast\". Versi \"Fast\" tidak berlaku untuk mengubah ukuran gambar (metode standar akan digunakan). Default adalah \"Standard\".)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
