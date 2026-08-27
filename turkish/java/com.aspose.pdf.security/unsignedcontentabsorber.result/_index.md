---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir PDF belgesinden imzasız içerik çıkarmaya çalışan bir işlemin sonucunu kapsüller. Bu sınıf, işlemin başarısı hakkında bilgi ve ayrıntılar sağlar."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Bir PDF belgesinden imzasız içerik çıkarmaya çalışan bir işlemin sonucunu kapsüller. Bu sınıf, işlemin başarısı, imzasız içeriğin detayları, sonucu açıklayan bir mesaj ve belgenin imzalarının kapsama durumuyla ilgili bilgi sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCoverage](#getCoverage--) | Belgenin geçerli dijital imzalarla ne kadar kapsandığını gösteren bir değeri alır. |
| [getMessage](#getMessage--) | İşlemin sonucunu açıklayan bir mesajı alır. |
| [getSuccess](#getSuccess--) | Belgeden imzasız içerik alma işleminin başarılı olup olmadığını gösteren bir değeri alır. |
| [getUnsignedContent](#getUnsignedContent--) | İmzasız bir içerik alır. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Belgenin geçerli dijital imzalarla ne kadar kapsandığını gösteren bir değeri alır.

**Returns:**
belgenin geçerli dijital imzalarla ne kadar kapsandığını gösteren bir değer.

### getMessage {#getMessage--}
```
public final String getMessage()
```

İşlemin sonucunu açıklayan bir mesajı alır.

**Returns:**
işlemin sonucunu açıklayan bir mesaj.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Belgeden imzasız içerik alma işleminin başarılı olup olmadığını gösteren bir değeri alır.

**Returns:**
belgeden imzasız içerik alma işleminin başarılı olup olmadığını gösteren bir değer.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

İmzasız bir içerik alır.

**Returns:**
imzasız bir içerik.
