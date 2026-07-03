---
title: Collection
second_title: Aspose.PDF for Java API Reference
description: Represents class for Collection(12.3.5 Collections).
type: docs
weight: 610
url: /java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Represents class for Collection(12.3.5 Collections).

## Constructors

| Constructor | Description |
| --- | --- |
| [Collection](#Collection--) | Initializes new Collection object. |

## Methods

| Method | Description |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Default embedded file name. |
| [getSchema](#getSchema--) | Gets a "Schema" of a document collection. |
| [getSortedCollection](#getSortedCollection--) | Gets a collection of files sorted according to the specification. |

### Collection {#Collection--}
```
public Collection()
```

Initializes new Collection object.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Default embedded file name.

**Returns:**
String object

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Gets a "Schema" of a document collection.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Gets a collection of files sorted according to the specification.

**Returns:**
The list of sorted files.
