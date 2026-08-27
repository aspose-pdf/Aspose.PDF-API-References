---
title: "Stempel"
linktitle: "Stempel"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili stempel."
type: docs
weight: 700
url: /id/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Kelas yang mewakili stempel.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Stamp](#Stamp--) | Konstruktor untuk objek Stamp. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Mengatur gambar yang akan digunakan sebagai stamp. |
| [bindImage](#bindImage-java.lang.String-) | <p> Mengatur gambar sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Mengatur teks sebagai stempel. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Halaman pertama akan digunakan sebagai stempel. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Mengatur status teks dari teks stempel. |
| [close](#close--) | Menutup instance ini |
| [getBlendingSpace](#getBlendingSpace--) | Mendapatkan nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman. |
| [getOpacity](#getOpacity--) | Mendapatkan opasitas stempel. |
| [getPageNumber](#getPageNumber--) | Mendapatkan nomor halaman. |
| [getPages](#getPages--) | Mendapatkan array dengan nomor halaman yang akan dipengaruhi oleh stempel. |
| [getQuality](#getQuality--) | Mendapatkan kualitas stempel gambar dalam persen. Nilai yang valid 0..100%. |
| [getRotation](#getRotation--) | Mendapatkan rotasi stempel dalam derajat. |
| [getStampId](#getStampId--) | Mendapatkan pengidentifikasi stempel. |
| [isBackground](#isBackground--) | Mendapatkan status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang disegel. Secara default diatur ke false. |
| [setBackground](#setBackground-boolean-) | Mengatur status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang disegel. Secara default diatur ke false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Mengatur nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman. |
| [setImageSize](#setImageSize-float-float-) | Mengatur ukuran stempel gambar. Gambar akan diubah skala sesuai nilai yang ditentukan. |
| [setOpacity](#setOpacity-float-) | Mengatur opasitas stempel. |
| [setOrigin](#setOrigin-float-float-) | Mengatur posisi pada halaman tempat stempel akan ditempatkan. |
| [setPageNumber](#setPageNumber-int-) | Mengatur nomor halaman. |
| [setPages](#setPages-int:A-) | <p> Mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. Jika Pages = null semua halaman dokumen akan dipengaruhi. </p> |
| [setQuality](#setQuality-int-) | Mengatur kualitas stempel gambar dalam persen. Nilai yang valid 0..100%. |
| [setRotation](#setRotation-float-) | <p> Mendapatkan atau mengatur rotasi stempel dalam derajat. </p> |
| [setStampId](#setStampId-int-) | Mengatur pengidentifikasi stempel. |

### Stamp {#Stamp--}
```
public Stamp()
```

Konstruktor untuk objek Stamp.

### bindImage {#bindImage-java.io.InputStream-}
Mengatur gambar yang akan digunakan sebagai stamp.

### bindImage {#bindImage-java.lang.String-}
<p> Mengatur gambar sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Mengatur teks sebagai stempel.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Mengatur file PDF dan nomor halaman yang akan digunakan sebagai stempel. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //Halaman pertama akan digunakan sebagai stempel. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Mengatur status teks dari teks stempel.

### close {#close--}
```
public void close()
```

Menutup instance ini

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Mendapatkan nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman.

**Returns:**
nilai int @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Mendapatkan opasitas stempel.

**Returns:**
nilai float

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Mendapatkan nomor halaman.

**Returns:**
nilai int

### getPages {#getPages--}
```
public int[] getPages()
```

Mendapatkan array dengan nomor halaman yang akan dipengaruhi oleh stempel.

**Returns:**
array int

### getQuality {#getQuality--}
```
public int getQuality()
```

Mendapatkan kualitas stempel gambar dalam persen. Nilai yang valid 0..100%.

**Returns:**
nilai int

### getRotation {#getRotation--}
```
public float getRotation()
```

Mendapatkan rotasi stempel dalam derajat.

**Returns:**
nilai float

### getStampId {#getStampId--}
```
public int getStampId()
```

Mendapatkan pengidentifikasi stempel.

**Returns:**
nilai int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Mendapatkan status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang disegel. Secara default diatur ke false.

**Returns:**
nilai boolean

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Mengatur status latar belakang. Jika true, stempel akan ditempatkan sebagai latar belakang halaman yang disegel. Secara default diatur ke false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Mengatur nilai BlendingColorSpace yang mendefinisikan ruang warna yang digunakan untuk melakukan operasi transparansi dan pencampuran pada halaman.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Mengatur ukuran stempel gambar. Gambar akan diubah skala sesuai nilai yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lebar |  | Lebar gambar. |
| tinggi |  | Tinggi gambar. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Mengatur opasitas stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Mengatur posisi pada halaman tempat stempel akan ditempatkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| originX |  | Koordinat X dari cap. |
| originY |  | Koordinat Y dari cap. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Mengatur nomor halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Mengatur array dengan nomor halaman yang akan dipengaruhi oleh stempel. Jika Pages = null semua halaman dokumen akan dipengaruhi. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Mengatur kualitas stempel gambar dalam persen. Nilai yang valid 0..100%.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Mendapatkan atau mengatur rotasi stempel dalam derajat. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Mengatur pengidentifikasi stempel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
