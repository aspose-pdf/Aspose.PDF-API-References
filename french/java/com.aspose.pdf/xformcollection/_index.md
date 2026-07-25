---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant la collection de XFormCollection."
type: docs
weight: 5600
url: /fr/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Classe représentant la collection de XFormCollection.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Ajoute un nouveau XForm à la collection. |
| [clear](#clear--) | Efface tous les éléments de la collection. |
| [contains](#contains-com.aspose.pdf.XForm-) | Détermine si la collection contient une valeur spécifique. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Copie XFormCollection dans la collection. |
| [delete](#delete--) | Supprime tous les XForms de la collection. |
| [delete](#delete-int-) | Supprime le XForm de la collection |
| [delete](#delete-java.lang.String-) | Supprime tous les XForms de la collection. |
| [freeMemory](#freeMemory--) | Efface les données en cache, libère la mémoire, etc. |
| [get_Item](#get_Item-int-) | Renvoie le XForm par indice. |
| [get_Item](#get_Item-java.lang.String-) | Renvoie le XForm par son nom. Une exception est levée si le XForm avec le nom spécifié n'est pas trouvé. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Renvoie le nom du formulaire dans cette collection de formulaires |
| [getSyncRoot](#getSyncRoot--) | Objet de synchronisation. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Retourne true si l'objet est synchronisé. |
| [iterator](#iterator--) | Renvoie l'énumérateur de la collection. |
| [remove](#remove-com.aspose.pdf.XForm-) | Supprime l'élément spécifié de la collection. |
| [size](#size--) | Obtient le nombre de XForms dans la collection. |

### add {#add-com.aspose.pdf.XForm-}
Ajoute un nouveau XForm à la collection.

### clear {#clear--}
```
public void clear()
```

Efface tous les éléments de la collection.

### contains {#contains-com.aspose.pdf.XForm-}
Détermine si la collection contient une valeur spécifique.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Copie XFormCollection dans la collection.

### delete {#delete--}
```
public void delete()
```

Supprime tous les XForms de la collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Supprime le XForm de la collection

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice du XForm qui doit être supprimé |

### delete {#delete-java.lang.String-}
Supprime tous les XForms de la collection.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Efface les données en cache, libère la mémoire, etc.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Renvoie le XForm par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de XFormCollection. La numérotation des XForms commence à 1 |

**Returns:**
XForm récupéré

### get_Item {#get_Item-java.lang.String-}
Renvoie le XForm par son nom. Une exception est levée si le XForm avec le nom spécifié n'est pas trouvé.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Renvoie le nom du formulaire dans cette collection de formulaires

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objet de synchronisation.

**Returns:**
Objet

### hasForm {#hasForm-java.lang.String-}


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

Retourne true si l'objet est synchronisé.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Renvoie l'énumérateur de la collection.

**Returns:**
Énumérateur pour la collection

### remove {#remove-com.aspose.pdf.XForm-}
Supprime l'élément spécifié de la collection.

### size {#size--}
```
public int size()
```

Obtient le nombre de XForms dans la collection.

**Returns:**
valeur int
