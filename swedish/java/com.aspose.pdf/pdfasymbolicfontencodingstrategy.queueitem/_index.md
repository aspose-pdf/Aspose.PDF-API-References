---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger kodningens deltabell. Varje kodningens deltabell har en unik kombination av parametrar (PlatformID, PlatformSpecificID). Enumeration {@code CMapEncodingTableType} och egenskap."
type: docs
weight: 3700
url: /sv/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Specificerar en kodningstabell. Varje kodningstabell har en unik kombination av parametrar (PlatformID, PlatformSpecificID). Uppräkning {@code CMapEncodingTableType} och egenskap {@code CMapEncodingTable} implementerades för att underlätta att ange den kodningstabell som behövs.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [QueueItem](#QueueItem--) | Konstruktor, anger mac-deltabell(1,0) som standard. |
| [QueueItem](#QueueItem-int-int-) | Konstruktör |
| [QueueItem](#QueueItem-short-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Anger kodningens deltabell via {@code CMapEncodingTableType}enumeration. |
| [getPlatformId](#getPlatformId--) | Plattformsidentifierare för kodningens deltabell. |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Plattformspecifik kodningsidentifierare för kodningens deltabell. |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Anger kodningens deltabell via {@code CMapEncodingTableType}enumeration. |
| [setPlatformId](#setPlatformId-int-) | Plattformsidentifierare för kodningens deltabell. |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Plattformspecifik kodningsidentifierare för kodningens deltabell. |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Konstruktor, anger mac-deltabell(1,0) som standard.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Konstruktör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| platformID |  | Plattformsidentifierare för kodningens deltabell. |
| platformSpecificID |  | Plattformspecifik kodningsidentifierare för kodningens deltabell. |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Konstruktör

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cmapTable |  | kodningens deltabell |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Anger kodningens deltabell via {@code CMapEncodingTableType}enumeration.

**Returns:**
kodningens deltabell

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Plattformsidentifierare för kodningens deltabell.

**Returns:**
int‑värde

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Plattformspecifik kodningsidentifierare för kodningens deltabell.

**Returns:**
int‑värde

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Anger kodningens deltabell via {@code CMapEncodingTableType}enumeration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | kodningens deltabell |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Plattformsidentifierare för kodningens deltabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Plattformspecifik kodningsidentifierare för kodningens deltabell.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |
