---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan subtabel enkoding. Setiap subtabel enkoding memiliki kombinasi unik dari parameter (PlatformID, PlatformSpecificID). Enumerasi {@code CMapEncodingTableType} dan properti."
type: docs
weight: 3700
url: /id/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Menentukan subtabel enkoding. Setiap subtabel enkoding memiliki kombinasi unik parameter (PlatformID, PlatformSpecificID). Enumerasi {@code CMapEncodingTableType} dan properti {@code CMapEncodingTable} diimplementasikan untuk mempermudah penetapan subtabel enkoding yang diperlukan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [QueueItem](#QueueItem--) | Konstruktor, menentukan subtabel mac(1,0) secara default. |
| [QueueItem](#QueueItem-int-int-) | Konstruktor |
| [QueueItem](#QueueItem-short-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Menentukan subtabel enkoding melalui enumerasi {@code CMapEncodingTableType}. |
| [getPlatformId](#getPlatformId--) | Pengidentifikasi platform untuk subtabel enkoding. |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Pengidentifikasi enkoding spesifik platform untuk subtabel enkoding. |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Menentukan subtabel enkoding melalui enumerasi {@code CMapEncodingTableType}. |
| [setPlatformId](#setPlatformId-int-) | Pengidentifikasi platform untuk subtabel enkoding. |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Pengidentifikasi enkoding spesifik platform untuk subtabel enkoding. |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Konstruktor, menentukan subtabel mac(1,0) secara default.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Konstruktor

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| platformID |  | Pengidentifikasi platform untuk subtabel enkoding. |
| platformSpecificID |  | Pengidentifikasi enkoding spesifik platform untuk subtabel enkoding. |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Konstruktor

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cmapTable |  | subtabel enkoding |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Menentukan subtabel enkoding melalui enumerasi {@code CMapEncodingTableType}.

**Returns:**
subtabel enkoding

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Pengidentifikasi platform untuk subtabel enkoding.

**Returns:**
nilai int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Pengidentifikasi enkoding spesifik platform untuk subtabel enkoding.

**Returns:**
nilai int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Menentukan subtabel enkoding melalui enumerasi {@code CMapEncodingTableType}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | subtabel enkoding |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Pengidentifikasi platform untuk subtabel enkoding.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Pengidentifikasi enkoding spesifik platform untuk subtabel enkoding.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
