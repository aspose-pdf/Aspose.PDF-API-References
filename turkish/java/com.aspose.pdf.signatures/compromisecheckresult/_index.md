---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Aspose.PDF for Java API Referansı"
description: "Belge dijital imzalarının ihlal edilip edilmediğini kontrol eden bir sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Belge dijital imzalarının ihlal edilip edilmediğini kontrol eden bir sınıfı temsil eder.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Belirlenmiş olarak tehlikeli tespit edilen dijital imzaların bir koleksiyonunu alır. Bu özellik, belgede tespit edilen tüm tehlikeli imzaların listesini içerir. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Bir belgede dijital imzaların kapsama durumunu alır. Eğer {@code SignaturesCoverage#Undefined}'a eşitse, imzalardan biri tehlikeli demektir. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Belgede herhangi bir tehlikeli dijital imza olup olmadığını gösterir. En az bir imza tehlikeli ise true, aksi takdirde false döndürür. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Belirlenmiş olarak tehlikeli tespit edilen dijital imzaların bir koleksiyonunu alır. Bu özellik, belgede tespit edilen tüm tehlikeli imzaların listesini içerir.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Bir belgede dijital imzaların kapsama durumunu alır. Eğer {@code SignaturesCoverage#Undefined}'a eşitse, imzalardan biri tehlikeli demektir.

**Returns:**
SignaturesCoverage öğesi

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Belgede herhangi bir tehlikeli dijital imza olup olmadığını gösterir. En az bir imza tehlikeli ise true, aksi takdirde false döndürür.

**Returns:**
boolean değer
