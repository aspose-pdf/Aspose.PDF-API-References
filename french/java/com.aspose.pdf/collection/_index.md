---
title: "Collection"
linktitle: "Collection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe pour Collection(12.3.5 Collections)."
type: docs
weight: 610
url: /fr/java/com.aspose.pdf/collection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection com.aspose.pdf.Collection, com.aspose.pdf.EmbeddedFileCollection, com.aspose.pdf.Collection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class Collection extends EmbeddedFileCollection
```

Représente la classe pour Collection(12.3.5 Collections).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Collection](#Collection--) | Initialise un nouvel objet Collection. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultEntry](#getDefaultEntry--) | Nom de fichier intégré par défaut. |
| [getSchema](#getSchema--) | Obtient un "Schéma" d'une collection de documents. |
| [getSortedCollection](#getSortedCollection--) | Obtient une collection de fichiers triés selon la spécification. |

### Collection {#Collection--}
```
public Collection()
```

Initialise un nouvel objet Collection.

### getDefaultEntry {#getDefaultEntry--}
```
public String getDefaultEntry()
```

Nom de fichier intégré par défaut.

**Returns:**
Objet String

### getSchema {#getSchema--}
```
public final CollectionSchema getSchema()
```

Obtient un "Schéma" d'une collection de documents.

**Returns:**
CollectionSchema

### getSortedCollection {#getSortedCollection--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< FileSpecification > getSortedCollection()
```

Obtient une collection de fichiers triés selon la spécification.

**Returns:**
La liste des fichiers triés.
