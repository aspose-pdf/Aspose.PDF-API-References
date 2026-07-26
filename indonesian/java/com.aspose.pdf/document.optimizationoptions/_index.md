---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang menjelaskan algoritma optimasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources(). @deprecated Kelas ini sudah usang. Silakan."
type: docs
weight: 1110
url: /id/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

Kelas yang menjelaskan algoritma optimisasi dokumen. Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources(). @deprecated Kelas ini sudah usang. Silakan gunakan com.aspose.pdf.optimization.OptimizationOptions sebagai gantinya.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | Usang. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [all](#all--) | Membuat strategi optimasi dengan semua opsi diaktifkan. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | Menentukan dimensi maksimum gambar. Jika lebar atau tinggi gambar yang ada lebih besar dari nilai ini - ukuran gambar akan dikurangi secara proporsional. |
| [getResolution](#getResolution--) | Menentukan dpi gambar baru ketika flag CompressIamges digunakan. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | Menentukan dimensi maksimum gambar. Jika lebar atau tinggi gambar yang ada lebih besar dari nilai ini - ukuran gambar akan dikurangi secara proporsional. |
| [setResolution](#setResolution-int-) | Menentukan dpi gambar baru ketika flag CompressIamges digunakan. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

Usang.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

Membuat strategi optimasi dengan semua opsi diaktifkan.

**Returns:**
Objek OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

Menentukan dimensi maksimum gambar. Jika lebar atau tinggi gambar yang ada lebih besar dari nilai ini - ukuran gambar akan dikurangi secara proporsional.

**Returns:**
dimensi maksimum gambar

### getResolution {#getResolution--}
```
public int getResolution()
```

Menentukan dpi gambar baru ketika flag CompressIamges digunakan.

**Returns:**
resolusi gambar

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

Menentukan dimensi maksimum gambar. Jika lebar atau tinggi gambar yang ada lebih besar dari nilai ini - ukuran gambar akan dikurangi secara proporsional.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dimensi |  | dimensi maksimum gambar |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

Menentukan dpi gambar baru ketika flag CompressIamges digunakan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dpi |  | resolusi gambar |
