---
title: "Colección"
linktitle: "Colección"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la clase para Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /es/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Representa la clase para Collection(12.3.5 Collections).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Collection](#Collection--) | Inicializa un nuevo objeto Collection. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Nombre predeterminado del archivo incrustado. |
| [getSchema](#getSchema--) | Obtiene un "Schema" de una colección de documentos. |
| [getSortedCollection](#getSortedCollection--) | Obtiene una colección de archivos ordenados según la especificación. |

### Collection {#Collection--}
```
public Collection()
```

Inicializa un nuevo objeto Collection.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Nombre predeterminado del archivo incrustado.

**Returns:**
Objeto String

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Obtiene un "Schema" de una colección de documentos.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Obtiene una colección de archivos ordenados según la especificación.

**Returns:**
La lista de archivos ordenados.
