---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد جدول الترميز الفرعي. كل جدول ترميز فرعي لديه تركيبة فريدة من المعلمات (PlatformID, PlatformSpecificID). تعداد {@code CMapEncodingTableType} والخاصية."
type: docs
weight: 3700
url: /ar/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

يحدد جدول الترميز الفرعي. كل جدول ترميز فرعي له تركيبة فريدة من المعلمات (PlatformID، PlatformSpecificID). تم تنفيذ التعداد {@code CMapEncodingTableType} والخاصية {@code CMapEncodingTable} لتسهيل تحديد جدول الترميز الفرعي المطلوب.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [QueueItem](#QueueItem--) | منشئ، يحدد جدول mac الفرعي (1,0) بشكل افتراضي. |
| [QueueItem](#QueueItem-int-int-) | منشئ |
| [QueueItem](#QueueItem-short-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | يحدد جدول الترميز الفرعي عبر تعداد {@code CMapEncodingTableType}enumeration |
| [getPlatformId](#getPlatformId--) | معرّف المنصة لجدول الترميز الفرعي |
| [getPlatformSpecificId](#getPlatformSpecificId--) | معرّف الترميز الخاص بالمنصة لجدول الترميز الفرعي |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | يحدد جدول الترميز الفرعي عبر تعداد {@code CMapEncodingTableType}enumeration |
| [setPlatformId](#setPlatformId-int-) | معرّف المنصة لجدول الترميز الفرعي |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | معرّف الترميز الخاص بالمنصة لجدول الترميز الفرعي |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

منشئ، يحدد جدول mac الفرعي (1,0) بشكل افتراضي.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

منشئ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| platformID |  | معرّف المنصة لجدول الترميز الفرعي |
| platformSpecificID |  | معرّف الترميز الخاص بالمنصة لجدول الترميز الفرعي |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

منشئ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cmapTable |  | جدول الترميز الفرعي |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

يحدد جدول الترميز الفرعي عبر تعداد {@code CMapEncodingTableType}enumeration

**Returns:**
جدول الترميز الفرعي

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

معرّف المنصة لجدول الترميز الفرعي

**Returns:**
قيمة int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

معرّف الترميز الخاص بالمنصة لجدول الترميز الفرعي

**Returns:**
قيمة int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

يحدد جدول الترميز الفرعي عبر تعداد {@code CMapEncodingTableType}enumeration

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | جدول الترميز الفرعي |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

معرّف المنصة لجدول الترميز الفرعي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

معرّف الترميز الخاص بالمنصة لجدول الترميز الفرعي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
