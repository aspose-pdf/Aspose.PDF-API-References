---
title: "UnsignedContentAbsorber.UnsignedContent"
linktitle: "UnsignedContentAbsorber.UnsignedContent"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mengkapsulkan elemen konten yang tidak ditandatangani yang diekstrak dari dokumen PDF. Kelas ini menyediakan akses ke halaman, bidang formulir, XForms, dan anotasi yang merupakan bagian dari yang tidak ditandatangani."
type: docs
weight: 50
url: /id/java/com.aspose.pdf.security/unsignedcontentabsorber.unsignedcontent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.UnsignedContent

```
public static final class UnsignedContentAbsorber.UnsignedContent extends Object
```

Mengenkapsulasi elemen konten tidak ditandatangani yang diekstrak dari dokumen PDF. Kelas ini menyediakan akses ke halaman, bidang formulir, XForms, dan anotasi yang merupakan bagian dari konten tidak ditandatangani dalam dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAnnotations](#getAnnotations--) | Mendapatkan kamus anotasi yang dimodifikasi yang mungkin telah diubah atau ditambahkan. |
| [getForms](#getForms--) | Mendapatkan bidang formulir yang telah diubah atau ditambahkan secara inkremental. |
| [getPages](#getPages--) | Mendapatkan daftar halaman yang kontennya belum ditandatangani atau telah diubah secara inkremental. Halaman dianggap dimodifikasi dan XForms tidak diperiksa serta tidak muncul dalam daftar XForms. |
| [getXForms](#getXForms--) | Mendapatkan kamus objek XForm yang dimodifikasi yang mungkin telah berubah, meskipun halaman itu sendiri tidak berubah (tidak ada dalam daftar Pages). |
| [setXForms](#setXForms-java.util.HashMap-) | Sebuah kamus objek XForm yang dimodifikasi yang mungkin telah berubah, meskipun halaman itu sendiri tidak berubah (tidak ada dalam daftar Pages). |

### getAnnotations {#getAnnotations--}
```
public final HashMap < Integer , Annotation > getAnnotations()
```

Mendapatkan kamus anotasi yang dimodifikasi yang mungkin telah diubah atau ditambahkan.

**Returns:**
sebuah kamus anotasi yang dimodifikasi yang mungkin telah berubah atau ditambahkan.

### getForms {#getForms--}
```
public final List < WidgetAnnotation > getForms()
```

Mendapatkan bidang formulir yang telah diubah atau ditambahkan secara inkremental.

**Returns:**
field formulir yang telah diubah atau ditambahkan secara inkremental.

### getPages {#getPages--}
```
public final List < Page > getPages()
```

Mendapatkan daftar halaman yang kontennya belum ditandatangani atau telah diubah secara inkremental. Halaman dianggap dimodifikasi dan XForms tidak diperiksa serta tidak muncul dalam daftar XForms.

**Returns:**
sebuah daftar halaman yang kontennya belum ditandatangani atau telah diubah secara inkremental.

### getXForms {#getXForms--}
```
public final HashMap < Integer , XForm > getXForms()
```

Mendapatkan kamus objek XForm yang dimodifikasi yang mungkin telah berubah, meskipun halaman itu sendiri tidak berubah (tidak ada dalam daftar Pages).

**Returns:**
sebuah kamus objek XForm yang dimodifikasi yang mungkin telah berubah, meskipun halaman itu sendiri tidak berubah (tidak ada dalam daftar Pages).

### setXForms {#setXForms-java.util.HashMap-}
Sebuah kamus objek XForm yang dimodifikasi yang mungkin telah berubah, meskipun halaman itu sendiri tidak berubah (tidak ada dalam daftar Pages).
