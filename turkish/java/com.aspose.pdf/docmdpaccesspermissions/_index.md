---
title: "DocMDPAccessPermissions"
linktitle: "DocMDPAccessPermissions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu belge için verilen erişim izinleri. Geçerli değerler şunlardır: 1 - Belgeye hiçbir değişiklik yapılmasına izin verilmez; belgeye yapılan herhangi bir değişiklik imzayı geçersiz kılar. 2 -."
type: docs
weight: 1010
url: /tr/java/com.aspose.pdf/docmdpaccesspermissions/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocMDPAccessPermissions > com.aspose.pdf.DocMDPAccessPermissions, java.lang.Enum < DocMDPAccessPermissions >, com.aspose.pdf.DocMDPAccessPermissions

**All Implemented Interfaces:**
Serializable, Comparable < DocMDPAccessPermissions >

```
public enum DocMDPAccessPermissions extends Enum < DocMDPAccessPermissions >
```

Bu belgeye verilen erişim izinleri. Geçerli değerler: 1 - Belgeye hiçbir değişiklik yapılmasına izin verilmez; belgeye yapılan herhangi bir değişiklik imzayı geçersiz kılar. 2 - İzin verilen değişiklikler form doldurma, sayfa şablonlarını örnekleme ve imzalama; diğer değişiklikler imzayı geçersiz kılar. 3 - İzin verilen değişiklikler 2 ile aynı olup, ek olarak açıklama oluşturma, silme ve değiştirme; diğer değişiklikler imzayı geçersiz kılar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AnnotationModification](#AnnotationModification) | 3 - İzin verilen değişiklikler 2 için olanlarla aynıdır ve ayrıca ek açıklama oluşturma, silme ve değiştirme; diğer değişiklikler imzayı geçersiz kılar. |
| [FillingInForms](#FillingInForms) | 2 - İzin verilen değişiklikler form doldurma, sayfa şablonlarını örnekleme ve imzalama; diğer değişiklikler imzayı geçersiz kılar. |
| [NoChanges](#NoChanges) | 1 - Belgeye hiçbir değişiklik yapılmasına izin verilmez; belgeye yapılan herhangi bir değişiklik imzayı geçersiz kılar. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### AnnotationModification {#AnnotationModification}
```
public static final DocMDPAccessPermissions AnnotationModification
```

3 - İzin verilen değişiklikler 2 için olanlarla aynıdır ve ayrıca ek açıklama oluşturma, silme ve değiştirme; diğer değişiklikler imzayı geçersiz kılar.

### FillingInForms {#FillingInForms}
```
public static final DocMDPAccessPermissions FillingInForms
```

2 - İzin verilen değişiklikler form doldurma, sayfa şablonlarını örnekleme ve imzalama; diğer değişiklikler imzayı geçersiz kılar.

### NoChanges {#NoChanges}
```
public static final DocMDPAccessPermissions NoChanges
```

1 - Belgeye hiçbir değişiklik yapılmasına izin verilmez; belgeye yapılan herhangi bir değişiklik imzayı geçersiz kılar.

### getByValue {#getByValue-int-}
```
public static DocMDPAccessPermissions getByValue(int value)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static DocMDPAccessPermissions [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
