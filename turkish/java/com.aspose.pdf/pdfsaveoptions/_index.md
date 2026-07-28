---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Pdf formatına dışa aktarma için kaydetme seçenekleri."
type: docs
weight: 3790
url: /tr/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Pdf formatına dışa aktarma için kaydetme seçenekleri.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Bilgisayarda bulunmayan yazı tipleri için varsayılan olarak kullanılan yazı tipi adı. PDF olarak kaydedilen PDF belgesi, belgede ve cihazda mevcut olmayan yazı tipleri içerdiğinde, API bu yazı tiplerini varsayılan yazı tipiyle değiştirir (eğer cihazda {@code DefaultFontName} adlı yazı tipi bulunursa). |
| [getTempPath](#getTempPath--) | Geçici dosyalar için yol. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Bilgisayarda bulunmayan yazı tipleri için varsayılan olarak kullanılan yazı tipi adı. PDF olarak kaydedilen PDF belgesi, belgede ve cihazda mevcut olmayan yazı tipleri içerdiğinde, API bu yazı tiplerini varsayılan yazı tipiyle değiştirir (eğer cihazda {@code DefaultFontName} adlı yazı tipi bulunursa). |
| [setTempPath](#setTempPath-java.lang.String-) | Geçici dosyalar için yol. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Yapıcı

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Bilgisayarda bulunmayan yazı tipleri için varsayılan olarak kullanılan yazı tipi adı. PDF olarak kaydedilen PDF belgesi, belgede ve cihazda mevcut olmayan yazı tipleri içerdiğinde, API bu yazı tiplerini varsayılan yazı tipiyle değiştirir (eğer cihazda {@code DefaultFontName} adlı yazı tipi bulunursa).

**Returns:**
String değeri

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Geçici dosyalar için yol.

**Returns:**
String değeri

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Bilgisayarda bulunmayan yazı tipleri için varsayılan olarak kullanılan yazı tipi adı. PDF olarak kaydedilen PDF belgesi, belgede ve cihazda mevcut olmayan yazı tipleri içerdiğinde, API bu yazı tiplerini varsayılan yazı tipiyle değiştirir (eğer cihazda {@code DefaultFontName} adlı yazı tipi bulunursa).

### setTempPath {#setTempPath-java.lang.String-}
Geçici dosyalar için yol.
