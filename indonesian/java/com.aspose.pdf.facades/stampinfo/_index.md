---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili informasi stempel."
type: docs
weight: 710
url: /id/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Kelas yang mewakili informasi stempel.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getForm](#getForm--) | Mendapatkan XForm dari stempel. |
| [getImage](#getImage--) | Mendapatkan gambar stempel. Mungkin null jika stempel tidak berisi gambar (misalnya untuk stempel teks). |
| [getImageInternal](#getImageInternal--) | Mendapatkan gambar stempel. Mungkin null jika stempel tidak berisi gambar (misalnya untuk stempel teks). |
| [getIndexOnPage](#getIndexOnPage--) | Mendapatkan indeks stempel pada halaman. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang tempat stempel ditempatkan. |
| [getStampId](#getStampId--) | Mendapatkan pengidentifikasi stempel. |
| [getStampType](#getStampType--) | Mendapatkan tipe stempel (gambar / form). |
| [getText](#getText--) | Mendapatkan teks dalam stempel. |
| [getVisible](#getVisible--) | Mendapatkan visibilitas stempel. Jika false maka stempel disembunyikan (dengan HideStampById). Stempel yang disembunyikan dapat dipulihkan dengan ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Mendapatkan XForm dari stempel.

**Returns:**
objek XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Mendapatkan gambar stempel. Mungkin null jika stempel tidak berisi gambar (misalnya untuk stempel teks).

**Returns:**
Objek BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Mendapatkan gambar stempel. Mungkin null jika stempel tidak berisi gambar (misalnya untuk stempel teks).

**Returns:**
objek Image

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Mendapatkan indeks stempel pada halaman.

**Returns:**
nilai int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang tempat stempel ditempatkan.

**Returns:**
elemen Persegi Panjang

### getStampId {#getStampId--}
```
public int getStampId()
```

Mendapatkan pengidentifikasi stempel.

**Returns:**
nilai int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Mendapatkan tipe stempel (gambar / form).

**Returns:**
Elemen StampType @see StampType

### getText {#getText--}
```
public String getText()
```

Mendapatkan teks dalam stempel.

**Returns:**
nilai String

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Mendapatkan visibilitas stempel. Jika false maka stempel disembunyikan (dengan HideStampById). Stempel yang disembunyikan dapat dipulihkan dengan ShowStampById.

**Returns:**
nilai boolean
