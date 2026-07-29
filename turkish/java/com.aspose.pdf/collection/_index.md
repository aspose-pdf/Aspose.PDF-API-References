---
title: "Koleksiyon"
linktitle: "Koleksiyon"
second_title: "Aspose.PDF for Java API Referansı"
description: "Collection(12.3.5 Collections) sınıfını temsil eder."
type: docs
weight: 610
url: /tr/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Collection(12.3.5 Collections) sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Collection](#Collection--) | Yeni Collection nesnesini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Varsayılan gömülü dosya adı. |
| [getSchema](#getSchema--) | Bir belge koleksiyonunun "Şeması"nı alır. |
| [getSortedCollection](#getSortedCollection--) | Belirtilen özelliğe göre sıralanmış dosyaların bir koleksiyonunu alır. |

### Collection {#Collection--}
```
public Collection()
```

Yeni Collection nesnesini başlatır.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Varsayılan gömülü dosya adı.

**Returns:**
Dize nesnesi

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Bir belge koleksiyonunun "Şeması"nı alır.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Belirtilen özelliğe göre sıralanmış dosyaların bir koleksiyonunu alır.

**Returns:**
Sıralanmış dosyaların listesi.
