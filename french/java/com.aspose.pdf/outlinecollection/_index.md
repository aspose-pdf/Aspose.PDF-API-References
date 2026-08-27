---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la hiérarchie du plan du document."
type: docs
weight: 3260
url: /fr/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Représente la hiérarchie du plan du document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Ajoute un élément d'outline à la collection. |
| [clear](#clear--) | Efface tous les éléments de la collection. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Pas encore pris en charge. Vérifie si la collection contient l'élément donné. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copie les éléments d'outline dans un System.Array, en commençant à un indice particulier du System.Array. |
| [delete](#delete--) | Supprime tous les éléments d'outline du plan du document. |
| [delete](#delete-java.lang.String-) | Supprime tous les éléments d'outline du plan du document. |
| [get_Item](#get_Item-int-) | Obtient l'élément d'outline de la collection par indice. |
| [getFirst](#getFirst--) | Obtient un élément d'outline représentant le premier élément de niveau supérieur dans l'outline. |
| [getLast](#getLast--) | Obtient un élément d'outline représentant le dernier élément de niveau supérieur dans l'outline. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection. |
| [getVisibleCount](#getVisibleCount--) | Count est la somme du nombre d'éléments d'outline descendants visibles à tous les niveaux. Remarque : veuillez ne pas confondre avec Count qui correspond au nombre d'éléments dans la collection. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe). |
| [iterator](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [next](#next--) |  |
| [remove](#remove-int-) | Supprime l'élément par indice. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Pas encore pris en charge. Lance toujours une exception |
| [size](#size--) | Obtient le nombre total d'éléments d'outline (signets) à tous les niveaux du plan du document. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Ajoute un élément d'outline à la collection.

### clear {#clear--}
```
public void clear()
```

Efface tous les éléments de la collection.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Pas encore pris en charge. Vérifie si la collection contient l'élément donné.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copie les éléments d'outline dans un System.Array, en commençant à un indice particulier du System.Array.

### delete {#delete--}
```
public void delete()
```

Supprime tous les éléments d'outline du plan du document.

### delete {#delete-java.lang.String-}
Supprime tous les éléments d'outline du plan du document.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Obtient l'élément d'outline de la collection par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'élément demandé. |

**Returns:**
Objet OutlineItemCollection

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Obtient un élément d'outline représentant le premier élément de niveau supérieur dans l'outline.

**Returns:**
Objet OutlineItemCollection

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Obtient un élément d'outline représentant le dernier élément de niveau supérieur dans l'outline.

**Returns:**
Objet OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection.

**Returns:**
Objet pour la synchronisation

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count est la somme du nombre d'éléments d'outline descendants visibles à tous les niveaux. Remarque : veuillez ne pas confondre avec Count qui correspond au nombre d'éléments dans la collection.

**Returns:**
valeur int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



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

Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe).

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Returns:**
Un objet System.Collections.IEnumerator pouvant être utilisé pour parcourir la collection.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Supprime l'élément par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'élément à supprimer. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Pas encore pris en charge. Lance toujours une exception

### size {#size--}
```
public int size()
```

Obtient le nombre total d'éléments d'outline (signets) à tous les niveaux du plan du document.

**Returns:**
valeur int
