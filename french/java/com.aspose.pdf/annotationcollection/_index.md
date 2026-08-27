---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant une collection d'annotations."
type: docs
weight: 80
url: /fr/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

Classe représentant une collection d'annotations.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | Constructeur de AnnotationCollection. Crée une collection d'annotations pour les annotations sur la page donnée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un visiteur pour traiter l'annotation. |
| [add](#add-com.aspose.pdf.Annotation-) | Ajoute l'annotation à la collection. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | Ajoute l'annotation à la collection. Si la page est pivotée, le rectangle de l'annotation sera recalculé en conséquence. |
| [clear](#clear--) | Supprime toutes les annotations de la collection. |
| [contains](#contains-com.aspose.pdf.Annotation-) | Vérifie si l'annotation spécifiée appartient à la collection. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | Copie le tableau d'annotations dans la collection. |
| [delete](#delete--) | Supprime toutes les annotations de la collection. |
| [delete](#delete-com.aspose.pdf.Annotation-) | Supprime toutes les annotations de la collection. |
| [delete](#delete-int-) | Supprime l'annotation de la collection par indice. |
| [findByName](#findByName-java.lang.String-) | Renvoie l'annotation par son nom. |
| [get_Item](#get_Item-int-) | L'indice de l'élément à obtenir. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet qui peut être utilisé pour synchroniser l'accès à com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à com.aspose.pdf.AnnotationCollection est synchronisé (thread‑safe). |
| [iterator](#iterator--) | Renvoie l'énumérateur de la collection. |
| [remove](#remove-com.aspose.pdf.Annotation-) | Supprime l'annotation spécifiée de la collection. |
| [size](#size--) | Obtient le nombre d'annotations dans la collection. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
Constructeur de AnnotationCollection. Crée une collection d'annotations pour les annotations sur la page donnée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un visiteur pour traiter l'annotation.

### add {#add-com.aspose.pdf.Annotation-}
Ajoute l'annotation à la collection.

### add {#add-com.aspose.pdf.Annotation-boolean-}
Ajoute l'annotation à la collection. Si la page est pivotée, le rectangle de l'annotation sera recalculé en conséquence.

### clear {#clear--}
```
public void clear()
```

Supprime toutes les annotations de la collection.

### contains {#contains-com.aspose.pdf.Annotation-}
Vérifie si l'annotation spécifiée appartient à la collection.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
Copie le tableau d'annotations dans la collection.

### delete {#delete--}
```
public void delete()
```

Supprime toutes les annotations de la collection.

### delete {#delete-com.aspose.pdf.Annotation-}
Supprime toutes les annotations de la collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Supprime l'annotation de la collection par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'annotation qui doit être supprimée. |

### findByName {#findByName-java.lang.String-}
Renvoie l'annotation par son nom.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

L'indice de l'élément à obtenir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | La valeur d'indice commence à un. |

**Returns:**
Objet d'annotation

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet qui peut être utilisé pour synchroniser l'accès à com.aspose.pdf.AnnotationCollection.

**Returns:**
Objet pour la synchronisation

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient une valeur indiquant si l'accès à com.aspose.pdf.AnnotationCollection est synchronisé (thread‑safe).

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

Renvoie l'énumérateur de la collection.

**Returns:**
Objet énumérateur

### remove {#remove-com.aspose.pdf.Annotation-}
Supprime l'annotation spécifiée de la collection.

### size {#size--}
```
public int size()
```

Obtient le nombre d'annotations dans la collection.

**Returns:**
valeur int
