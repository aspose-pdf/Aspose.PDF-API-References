---
title: PdfASymbolicFontEncodingStrategy.QueueItem
linktitle: PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for Java API Reference
description: Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificID). Enumeration {@code CMapEncodingTableType} and property.
type: docs
weight: 3700
url: /java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Specifies encoding subtable. Each encoding subtable has unique combination of parameters (PlatformID, PlatformSpecificID). Enumeration {@code CMapEncodingTableType} and property {@code CMapEncodingTable} were implemented to make easier set of encoding subtable needed.

## Constructors

| Constructor | Description |
| --- | --- |
| [QueueItem](#QueueItem--) | Constructor, specifies mac subtable(1,0) by default |
| [QueueItem](#QueueItem-int-int-) | Constructor |
| [QueueItem](#QueueItem-short-) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Specifies encoding subtable via {@code CMapEncodingTableType}enumeration |
| [getPlatformId](#getPlatformId--) | Platform identifier for encoding subtable |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Platform-specific encoding identifier for encoding subtable |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Specifies encoding subtable via {@code CMapEncodingTableType}enumeration |
| [setPlatformId](#setPlatformId-int-) | Platform identifier for encoding subtable |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Platform-specific encoding identifier for encoding subtable |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Constructor, specifies mac subtable(1,0) by default

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| platformID |  | Platform identifier for encoding subtable |
| platformSpecificID |  | Platform-specific encoding identifier for encoding subtable |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmapTable |  | encoding subtable |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Specifies encoding subtable via {@code CMapEncodingTableType}enumeration

**Returns:**
encoding subtable

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Platform identifier for encoding subtable

**Returns:**
int value

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Platform-specific encoding identifier for encoding subtable

**Returns:**
int value

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Specifies encoding subtable via {@code CMapEncodingTableType}enumeration

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | encoding subtable |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Platform identifier for encoding subtable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Platform-specific encoding identifier for encoding subtable

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
