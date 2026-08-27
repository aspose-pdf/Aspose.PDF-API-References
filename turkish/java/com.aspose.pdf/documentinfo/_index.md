---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinin meta bilgilerini temsil eder."
type: docs
weight: 1160
url: /tr/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

PDF belgesinin meta bilgilerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | DocumentInfo örneğini başlat. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Belirtilen anahtar ve değerle bir öğe koleksiyona ekler. |
| [clear](#clear--) | Belge bilgisini temizler. |
| [clearCustomData](#clearCustomData--) | Yalnızca özel verileri temizler, diğer tüm önceden tanımlı değerleri (Başlık, Yazar, vb.) bırakır. |
| [get_Item](#get_Item-java.lang.String-) | Belirtilen anahtarla ilişkili değeri alır. |
| [getAuthor](#getAuthor--) | Belge yazarını alır. |
| [getCreationDate](#getCreationDate--) | Belge oluşturma tarihini alır. |
| [getCreationTimeZone](#getCreationTimeZone--) | Oluşturma tarihinin milisaniye cinsinden saat dilimi. |
| [getCreator](#getCreator--) | Belge oluşturucusunu alır. |
| [getKeywords](#getKeywords--) | Belgenin anahtar kelimelerini alır. |
| [getModDate](#getModDate--) | Belge değiştirme tarihini alır. |
| [getModTimeZone](#getModTimeZone--) | Değiştirme tarihinin saat dilimi. |
| [getProducer](#getProducer--) | Belge üreticisini alır. |
| [getSubject](#getSubject--) | Belgenin konusunu alır. |
| [getTitle](#getTitle--) | Belge başlığını alır. |
| [getTrapped](#getTrapped--) | Tuzak bayrağını alır. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Anahtarın önceden tanımlı (Başlık, Yazar, vb.) olup olmadığını, özel olmadığını belirler. |
| [remove](#remove-java.lang.String-) | Belirtilen anahtara sahip öğeyi koleksiyondan kaldırır. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Belirtilen anahtarla ilişkili değeri ayarlar. |
| [setAuthor](#setAuthor-java.lang.String-) | Belge yazarını ayarlar. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Belge oluşturma tarihini ayarlar. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Oluşturma tarihinin milisaniye cinsinden saat dilimi. |
| [setCreator](#setCreator-java.lang.String-) | Belge oluşturucusunu ayarlar. |
| [setKeywords](#setKeywords-java.lang.String-) | Belgenin anahtar kelimelerini ayarlar. |
| [setModDate](#setModDate-java.util.Date-) | Belge değiştirme tarihini ayarlar. |
| [setModTimeZone](#setModTimeZone-double-) | Değiştirme tarihinin saat dilimi. |
| [setProducer](#setProducer-java.lang.String-) | Belge üreticisini ayarlar. |
| [setSubject](#setSubject-java.lang.String-) | Belgenin konusunu ayarlar. |
| [setTitle](#setTitle-java.lang.String-) | Belge başlığını ayarlar. |
| [setTrapped](#setTrapped-java.lang.String-) | Tutsak bayrağını ayarlar. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
DocumentInfo örneğini başlat.

### addItem {#addItem-java.lang.String-java.lang.String-}
Belirtilen anahtar ve değerle bir öğe koleksiyona ekler.

### clear {#clear--}
```
public void clear()
```

Belge bilgisini temizler.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Yalnızca özel verileri temizler, diğer tüm önceden tanımlı değerleri (Başlık, Yazar, vb.) bırakır.

### get_Item {#get_Item-java.lang.String-}
Belirtilen anahtarla ilişkili değeri alır.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Belge yazarını alır.

**Returns:**
String değeri

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Belge oluşturma tarihini alır.

**Returns:**
Date nesnesi

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Oluşturma tarihinin milisaniye cinsinden saat dilimi.

**Returns:**
double değer

### getCreator {#getCreator--}
```
public String getCreator()
```

Belge oluşturucusunu alır.

**Returns:**
String değeri

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Belgenin anahtar kelimelerini alır.

**Returns:**
String değeri

### getModDate {#getModDate--}
```
public Date getModDate()
```

Belge değiştirme tarihini alır.

**Returns:**
Date nesnesi

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Değiştirme tarihinin saat dilimi.

**Returns:**
double değer

### getProducer {#getProducer--}
```
public String getProducer()
```

Belge üreticisini alır.

**Returns:**
String değeri

### getSubject {#getSubject--}
```
public String getSubject()
```

Belgenin konusunu alır.

**Returns:**
String değeri

### getTitle {#getTitle--}
```
public String getTitle()
```

Belge başlığını alır.

**Returns:**
String değeri

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Tuzak bayrağını alır.

**Returns:**
String değeri

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Anahtarın önceden tanımlı (Başlık, Yazar, vb.) olup olmadığını, özel olmadığını belirler.

### remove {#remove-java.lang.String-}
Belirtilen anahtara sahip öğeyi koleksiyondan kaldırır.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Belirtilen anahtarla ilişkili değeri ayarlar.

### setAuthor {#setAuthor-java.lang.String-}
Belge yazarını ayarlar.

### setCreationDate {#setCreationDate-java.util.Date-}
Belge oluşturma tarihini ayarlar.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Oluşturma tarihinin milisaniye cinsinden saat dilimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | milisaniye cinsinden |

### setCreator {#setCreator-java.lang.String-}
Belge oluşturucusunu ayarlar.

### setKeywords {#setKeywords-java.lang.String-}
Belgenin anahtar kelimelerini ayarlar.

### setModDate {#setModDate-java.util.Date-}
Belge değiştirme tarihini ayarlar.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Değiştirme tarihinin saat dilimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setProducer {#setProducer-java.lang.String-}
Belge üreticisini ayarlar.

### setSubject {#setSubject-java.lang.String-}
Belgenin konusunu ayarlar.

### setTitle {#setTitle-java.lang.String-}
Belge başlığını ayarlar.

### setTrapped {#setTrapped-java.lang.String-}
Tutsak bayrağını ayarlar.
