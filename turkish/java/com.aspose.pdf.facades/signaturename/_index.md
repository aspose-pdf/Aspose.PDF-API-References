---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Aspose.PDF for Java API Referansı"
description: "İmza adı için bir sınıfı temsil eder. Daha kesin bir imza adı temsil eder. Dize adları yerine kullanılır. Aynı dize adlarına sahip imzaları sunmanıza olanak tanır."
type: docs
weight: 690
url: /tr/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

İmza adı için bir sınıfı temsil eder. Daha kesin bir imza adı temsil eder. Dize adları yerine kullanılır. Aynı dize adlarına sahip imzaları sunmanıza olanak tanır.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [FullName](#FullName) | İmzanın tam adını alır, imza alanı için benzersiz ve kesin bir tanımlayıcı sağlar. |
| [Name](#Name) | Bir imzanın adını alır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Bu örnek ile belirtilen nesnenin eşit olup olmadığını belirler. |
| [getSignatureDictionary](#getSignatureDictionary--) | İmza sözlüğünü alır. |
| [hashCode](#hashCode--) | Bu örnek için FullName özelliğine dayalı bir karma kod döndürür. |
| [hasSignature](#hasSignature--) | İmzanın mevcut olup olmadığını gösterir. |
| [toString](#toString--) | {@link SignatureName} örneğinin bir dize temsili döndürür, öncelikle adını kullanarak. |

### FullName {#FullName}
```
public final String FullName
```

İmzanın tam adını alır, imza alanı için benzersiz ve kesin bir tanımlayıcı sağlar.

### Name {#Name}
```
public final String Name
```

Bir imzanın adını alır.

### equals {#equals-java.lang.Object-}
Bu örnek ile belirtilen nesnenin eşit olup olmadığını belirler.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

İmza sözlüğünü alır.

**Returns:**
İmza sözlüğü veya bulunamazsa null.

### hashCode {#hashCode--}
```
public int hashCode()
```

Bu örnek için FullName özelliğine dayalı bir karma kod döndürür.

**Returns:**
FullName özelliğinin karma kodunu temsil eden bir tamsayı.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

İmzanın mevcut olup olmadığını gösterir.

**Returns:**
boolean değer

### toString {#toString--}
```
public String toString()
```

{@link SignatureName} örneğinin bir dize temsili döndürür, öncelikle adını kullanarak.

**Returns:**
İmzanın adını temsil eden bir dize.
