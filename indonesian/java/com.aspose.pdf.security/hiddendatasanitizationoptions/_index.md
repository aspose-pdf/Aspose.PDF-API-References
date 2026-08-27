---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi konfigurasi untuk membersihkan data tersembunyi dalam dokumen."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Mewakili opsi konfigurasi untuk membersihkan data tersembunyi dalam dokumen.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [all](#all--) | Membuat instance baru dari kelas {@link HiddenDataSanitizationOptions} dengan semua opsi diatur untuk sanitasi. Ini termasuk mengaktifkan penghapusan anotasi, JavaScript, metadata, lampiran, indeks pencarian, informasi pribadi, pelapisan formulir dan lapisan, sambil menonaktifkan opsi untuk mengonversi halaman menjadi gambar. Konfigurasi opsional seperti {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) atau {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) dapat dimodifikasi secara manual setelah mendapatkan instance, karena tidak aktif secara default. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Mendapatkan opsi untuk mengonversi halaman menjadi gambar. Jika opsi ini diaktifkan, opsi ImageCompressionOptions akan diabaikan. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. Konversi halaman menjadi gambar akan terjadi setelah membersihkan data tersembunyi utama, yang dikendalikan oleh opsi lain. |
| [getFlattenForms](#getFlattenForms--) | Mendapatkan nilai yang menunjukkan apakah formulir dalam dokumen harus dilapisi selama proses sanitasi. Melapisi formulir mengubah bidang formulir interaktif menjadi konten statis, membuatnya tidak dapat diedit atau diisi. |
| [getFlattenLayers](#getFlattenLayers--) | Mendapatkan opsi untuk melapisi lapisan dalam dokumen PDF. Ketika diaktifkan, semua lapisan dalam dokumen digabung menjadi satu lapisan, menghapus struktur terpisahnya. Opsi ini berguna untuk menyaring dokumen dengan menyederhanakan kontennya dan memastikan tidak ada data tersembunyi yang berada di dalam lapisan. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Mendapatkan opsi konversi gambar dokumen. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. |
| [getImageDpi](#getImageDpi--) | Mendapatkan opsi untuk menyelesaikan gambar halaman selama konversi. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Mendapatkan nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen. Ketika diaktifkan, semua anotasi yang ada dalam dokumen akan dihapus selama proses sanitasi. Anotasi redaksi akan diterapkan. |
| [getRemoveAttachments](#getRemoveAttachments--) | Mendapatkan opsi untuk menghapus semua file terlampir dari dokumen. Ketika diaktifkan, ini memastikan bahwa semua lampiran dalam PDF dihilangkan selama proses sanitasi. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Mendapatkan nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen. Opsi ini berguna untuk menghilangkan potensi kerentanan keamanan yang diperkenalkan oleh skrip yang disematkan. |
| [getRemoveMetadata](#getRemoveMetadata--) | Mendapatkan opsi untuk menghapus metadata dari dokumen. Jika diatur ke true, metadata seperti properti dokumen dan informasi metadata tersemat tambahan akan dihapus selama sanitasi. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Mendapatkan nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen. Mengaktifkan penghapusan indeks pencarian tersemat dan data pribadi untuk meningkatkan keamanan dan privasi dokumen. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Mengatur opsi untuk mengonversi halaman menjadi gambar. Jika opsi ini diaktifkan, opsi ImageCompressionOptions akan diabaikan. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. Konversi halaman menjadi gambar akan terjadi setelah membersihkan data tersembunyi utama, yang dikendalikan oleh opsi lain. |
| [setFlattenForms](#setFlattenForms-boolean-) | Mengatur nilai yang menunjukkan apakah formulir dalam dokumen harus dilapisi selama proses sanitasi. Melapisi formulir mengubah bidang formulir interaktif menjadi konten statis, membuatnya tidak dapat diedit atau diisi. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Mengatur opsi untuk melapisi lapisan dalam dokumen PDF. Ketika diaktifkan, semua lapisan dalam dokumen digabung menjadi satu lapisan, menghapus struktur terpisahnya. Opsi ini berguna untuk menyaring dokumen dengan menyederhanakan kontennya dan memastikan tidak ada data tersembunyi yang berada di dalam lapisan. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Mengatur opsi konversi gambar dokumen. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. |
| [setImageDpi](#setImageDpi-int-) | Mengatur opsi untuk menyelesaikan gambar halaman selama konversi. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Mengatur nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen. Ketika diaktifkan, semua anotasi yang ada dalam dokumen akan dihapus selama proses sanitasi. Anotasi redaksi akan diterapkan. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Mengatur opsi untuk menghapus semua file terlampir dari dokumen. Ketika diaktifkan, opsi ini memastikan bahwa semua lampiran dalam PDF dihilangkan selama proses sanitasi. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Mengatur nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen. Opsi ini berguna untuk menghilangkan potensi kerentanan keamanan yang diperkenalkan oleh skrip yang disematkan. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Mengatur opsi untuk menghapus metadata dari dokumen. Jika diatur ke true, metadata seperti properti dokumen dan informasi metadata tambahan yang disematkan akan dihapus selama proses sanitasi. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Mengatur nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen. Mengaktifkan penghapusan indeks pencarian yang disematkan dan data pribadi untuk meningkatkan keamanan dan privasi dokumen. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Membuat instance baru dari kelas {@link HiddenDataSanitizationOptions} dengan semua opsi diatur untuk sanitasi. Ini termasuk mengaktifkan penghapusan anotasi, JavaScript, metadata, lampiran, indeks pencarian, informasi pribadi, pelapisan formulir dan lapisan, sambil menonaktifkan opsi untuk mengonversi halaman menjadi gambar. Konfigurasi opsional seperti {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) atau {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) dapat dimodifikasi secara manual setelah mendapatkan instance, karena tidak aktif secara default.

**Returns:**
Sebuah instance {@link HiddenDataSanitizationOptions} dengan semua opsi sanitasi yang telah dikonfigurasi sebelumnya.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Mendapatkan opsi untuk mengonversi halaman menjadi gambar. Jika opsi ini diaktifkan, opsi ImageCompressionOptions akan diabaikan. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. Konversi halaman menjadi gambar akan terjadi setelah membersihkan data tersembunyi utama, yang dikendalikan oleh opsi lain.

**Returns:**
opsi untuk mengonversi halaman menjadi gambar.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Mendapatkan nilai yang menunjukkan apakah formulir dalam dokumen harus dilapisi selama proses sanitasi. Melapisi formulir mengubah bidang formulir interaktif menjadi konten statis, membuatnya tidak dapat diedit atau diisi.

**Returns:**
nilai yang menunjukkan apakah formulir dalam dokumen harus dilapiskan selama proses sanitasi.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Mendapatkan opsi untuk melapisi lapisan dalam dokumen PDF. Ketika diaktifkan, semua lapisan dalam dokumen digabung menjadi satu lapisan, menghapus struktur terpisahnya. Opsi ini berguna untuk menyaring dokumen dengan menyederhanakan kontennya dan memastikan tidak ada data tersembunyi yang berada di dalam lapisan.

**Returns:**
opsi untuk melapiskan lapisan dalam dokumen PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Mendapatkan opsi konversi gambar dokumen. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan.

**Returns:**
opsi konversi gambar dokumen.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Mendapatkan opsi untuk menyelesaikan gambar halaman selama konversi.

**Returns:**
opsi untuk menyelesaikan gambar halaman selama konversi.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Mendapatkan nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen. Ketika diaktifkan, semua anotasi yang ada dalam dokumen akan dihapus selama proses sanitasi. Anotasi redaksi akan diterapkan.

**Returns:**
nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Mendapatkan opsi untuk menghapus semua file terlampir dari dokumen. Ketika diaktifkan, ini memastikan bahwa semua lampiran dalam PDF dihilangkan selama proses sanitasi.

**Returns:**
opsi untuk menghapus semua file terlampir dari dokumen.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Mendapatkan nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen. Opsi ini berguna untuk menghilangkan potensi kerentanan keamanan yang diperkenalkan oleh skrip yang disematkan.

**Returns:**
nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Mendapatkan opsi untuk menghapus metadata dari dokumen. Jika diatur ke true, metadata seperti properti dokumen dan informasi metadata tersemat tambahan akan dihapus selama sanitasi.

**Returns:**
opsi untuk menghapus metadata dari dokumen.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Mendapatkan nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen. Mengaktifkan penghapusan indeks pencarian tersemat dan data pribadi untuk meningkatkan keamanan dan privasi dokumen.

**Returns:**
nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Mengatur opsi untuk mengonversi halaman menjadi gambar. Jika opsi ini diaktifkan, opsi ImageCompressionOptions akan diabaikan. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan. Konversi halaman menjadi gambar akan terjadi setelah membersihkan data tersembunyi utama, yang dikendalikan oleh opsi lain.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opsi untuk mengonversi halaman menjadi gambar. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Mengatur nilai yang menunjukkan apakah formulir dalam dokumen harus dilapisi selama proses sanitasi. Melapisi formulir mengubah bidang formulir interaktif menjadi konten statis, membuatnya tidak dapat diedit atau diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang menunjukkan apakah formulir dalam dokumen harus dilapiskan selama proses sanitasi. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Mengatur opsi untuk melapisi lapisan dalam dokumen PDF. Ketika diaktifkan, semua lapisan dalam dokumen digabung menjadi satu lapisan, menghapus struktur terpisahnya. Opsi ini berguna untuk menyaring dokumen dengan menyederhanakan kontennya dan memastikan tidak ada data tersembunyi yang berada di dalam lapisan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opsi untuk melapiskan lapisan dalam dokumen PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Mengatur opsi konversi gambar dokumen. Opsi harus diaktifkan secara manual saat menggunakan metode {@code #All()} jika diperlukan.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Mengatur opsi untuk menyelesaikan gambar halaman selama konversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opsi untuk menyelesaikan gambar halaman selama konversi. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Mengatur nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen. Ketika diaktifkan, semua anotasi yang ada dalam dokumen akan dihapus selama proses sanitasi. Anotasi redaksi akan diterapkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang menunjukkan apakah anotasi harus dihapus dari dokumen. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Mengatur opsi untuk menghapus semua file terlampir dari dokumen. Ketika diaktifkan, opsi ini memastikan bahwa semua lampiran dalam PDF dihilangkan selama proses sanitasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opsi untuk menghapus semua file terlampir dari dokumen. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Mengatur nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen. Opsi ini berguna untuk menghilangkan potensi kerentanan keamanan yang diperkenalkan oleh skrip yang disematkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang menunjukkan apakah JavaScript dan tindakan terkait harus dihapus dari dokumen. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Mengatur opsi untuk menghapus metadata dari dokumen. Jika diatur ke true, metadata seperti properti dokumen dan informasi metadata tambahan yang disematkan akan dihapus selama proses sanitasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | opsi untuk menghapus metadata dari dokumen. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Mengatur nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen. Mengaktifkan penghapusan indeks pencarian yang disematkan dan data pribadi untuk meningkatkan keamanan dan privasi dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai yang menunjukkan apakah indeks pencarian dan informasi pribadi harus dihapus dari dokumen. |
