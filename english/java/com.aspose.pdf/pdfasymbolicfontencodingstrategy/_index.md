---
title: PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for Java API Reference
description: This class describes rules which can be used to tune process of copy encoding data for cases when TrueType symbolic font has more than one encoding.
type: docs
weight: 277
url: /java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object
```
public class PdfASymbolicFontEncodingStrategy
```

This class describes rules which can be used to tune process of copy encoding data for cases when TrueType symbolic font has more than one encoding. Some PDF documents after conversion into PDF/A format could have error "More than one encoding in symbolic TrueType font's cmap". What is a reason of this error? All TrueType symbolic fonts have special table "cmap" in it's internal data. This table maps character codes to glyph indices. And this table could contain different encoding subtables which describe encodings used. See advanced info about cmap tables at https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Usually cmap table contains several encoding subtables, but PDF/A standard requires that only one encoding subtable (3,0) must be leaved for this font in PDF/A document. And key question here - what data must be taken from another subtables to copy into destination encoding table (3,0)? Majority of fonts have 'well-formed' cmap tables where every encoding subtable is fully consistent with another subtable. But some fonts have cmap tables with collisions - where for example one subtable has glyph index 100 for unicode 100, but another subtable has glyph index 200 for the same unicode 100. To solve this problems special strategy needed. By default following strategy used: mac subtable(1,0) is looked for. If this table is found, only this data used to fill destination table (3,0). If mac subtable is not found then all subtables except (3,0) are iterated and used to copy data into destination (3,0) subtable. Also mapping for every unicode(unicode, glyph index) is copied into destination table only if destination table has no this unicode at current moment. So, for example if first subtabe has glyph index 100 for unicode 100, and next subtable has glyph index 200 for the same unicode 100, only data from first subtable (unicode=100, glyph index = 100) will be copied. So each previous subtable takes precedence over the next. Properties of this class  PdfASymbolicFontEncodingStrategy  help tune default behaviour. If property  PreferredCmapEncodingTable  of type  QueueItem.CMapEncodingTableType  is set, then relevant subtable will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration  QueueItem.CMapEncodingTableType  has no sense in this case, cause it points on the same mac subtable (1,0) which will be used by default. Property  CmapEncodingTablesPriorityQueue  discards all priorities for any subtable. If this property is set, then only subtables from declared queue will be used in specified order. If subtables specified are not found then default iteration of all subtables and copy strategy described above will be used. Object  QueueItem  specifies encoding subtable used. This subtable can be set via combination of members(PlatformID, PlatformSpecificID) or via  QueueItem.CMapEncodingTableType  enumeration.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy()](#PdfASymbolicFontEncodingStrategy--) | Constructor. |
| [PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | Constructor |
| [PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)](#PdfASymbolicFontEncodingStrategy-short-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getPreferredCmapEncodingTable()](#getPreferredCmapEncodingTable--) | Specifies subtable which will be used in precedence to mac subtable(1,0). |
| [setPreferredCmapEncodingTable(short value)](#setPreferredCmapEncodingTable-short-) | Specifies subtable which will be used in precedence to mac subtable(1,0). |
| [getCmapEncodingTablesPriorityQueue()](#getCmapEncodingTablesPriorityQueue--) | Specifies queue of encoding subtables to process. |
| [setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--) | Specifies queue of encoding subtables to process. |
### PdfASymbolicFontEncodingStrategy() {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```


Constructor. Sets default subtable (mac 1,0)

### PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue) {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public PdfASymbolicFontEncodingStrategy(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> priorityQueue)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| priorityQueue | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | queue of encoding subtables to iterate |

### PdfASymbolicFontEncodingStrategy(short preferredEncodingTable) {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| preferredEncodingTable | short | encoding subtable which will be used in precedence to mac subtable(1,0) |

### getPreferredCmapEncodingTable() {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```


Specifies subtable which will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration  QueueItem.CMapEncodingTableType  has no sense in this case.

**Returns:**
short - CMapEncodingTableType element
### setPreferredCmapEncodingTable(short value) {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```


Specifies subtable which will be used in precedence to mac subtable(1,0). Value 'MacTable' from enumeration  QueueItem.CMapEncodingTableType  has no sense in this case.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short | preferredEncodingTable encoding subtable which will be used in precedence to mac subtable(1,0) |

### getCmapEncodingTablesPriorityQueue() {#getCmapEncodingTablesPriorityQueue--}
```
public System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> getCmapEncodingTablesPriorityQueue()
```


Specifies queue of encoding subtables to process.

**Returns:**
com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> - Queue of QueueItem
### setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value) {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem--}
```
public void setCmapEncodingTablesPriorityQueue(System.Collections.Generic.Queue<PdfASymbolicFontEncodingStrategy.QueueItem> value)
```


Specifies queue of encoding subtables to process.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Generic.Queue<com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem> | Queue of QueueItem |

