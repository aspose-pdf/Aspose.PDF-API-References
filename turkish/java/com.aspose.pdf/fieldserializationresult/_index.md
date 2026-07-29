---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir form alanı serileştirme işleminin sonucunu temsil eder."
type: docs
weight: 1390
url: /tr/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

Bir form alanı serileştirme işleminin sonucunu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | Yeni bir {@link FieldSerializationResult} sınıfı örneği başlatır. |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | Yeni bir {@link FieldSerializationResult} sınıfı örneği başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | Serileştirme süreciyle ilişkili hata mesajlarını alır. Değer: Bir dizi hata mesajı. |
| [getFieldFullName](#getFieldFullName--) | Alanının tam adını alır. Değer: Alanının tam adı. |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | Form alanı serileştirme durumunu alır. Değer: Form alanının serileştirme durumu. |
| [getWarningMessages](#getWarningMessages--) | Serileştirme süreciyle ilişkili uyarı mesajlarını alır. Değer: Bir dizi uyarı mesajı. |
| [updateStatus](#updateStatus-int-java.lang.String-) | Serileştirme durumunu günceller ve uygun kümeye bir mesaj ekler. |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

Yeni bir {@link FieldSerializationResult} sınıfı örneği başlatır.

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
Yeni bir {@link FieldSerializationResult} sınıfı örneği başlatır.

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

Serileştirme süreciyle ilişkili hata mesajlarını alır. Değer: Bir dizi hata mesajı.

**Returns:**
String örneğinin HashSet'i

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

Alanının tam adını alır. Değer: Alanının tam adı.

**Returns:**
String değeri

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

Form alanı serileştirme durumunu alır. Değer: Form alanının serileştirme durumu.

**Returns:**
FieldSerializationStatus öğesi

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

Serileştirme süreciyle ilişkili uyarı mesajlarını alır. Değer: Bir dizi uyarı mesajı.

**Returns:**
String örneğinin HashSet'i

### updateStatus {#updateStatus-int-java.lang.String-}
Serileştirme durumunu günceller ve uygun kümeye bir mesaj ekler.
