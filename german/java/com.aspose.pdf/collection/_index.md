---
title: "Sammlung"
linktitle: "Sammlung"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Klasse für Collection(12.3.5 Collections) dar."
type: docs
weight: 610
url: /de/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Stellt die Klasse für Collection(12.3.5 Collections) dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Collection](#Collection--) | Initialisiert ein neues Collection-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Standardname für eingebettete Datei. |
| [getSchema](#getSchema--) | Liefert ein "Schema" einer Dokumentensammlung. |
| [getSortedCollection](#getSortedCollection--) | Liefert eine Sammlung von Dateien, sortiert nach der Spezifikation. |

### Collection {#Collection--}
```
public Collection()
```

Initialisiert ein neues Collection-Objekt.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Standardname für eingebettete Datei.

**Returns:**
String-Objekt

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Liefert ein "Schema" einer Dokumentensammlung.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Liefert eine Sammlung von Dateien, sortiert nach der Spezifikation.

**Returns:**
Die Liste der sortierten Dateien.
