---
title: "Id"
linktitle: "Id"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Dosya tanımlayıcı yapısını temsil eder. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /tr/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Dosya tanımlayıcı yapısını temsil eder. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getModified](#getModified--) | Belgenin içeriğine göre, son güncellendiği zamanda tanımlayıcıyı değiştirme. |
| [getOriginal](#getOriginal--) | Belgenin orijinal olarak oluşturulduğu zamandaki içeriğine dayalı kalıcı tanımlayıcı. |

### getModified {#getModified--}
```
public String getModified()
```

Belgenin içeriğine göre, son güncellendiği zamanda tanımlayıcıyı değiştirme.

**Returns:**
String değeri

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Belgenin orijinal olarak oluşturulduğu zamandaki içeriğine dayalı kalıcı tanımlayıcı.

**Returns:**
String değeri
