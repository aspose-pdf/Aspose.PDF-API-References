---
title: "PdfASymbolicFontEncodingStrategy.QueueItem"
linktitle: "PdfASymbolicFontEncodingStrategy.QueueItem"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica a sub‑tabela de codificação. Cada sub‑tabela de codificação tem uma combinação única de parâmetros (PlatformID, PlatformSpecificID). Enumeração {@code CMapEncodingTableType} e propriedade."
type: docs
weight: 3700
url: /pt/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy.QueueItem

```
public static class PdfASymbolicFontEncodingStrategy.QueueItem extends Object
```

Especifica a sub‑tabela de codificação. Cada sub‑tabela de codificação tem combinação única de parâmetros (PlatformID, PlatformSpecificID). A enumeração {@code CMapEncodingTableType} e a propriedade {@code CMapEncodingTable} foram implementadas para facilitar o conjunto de sub‑tabelas de codificação necessárias.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [QueueItem](#QueueItem--) | Construtor, especifica a sub‑tabela mac(1,0) por padrão. |
| [QueueItem](#QueueItem-int-int-) | Construtor |
| [QueueItem](#QueueItem-short-) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCMapEncodingTable](#getCMapEncodingTable--) | Especifica a sub‑tabela de codificação via enumeração {@code CMapEncodingTableType}. |
| [getPlatformId](#getPlatformId--) | Identificador da plataforma para a sub‑tabela de codificação. |
| [getPlatformSpecificId](#getPlatformSpecificId--) | Identificador de codificação específico da plataforma para a sub‑tabela de codificação. |
| [setCMapEncodingTable](#setCMapEncodingTable-short-) | Especifica a sub‑tabela de codificação via enumeração {@code CMapEncodingTableType}. |
| [setPlatformId](#setPlatformId-int-) | Identificador da plataforma para a sub‑tabela de codificação. |
| [setPlatformSpecificId](#setPlatformSpecificId-int-) | Identificador de codificação específico da plataforma para a sub‑tabela de codificação. |

### QueueItem {#QueueItem--}
```
public QueueItem()
```

Construtor, especifica a sub‑tabela mac(1,0) por padrão.

### QueueItem {#QueueItem-int-int-}
```
public QueueItem(int platformID, int platformSpecificID)
```

Construtor

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| platformID |  | Identificador da plataforma para a sub‑tabela de codificação. |
| platformSpecificID |  | Identificador de codificação específico da plataforma para a sub‑tabela de codificação. |

### QueueItem {#QueueItem-short-}
```
public QueueItem(short cmapTable)
```

Construtor

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cmapTable |  | sub‑tabela de codificação |

### getCMapEncodingTable {#getCMapEncodingTable--}
```
public short getCMapEncodingTable()
```

Especifica a sub‑tabela de codificação via enumeração {@code CMapEncodingTableType}.

**Returns:**
sub‑tabela de codificação

### getPlatformId {#getPlatformId--}
```
public int getPlatformId()
```

Identificador da plataforma para a sub‑tabela de codificação.

**Returns:**
valor int

### getPlatformSpecificId {#getPlatformSpecificId--}
```
public int getPlatformSpecificId()
```

Identificador de codificação específico da plataforma para a sub‑tabela de codificação.

**Returns:**
valor int

### setCMapEncodingTable {#setCMapEncodingTable-short-}
```
public void setCMapEncodingTable(short value)
```

Especifica a sub‑tabela de codificação via enumeração {@code CMapEncodingTableType}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | sub‑tabela de codificação |

### setPlatformId {#setPlatformId-int-}
```
public void setPlatformId(int value)
```

Identificador da plataforma para a sub‑tabela de codificação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPlatformSpecificId {#setPlatformSpecificId-int-}
```
public void setPlatformSpecificId(int value)
```

Identificador de codificação específico da plataforma para a sub‑tabela de codificação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |
