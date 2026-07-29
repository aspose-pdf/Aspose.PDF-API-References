---
title: "PageCollection"
linktitle: "PageCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Collection de pages de document PDF."
type: docs
weight: 3340
url: /fr/java/com.aspose.pdf/pagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageCollection

**All Implemented Interfaces:**
Iterable < Page >

```
public final class PageCollection extends Object implements Iterable < Page >
```

Collection de pages de document PDF.

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte l'objet visiteur {@code AnnotationSelector} qui fournit des fonctionnalités pour travailler avec les annotations. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepte l'objet visiteur {@code ImagePlacementAbsorber} qui fournit des fonctionnalités pour travailler avec des objets de placement d'image. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepte l'objet visiteur {@code TextAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepte l'objet visiteur {@code TextFragmentAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [add_Rename_Namesake](#add_Rename_Namesake-com.aspose.pdf.Page-) | Ajoute une page à la collection. |
| [add](#add--) | Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [add](#add-java.lang.Iterable-) | Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [add](#add-java.util.List-) | Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [add](#add-com.aspose.pdf.Page-) | Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [add](#add-com.aspose.pdf.Page:A-) | Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [beginUpdate](#beginUpdate--) | Met à jour lorsque les changements de groupe commencent. |
| [clear](#clear--) | Efface la collection de pages. |
| [contains](#contains-com.aspose.pdf.Page-) | Détermine si cette instance contient l'objet. |
| [copyTo](#copyTo-com.aspose.pdf.Page:A-int-) | Copie les pages dans le document. |
| [delete](#delete--) | Supprime toutes les pages de la collection. |
| [delete](#delete-int-) | Supprime la page spécifiée. |
| [delete](#delete-java.lang.Integer:A-) | Supprime toutes les pages de la collection. |
| [endUpdate](#endUpdate--) | Met à jour lorsque les changements de groupe sont terminés. |
| [findByPdfObject](#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-) |  |
| [flatten](#flatten--) | Supprime tous les champs situés sur les pages et place leurs valeurs à la place. |
| [freeMemory](#freeMemory--) | Efface les données en cache |
| [get_Item](#get_Item-int-) | Obtient la page par indice. |
| [getSyncRoot](#getSyncRoot--) | Obtient l'objet de synchronisation de la collection. |
| [getUnrestricted](#getUnrestricted-int-) | Renvoie la page par son indice. {@code Page} |
| [indexOf](#indexOf-com.aspose.pdf.Page-) | <p> Renvoie l'indice de la page spécifiée. </p> |
| [insert](#insert-int-) | Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée. |
| [insert](#insert-int-java.lang.Iterable-) | Insère les pages de la collection dans le document. |
| [insert](#insert-int-java.util.List-) | Insère les pages de la collection dans le document. |
| [insert](#insert-int-com.aspose.pdf.Page-) | Insère une page dans la collection de pages à l'emplacement spécifié. |
| [insert](#insert-int-com.aspose.pdf.Page:A-) | Insère les pages du tableau dans le document. |
| [isEmpty](#isEmpty--) | Renvoie VRAI si la collection est vide. |
| [isReadOnly](#isReadOnly--) | Obtient la valeur indiquant que la collection est en lecture seule. Retourne toujours false. |
| [isSynchronized](#isSynchronized--) | Renvoie true si l'objet est synchronisé. |
| [iterator](#iterator--) | Renvoie l'énumérateur des pages. |
| [remove](#remove-com.aspose.pdf.Page-) | Supprime l'élément spécifié, lève une exception. |
| [size](#size--) | Obtient le nombre de pages dans le document. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte l'objet visiteur {@code AnnotationSelector} qui fournit des fonctionnalités pour travailler avec les annotations.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepte l'objet visiteur {@code ImagePlacementAbsorber} qui fournit des fonctionnalités pour travailler avec des objets de placement d'image.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepte l'objet visiteur {@code TextAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepte l'objet visiteur {@code TextFragmentAbsorber} qui fournit des fonctionnalités pour travailler avec des objets texte.

### add_Rename_Namesake {#add_Rename_Namesake-com.aspose.pdf.Page-}
Ajoute une page à la collection.

### add {#add--}
```
public Page add()
```

Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Returns:**
Page ajoutée.

### add {#add-java.lang.Iterable-}
Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Returns:**
Page ajoutée.

### add {#add-java.util.List-}
Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Returns:**
Page ajoutée.

### add {#add-com.aspose.pdf.Page-}
Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Returns:**
Page ajoutée.

### add {#add-com.aspose.pdf.Page:A-}
Ajoute une page vide. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Returns:**
Page ajoutée.

### beginUpdate {#beginUpdate--}
```
public final void beginUpdate()
```

Met à jour lorsque les changements de groupe commencent.

### clear {#clear--}
```
public void clear()
```

Efface la collection de pages.

### contains {#contains-com.aspose.pdf.Page-}
Détermine si cette instance contient l'objet.

### copyTo {#copyTo-com.aspose.pdf.Page:A-int-}
Copie les pages dans le document.

### delete {#delete--}
```
public void delete()
```

Supprime toutes les pages de la collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Supprime la page spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Numéro de la page qui sera supprimée. Les numéros de pages commencent à 1. |

### delete {#delete-java.lang.Integer:A-}
Supprime toutes les pages de la collection.

### endUpdate {#endUpdate--}
```
public final void endUpdate()
```

Met à jour lorsque les changements de groupe sont terminés.

### findByPdfObject {#findByPdfObject-com.aspose.pdf.engine.data.IPdfObject-}


### flatten {#flatten--}
```
public void flatten()
```

Supprime tous les champs situés sur les pages et place leurs valeurs à la place.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Efface les données en cache

### get_Item {#get_Item-int-}
```
public Page get_Item(int index)
```

Obtient la page par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de la page. |

**Returns:**
Page récupérée.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient l'objet de synchronisation de la collection.

**Returns:**
Objet pour la synchronisation

### getUnrestricted {#getUnrestricted-int-}
```
public Page getUnrestricted(int index)
```

Renvoie la page par son indice. {@code Page}

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de la page demandée. Les pages sont numérotées à partir de 1. |

**Returns:**
Page demandée

### indexOf {#indexOf-com.aspose.pdf.Page-}
<p> Renvoie l'indice de la page spécifiée. </p>

### insert {#insert-int-}
```
public Page insert(int pageNumber)
```

Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Position de la nouvelle page. |

**Returns:**
Page insérée.

### insert {#insert-int-java.lang.Iterable-}
Insère les pages de la collection dans le document.

### insert {#insert-int-java.util.List-}
Insère les pages de la collection dans le document.

### insert {#insert-int-com.aspose.pdf.Page-}
Insère une page dans la collection de pages à l'emplacement spécifié.

### insert {#insert-int-com.aspose.pdf.Page:A-}
Insère les pages du tableau dans le document.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Renvoie VRAI si la collection est vide.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient la valeur indiquant que la collection est en lecture seule. Retourne toujours false.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Renvoie true si l'objet est synchronisé.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public Iterator < Page > iterator()
```

Renvoie l'énumérateur des pages.

**Returns:**
Énumérateur de pages

### remove {#remove-com.aspose.pdf.Page-}
Supprime l'élément spécifié, lève une exception.

### size {#size--}
```
public int size()
```

Obtient le nombre de pages dans le document.

**Returns:**
valeur int
