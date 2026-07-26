---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mengkapsulkan hasil operasi yang mencoba mengekstrak konten tidak bertanda tangan dari dokumen PDF. Kelas ini menyediakan informasi tentang keberhasilan operasi, detailnya."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Mengenkapsulasi hasil operasi yang mencoba mengekstrak konten yang tidak ditandatangani dari dokumen PDF. Kelas ini menyediakan informasi tentang keberhasilan operasi, detail konten yang tidak ditandatangani, pesan yang menggambarkan hasil, dan status cakupan tanda tangan dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCoverage](#getCoverage--) | Mendapatkan nilai yang menunjukkan sejauh mana dokumen ditandatangani dengan tanda tangan digital yang valid. |
| [getMessage](#getMessage--) | Mendapatkan pesan yang menggambarkan hasil operasi. |
| [getSuccess](#getSuccess--) | Mendapatkan nilai yang menunjukkan apakah operasi pengambilan konten tidak bertanda tangan dari dokumen berhasil. |
| [getUnsignedContent](#getUnsignedContent--) | Mendapatkan konten tidak bertanda tangan. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Mendapatkan nilai yang menunjukkan sejauh mana dokumen ditandatangani dengan tanda tangan digital yang valid.

**Returns:**
nilai yang menunjukkan sejauh mana dokumen ditandatangani dengan tanda tangan digital yang valid.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Mendapatkan pesan yang menggambarkan hasil operasi.

**Returns:**
pesan yang menggambarkan hasil operasi.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Mendapatkan nilai yang menunjukkan apakah operasi pengambilan konten tidak bertanda tangan dari dokumen berhasil.

**Returns:**
nilai yang menunjukkan apakah operasi pengambilan konten tidak bertanda tangan dari dokumen berhasil.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Mendapatkan konten tidak bertanda tangan.

**Returns:**
konten tidak bertanda tangan.
