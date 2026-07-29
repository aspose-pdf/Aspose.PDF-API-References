---
title: "Samling"
linktitle: "Samling"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar klass för Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /sv/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Representerar klass för Collection(12.3.5 Collections).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Collection](#Collection--) | Initierar ett nytt Collection-objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Standardnamn för inbäddad fil. |
| [getSchema](#getSchema--) | Hämtar ett "Schema" för en dokumentsamling. |
| [getSortedCollection](#getSortedCollection--) | Hämtar en samling filer sorterade enligt specifikationen. |

### Collection {#Collection--}
```
public Collection()
```

Initierar ett nytt Collection-objekt.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Standardnamn för inbäddad fil.

**Returns:**
String-objekt

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Hämtar ett "Schema" för en dokumentsamling.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Hämtar en samling filer sorterade enligt specifikationen.

**Returns:**
Listan över sorterade filer.
