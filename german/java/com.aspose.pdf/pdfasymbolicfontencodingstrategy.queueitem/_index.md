---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt die Encoding-Untertabelle an. Jede Encoding-Untertabelle hat eine eindeutige Kombination von Parametern (PlatformID, PlatformSpecificID). Aufzählung {@code CMapEncodingTableType} und Eigenschaft."
type: docs
weight: 3700
url: /de/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Gibt die Kodierungstabelle an. Jede Kodierungstabelle hat eine eindeutige Kombination von Parametern (PlatformID, PlatformSpecificID). Die Aufzählung {@code CMapEncodingTableType} und die Eigenschaft {@code CMapEncodingTable} wurden implementiert, um die benötigte Auswahl von Kodierungstabellen zu erleichtern.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [QueueItem](#QueueItem--) | Konstruktor, gibt standardmäßig die mac-Untertabelle (1,0) an. |
| [QueueItem](#QueueItem-int-int-) | Konstruktor |
| [QueueItem](#QueueItem-short-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Gibt die Codierungstabelle über {@code CMapEncodingTableType}enumeration an |
| [getPlatformId](#getPlatformId--) | Plattformkennung für die Codierungstabelle |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Plattformspezifische Codierungskennung für die Codierungstabelle |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Gibt die Codierungstabelle über {@code CMapEncodingTableType}enumeration an |
| [setPlatformId](#setPlatformId-int-) | Plattformkennung für die Codierungstabelle |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Plattformspezifische Codierungskennung für die Codierungstabelle |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Konstruktor, gibt standardmäßig die mac-Untertabelle (1,0) an.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Konstruktor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| platformID |  | Plattformkennung für die Codierungstabelle |
| platformSpecificID |  | Plattformspezifische Codierungskennung für die Codierungstabelle |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Konstruktor

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cmapTable |  | Codierungstabelle |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Gibt die Codierungstabelle über {@code CMapEncodingTableType}enumeration an

**Returns:**
Codierungstabelle

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Plattformkennung für die Codierungstabelle

**Returns:**
int-Wert

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Plattformspezifische Codierungskennung für die Codierungstabelle

**Returns:**
int-Wert

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Gibt die Codierungstabelle über {@code CMapEncodingTableType}enumeration an

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Codierungstabelle |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Plattformkennung für die Codierungstabelle

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Plattformspezifische Codierungskennung für die Codierungstabelle

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |
