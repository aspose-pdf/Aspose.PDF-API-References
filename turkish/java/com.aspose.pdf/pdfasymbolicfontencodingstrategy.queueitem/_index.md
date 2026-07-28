---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF for Java API Referansı"
description: "Kodlama alt tablosunu belirtir. Her kodlama alt tablosu, (PlatformID, PlatformSpecificID) parametrelerinin benzersiz bir kombinasyonuna sahiptir. {@code CMapEncodingTableType} enumu ve özelliği."
type: docs
weight: 3700
url: /tr/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Kodlama alt tablosunu belirtir. Her kodlama alt tablosu, (PlatformID, PlatformSpecificID) parametrelerinin benzersiz bir kombinasyonuna sahiptir. {@code CMapEncodingTableType} enum'ı ve {@code CMapEncodingTable} özelliği, gerekli kodlama alt tablosunu ayarlamayı kolaylaştırmak için uygulanmıştır.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [QueueItem](#QueueItem--) | Yapıcı, varsayılan olarak mac alt tablosunu (1,0) belirtir. |
| [QueueItem](#QueueItem-int-int-) | Yapıcı |
| [QueueItem](#QueueItem-short-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Kodlama alt tablosunu {@code CMapEncodingTableType}enumu aracılığıyla belirtir. |
| [getPlatformId](#getPlatformId--) | Kodlama alt tablosu için platform tanımlayıcısı |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Kodlama alt tablosunu {@code CMapEncodingTableType}enumu aracılığıyla belirtir. |
| [setPlatformId](#setPlatformId-int-) | Kodlama alt tablosu için platform tanımlayıcısı |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Yapıcı, varsayılan olarak mac alt tablosunu (1,0) belirtir.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| platformID |  | Kodlama alt tablosu için platform tanımlayıcısı |
| platformSpecificID |  | Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Yapıcı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cmapTable |  | kodlama alt tablosu |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Kodlama alt tablosunu {@code CMapEncodingTableType}enumu aracılığıyla belirtir.

**Returns:**
kodlama alt tablosu

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Kodlama alt tablosu için platform tanımlayıcısı

**Returns:**
int değer

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı

**Returns:**
int değer

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Kodlama alt tablosunu {@code CMapEncodingTableType}enumu aracılığıyla belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | kodlama alt tablosu |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Kodlama alt tablosu için platform tanımlayıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Kodlama alt tablosu için platforma özgü kodlama tanımlayıcısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
