---
title: "XImage"
linktitle: "XImage"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili X-Object gambar."
type: docs
weight: 5610
url: /id/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Kelas yang mewakili X-Object gambar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | hanya untuk penggunaan internal |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Menambahkan masker stensil ke XImage. |
| [containsTransparency](#containsTransparency--) | Jika gambar mengandung transparansi maka mengembalikan true; jika tidak, false. |
| [delete](#delete--) | Menghapus gambar dari koleksi induk. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Mengembalikan tipe warna gambar. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Mengembalikan daftar string dengan Teks Alternatif untuk XImage. |
| [getColorType](#getColorType--) | Mengembalikan tipe warna gambar. |
| [getEngineImg](#getEngineImg--) | Objek IPdfImage yang mendeskripsikan gambar. Hanya internal |
| [getFilterType](#getFilterType--) | Mendapatkan tipe filter gambar. |
| [getGrayscaled](#getGrayscaled--) | Mendapatkan versi gambar dalam skala abu-abu. |
| [getHeight](#getHeight--) | Mendapatkan tinggi gambar. |
| [getImage](#getImage--) | Hanya untuk penggunaan internal |
| [getMetadata](#getMetadata--) | Metadata gambar. |
| [getName](#getName--) | Mendapatkan nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen dapat menjadi tidak benar. Harap gunakan metode XImage.Rename dalam kasus ini. |
| [getNameInCollection](#getNameInCollection--) | Mengembalikan nama gambar dalam koleksinya. |
| [getRawBytes](#getRawBytes--) | Mengembalikan byte mentah untuk gambar tanpa mendekode. |
| [getRawImageData](#getRawImageData--) | Mengambil data gambar mentah dari gambar sumber. |
| [getRawParameters](#getRawParameters--) | Mendapatkan parameter gambar mentah |
| [getWidth](#getWidth--) | Mendapatkan lebar gambar. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Mengembalikan true jika primitif adalah gambar. |
| [isImageMask](#isImageMask--) | Mendapatkan flag yang menunjukkan apakah gambar harus diperlakukan sebagai mask gambar (lihat 8.9.6, "Masked Images"). Jika flag ini true, nilai BitsPerComponent harus 1 dan Mask serta ColorSpace tidak boleh ditentukan; area yang tidak dimask akan dilukis menggunakan warna non-stroking saat ini. Nilai default: false. Nilai: True jika gambar adalah mask gambar. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Mengembalikan true jika kedua gambar merujuk ke objek yang sama. |
| [rename](#rename-java.lang.String-) | Mengganti nama gambar dan menggantikan semua referensi ke gambar dengan nama baru |
| [replace](#replace-java.io.InputStream-) | Mengganti gambar ke aliran yang ditentukan dalam {@code image}. * |
| [save](#save-java.io.OutputStream-) | Menyimpan data gambar ke aliran sebagai gambar JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | Menyimpan gambar ke aliran dengan format yang diminta. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Menyimpan gambar ke aliran dengan format yang diminta. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Menyimpan gambar ke aliran dengan format yang diminta. |
| [save](#save-java.io.OutputStream-int-) | Menyimpan gambar ke aliran dengan format yang diminta dengan resolusi yang ditentukan. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Menyimpan gambar ke aliran dengan format yang diminta. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Menyimpan data gambar ke aliran sebagai gambar JPEG dengan resolusi yang ditentukan. |
| [setName](#setName-java.lang.String-) | Mengatur nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen mungkin menjadi tidak benar. Silakan gunakan metode XImage.Rename dalam kasus ini. |
| [toStream](#toStream--) | Mengembalikan aliran gambar asli. |
| [toString](#toString--) | Mengembalikan representasi string properti objek XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Mengatur teks alternatif untuk XImage pada halaman. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
hanya untuk penggunaan internal

### addStencilMask {#addStencilMask-java.io.InputStream-}
Menambahkan masker stensil ke XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Jika gambar mengandung transparansi maka mengembalikan true; jika tidak, false.

**Returns:**
nilai boolean

### delete {#delete--}
```
public void delete()
```

Menghapus gambar dari koleksi induk.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Mengembalikan tipe warna gambar.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Mengembalikan daftar string dengan Teks Alternatif untuk XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Mengembalikan tipe warna gambar.

**Returns:**
Nilai tipe warna.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

Objek IPdfImage yang mendeskripsikan gambar. Hanya internal

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Mendapatkan tipe filter gambar.

**Returns:**
ImageFilterType element

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Mendapatkan versi gambar dalam skala abu-abu.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Mendapatkan tinggi gambar.

**Returns:**
nilai int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Hanya untuk penggunaan internal

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadata gambar.

**Returns:**
Instansi Metadata

### getName {#getName--}
```
public String getName()
```

Mendapatkan nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen dapat menjadi tidak benar. Harap gunakan metode XImage.Rename dalam kasus ini.

**Returns:**
String

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Mengembalikan nama gambar dalam koleksinya.

**Returns:**
Kunci gambar (nama).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Mengembalikan byte mentah untuk gambar tanpa mendekode.

**Returns:**
array byte

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Mengambil data gambar mentah dari gambar sumber.

**Returns:**
Sebuah {@link byte[]} yang berisi data gambar asli.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Mendapatkan parameter gambar mentah

**Returns:**
Instansi RawParameters

### getWidth {#getWidth--}
```
public int getWidth()
```

Mendapatkan lebar gambar.

**Returns:**
nilai int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Mengembalikan true jika primitif adalah gambar.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Mendapatkan flag yang menunjukkan apakah gambar harus diperlakukan sebagai mask gambar (lihat 8.9.6, "Masked Images"). Jika flag ini true, nilai BitsPerComponent harus 1 dan Mask serta ColorSpace tidak boleh ditentukan; area yang tidak dimask akan dilukis menggunakan warna non-stroking saat ini. Nilai default: false. Nilai: True jika gambar adalah mask gambar.

**Returns:**
nilai boolean

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Mengembalikan true jika kedua gambar merujuk ke objek yang sama.

### rename {#rename-java.lang.String-}
Mengganti nama gambar dan menggantikan semua referensi ke gambar dengan nama baru

### replace {#replace-java.io.InputStream-}
Mengganti gambar ke aliran yang ditentukan dalam {@code image}. *

### save {#save-java.io.OutputStream-}
Menyimpan data gambar ke aliran sebagai gambar JPEG.

### save {#save-java.io.OutputStream-float-float-}
Menyimpan gambar ke aliran dengan format yang diminta.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Menyimpan gambar ke aliran dengan format yang diminta.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Menyimpan gambar ke aliran dengan format yang diminta.

### save {#save-java.io.OutputStream-int-}
Menyimpan gambar ke aliran dengan format yang diminta dengan resolusi yang ditentukan.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Menyimpan gambar ke aliran dengan format yang diminta.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Menyimpan data gambar ke aliran sebagai gambar JPEG dengan resolusi yang ditentukan.

### setName {#setName-java.lang.String-}
Mengatur nama gambar. Harap perhatikan bahwa jika Anda mengubah nama gambar yang memiliki referensi dalam konten halaman, dokumen mungkin menjadi tidak benar. Silakan gunakan metode XImage.Rename dalam kasus ini.

### toStream {#toStream--}
```
public InputStream toStream()
```

Mengembalikan aliran gambar asli.

**Returns:**
Aliran gambar asli.

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi string properti objek XImage.

**Returns:**
Instansi String

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Mengatur teks alternatif untuk XImage pada halaman.
