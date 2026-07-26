---
title: "Raccolta"
linktitle: "Raccolta"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe per Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /it/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Rappresenta la classe per Collection(12.3.5 Collections).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Collection](#Collection--) | Inizializza un nuovo oggetto Collection. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Nome predefinito del file incorporato. |
| [getSchema](#getSchema--) | Restituisce uno "Schema" di una raccolta di documenti. |
| [getSortedCollection](#getSortedCollection--) | Restituisce una raccolta di file ordinati secondo la specifica. |

### Collection {#Collection--}
```
public Collection()
```

Inizializza un nuovo oggetto Collection.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Nome predefinito del file incorporato.

**Returns:**
Oggetto stringa

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Restituisce uno "Schema" di una raccolta di documenti.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Restituisce una raccolta di file ordinati secondo la specifica.

**Returns:**
L'elenco dei file ordinati.
