---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas hasil dari membandingkan dua halaman PDF."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Mewakili kelas hasil dari membandingkan dua halaman PDF.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Mengonversi array perbedaan menjadi gambar bitmap menggunakan warna yang ditentukan. |
| [dispose](#dispose--) | Melakukan operasi pembersihan yang diperlukan sebelum objek dihancurkan. |
| [getDestinationImage](#getDestinationImage--) | Mengembalikan bitmap baru yang mewakili gambar tujuan dengan menerapkan array perbedaan ke gambar sumber. |
| [getDifference](#getDifference--) | Mendapatkan array perbedaan. Array ini mirip dengan array data gambar asli yang diperoleh sebagai hasil dari metode LockBits. |
| [getHeight](#getHeight--) | Tinggi perbedaan. |
| [getSourceImage](#getSourceImage--) | Mendapatkan gambar halaman pertama yang dibandingkan. Gambar memiliki format piksel 24bpp. |
| [getStride](#getStride--) | Stride data gambar perbedaan. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Mengonversi array perbedaan menjadi gambar bitmap menggunakan warna yang ditentukan.

### dispose {#dispose--}
```
public final void dispose()
```

Melakukan operasi pembersihan yang diperlukan sebelum objek dihancurkan.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Mengembalikan bitmap baru yang mewakili gambar tujuan dengan menerapkan array perbedaan ke gambar sumber.

**Returns:**
Gambar tujuan.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Mendapatkan array perbedaan. Array ini mirip dengan array data gambar asli yang diperoleh sebagai hasil dari metode LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

Tinggi perbedaan.

**Returns:**
nilai int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Mendapatkan gambar halaman pertama yang dibandingkan. Gambar memiliki format piksel 24bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

Stride data gambar perbedaan.

**Returns:**
nilai int
