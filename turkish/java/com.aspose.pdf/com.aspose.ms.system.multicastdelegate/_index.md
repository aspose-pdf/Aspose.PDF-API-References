---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Aspose.PDF for Java API Referansı"
description: "Olayları temsil eden sınıf"
type: docs
weight: 740
url: /tr/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

Olayları temsil eden sınıf

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-T-) | Bir delege daha ekle. |
| [assign](#assign-T-) | Yalnızca mevcut delegeyi ekle, diğerlerini temizleyerek. |
| [clear](#clear--) | Delege listesini temizle |
| [isEmpty](#isEmpty--) | İşleyiciler listesi boşsa true döndürür |
| [remove](#remove-T-) | Temsilciyi listeden sil |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

Bir delege daha ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| temsilci |  | İşleyiciler nesnesi |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

Yalnızca mevcut delegeyi ekle, diğerlerini temizleyerek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| temsilci |  | İşleyiciler nesnesi |

### clear {#clear--}
```
public final void clear()
```

Delege listesini temizle

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

İşleyiciler listesi boşsa true döndürür

**Returns:**
boolean değer

### remove {#remove-T-}
```
public final void remove( T delegate)
```

Temsilciyi listeden sil

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| temsilci |  | İşleyiciler nesnesi |
