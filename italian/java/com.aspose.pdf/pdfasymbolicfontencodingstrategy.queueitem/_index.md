---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Specifica la sottotabella di codifica. Ogni sottotabella di codifica ha una combinazione unica di parametri (PlatformID, PlatformSpecificID). Enumerazione {@code CMapEncodingTableType} e proprietà."
type: docs
weight: 3700
url: /it/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Specifica la sottotabella di codifica. Ogni sottotabella di codifica ha una combinazione unica di parametri (PlatformID, PlatformSpecificID). L'enumerazione {@code CMapEncodingTableType} e la proprietà {@code CMapEncodingTable} sono state implementate per semplificare la definizione della sottotabella di codifica necessaria.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [QueueItem](#QueueItem--) | Costruttore, specifica la sottotabella mac(1,0) per impostazione predefinita |
| [QueueItem](#QueueItem-int-int-) | Costruttore |
| [QueueItem](#QueueItem-short-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Specifica la sottotabella di codifica tramite l'enumerazione {@code CMapEncodingTableType} |
| [getPlatformId](#getPlatformId--) | Identificatore della piattaforma per la sottotabella di codifica |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Identificatore di codifica specifico della piattaforma per la sottotabella di codifica |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Specifica la sottotabella di codifica tramite l'enumerazione {@code CMapEncodingTableType} |
| [setPlatformId](#setPlatformId-int-) | Identificatore della piattaforma per la sottotabella di codifica |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Identificatore di codifica specifico della piattaforma per la sottotabella di codifica |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Costruttore, specifica la sottotabella mac(1,0) per impostazione predefinita

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Costruttore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| platformID |  | Identificatore della piattaforma per la sottotabella di codifica |
| platformSpecificID |  | Identificatore di codifica specifico della piattaforma per la sottotabella di codifica |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Costruttore

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cmapTable |  | sottotabella di codifica |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Specifica la sottotabella di codifica tramite l'enumerazione {@code CMapEncodingTableType}

**Returns:**
sottotabella di codifica

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Identificatore della piattaforma per la sottotabella di codifica

**Returns:**
valore int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Identificatore di codifica specifico della piattaforma per la sottotabella di codifica

**Returns:**
valore int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Specifica la sottotabella di codifica tramite l'enumerazione {@code CMapEncodingTableType}

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | sottotabella di codifica |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Identificatore della piattaforma per la sottotabella di codifica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Identificatore di codifica specifico della piattaforma per la sottotabella di codifica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
