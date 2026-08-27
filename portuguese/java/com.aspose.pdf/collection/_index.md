---
title: "Coleção"
linktitle: "Coleção"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe para Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /pt/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Representa a classe para Collection(12.3.5 Collections).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [Collection](#Collection--) | Inicializa um novo objeto Collection. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Nome padrão do arquivo incorporado. |
| [getSchema](#getSchema--) | Obtém um "Schema" de uma coleção de documentos. |
| [getSortedCollection](#getSortedCollection--) | Obtém uma coleção de arquivos ordenados de acordo com a especificação. |

### Collection {#Collection--}
```
public Collection()
```

Inicializa um novo objeto Collection.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Nome padrão do arquivo incorporado.

**Returns:**
Objeto String

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Obtém um "Schema" de uma coleção de documentos.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Obtém uma coleção de arquivos ordenados de acordo com a especificação.

**Returns:**
A lista de arquivos ordenados.
