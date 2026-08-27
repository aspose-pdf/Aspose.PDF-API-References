---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas MemoryExtender. Menggunakan file besar pada sistem dengan memori heap terbatas, dapat diaktifkan untuk menggunakan ruang disk sebagai memori swap sementara."
type: docs
weight: 3020
url: /id/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

Mewakili kelas MemoryExtender. Menggunakan file besar pada sistem dengan memori heap terbatas, dapat diaktifkan untuk menggunakan ruang disk sebagai memori swap sementara.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | Dapatkan analisator cache khusus. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | Waktu maksimum untuk merender elemen tunggal yang digunakan dalam konversi halaman ke gambar. Nilai default 10000 milidetik. Hanya digunakan ketika isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | Dapatkan status untuk bidang EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | Diaktifkan untuk menggunakan OptimizedMemoryStream sebagai penyimpanan memori default. Diperlukan untuk bekerja dengan dokumen besar lebih dari 2 GB. Nilai default adalah FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | Diaktifkan untuk menggunakan OptimizedMemoryStream sebagai penyimpanan memori default. Diperlukan untuk bekerja dengan dokumen besar lebih dari 2 GB. Nilai default adalah FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | Diaktifkan untuk melewatkan objek dengan konsumsi memori tinggi dalam proses rendering ketika memori heap kurang. Nilai default adalah FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | Diaktifkan untuk menggunakan ruang disk sebagai memori swap sementara. Nilai default adalah FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | Menampilkan nilai yang menunjukkan apakah folder yang hilang harus dibuat secara otomatis. <p>Jika disetel ke {@code true}, metode Aspose yang menyimpan dengan path akan mencoba membuat struktur folder target jika belum ada. <p>Nilai default adalah {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | Terapkan analisator cache khusus baru. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | Waktu maksimum untuk merender elemen tunggal yang digunakan dalam konversi halaman ke gambar. Nilai default 10000 milidetik. Hanya digunakan ketika isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | Setel status baru untuk bidang EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | Setel flag untuk mengaktifkan melewatkan objek dengan konsumsi memori tinggi dalam rendering ketika memori heap kurang. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | Atur flag apakah ruang disk diaktifkan untuk digunakan sebagai memori swap sementara. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | Mengatur nilai yang menunjukkan apakah folder yang hilang harus dibuat secara otomatis. <p>Jika disetel ke {@code true}, metode Aspose yang menyimpan dengan path akan mencoba membuat struktur folder target jika belum ada. <p>Nilai default adalah {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

Dapatkan analisator cache khusus.

**Returns:**
objek CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

Waktu maksimum untuk merender elemen tunggal yang digunakan dalam konversi halaman ke gambar. Nilai default 10000 milidetik. Hanya digunakan ketika isSkipHeavyContentEnabled() == true.

**Returns:**
nilai int Jumlah milidetik

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

Dapatkan status untuk bidang EnabledMultiPageImageCache.

**Returns:**
nilai boolean

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

Diaktifkan untuk menggunakan OptimizedMemoryStream sebagai penyimpanan memori default. Diperlukan untuk bekerja dengan dokumen besar lebih dari 2 GB. Nilai default adalah FALSE.

**Returns:**
nilai boolean

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

Diaktifkan untuk menggunakan OptimizedMemoryStream sebagai penyimpanan memori default. Diperlukan untuk bekerja dengan dokumen besar lebih dari 2 GB. Nilai default adalah FALSE.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

Diaktifkan untuk melewatkan objek dengan konsumsi memori tinggi dalam proses rendering ketika memori heap kurang. Nilai default adalah FALSE.

**Returns:**
nilai boolean

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

Diaktifkan untuk menggunakan ruang disk sebagai memori swap sementara. Nilai default adalah FALSE.

**Returns:**
nilai boolean

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

Menampilkan nilai yang menunjukkan apakah folder yang hilang harus dibuat secara otomatis. <p>Jika disetel ke {@code true}, metode Aspose yang menyimpan dengan path akan mencoba membuat struktur folder target jika belum ada. <p>Nilai default adalah {@code false}.

**Returns:**
nilai boolean

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
Terapkan analisator cache khusus baru.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

Waktu maksimum untuk merender elemen tunggal yang digunakan dalam konversi halaman ke gambar. Nilai default 10000 milidetik. Hanya digunakan ketika isSkipHeavyContentEnabled() == true.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int Jumlah milidetik |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

Setel status baru untuk bidang EnabledMultiPageImageCache.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | nilai boolean |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

Setel flag untuk mengaktifkan melewatkan objek dengan konsumsi memori tinggi dalam rendering ketika memori heap kurang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

Atur flag apakah ruang disk diaktifkan untuk digunakan sebagai memori swap sementara.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

Mengatur nilai yang menunjukkan apakah folder yang hilang harus dibuat secara otomatis. <p>Jika disetel ke {@code true}, metode Aspose yang menyimpan dengan path akan mencoba membuat struktur folder target jika belum ada. <p>Nilai default adalah {@code false}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
