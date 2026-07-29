---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificID). Enumeración {@code CMapEncodingTableType} y propiedad."
type: docs
weight: 3700
url: /es/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificID). La enumeración {@code CMapEncodingTableType} y la propiedad {@code CMapEncodingTable} se implementaron para facilitar el conjunto de subtablas de codificación necesario.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [QueueItem](#QueueItem--) | Constructor, especifica la subtabla mac(1,0) por defecto. |
| [QueueItem](#QueueItem-int-int-) | Constructor |
| [QueueItem](#QueueItem-short-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Especifica la subtabla de codificación mediante la enumeración {@code CMapEncodingTableType}. |
| [getPlatformId](#getPlatformId--) | Identificador de plataforma para la subtabla de codificación. |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Identificador de codificación específico de la plataforma para la subtabla de codificación. |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Especifica la subtabla de codificación mediante la enumeración {@code CMapEncodingTableType}. |
| [setPlatformId](#setPlatformId-int-) | Identificador de plataforma para la subtabla de codificación. |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Identificador de codificación específico de la plataforma para la subtabla de codificación. |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Constructor, especifica la subtabla mac(1,0) por defecto.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Constructor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| platformID |  | Identificador de plataforma para la subtabla de codificación. |
| platformSpecificID |  | Identificador de codificación específico de la plataforma para la subtabla de codificación. |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Constructor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmapTable |  | subtabla de codificación |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Especifica la subtabla de codificación mediante la enumeración {@code CMapEncodingTableType}.

**Returns:**
subtabla de codificación

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Identificador de plataforma para la subtabla de codificación.

**Returns:**
valor int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Identificador de codificación específico de la plataforma para la subtabla de codificación.

**Returns:**
valor int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Especifica la subtabla de codificación mediante la enumeración {@code CMapEncodingTableType}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | subtabla de codificación |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Identificador de plataforma para la subtabla de codificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Identificador de codificación específico de la plataforma para la subtabla de codificación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
