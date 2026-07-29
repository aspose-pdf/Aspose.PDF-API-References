---
title: "OptionCollection"
linktitle: "OptionCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant la collection d'options du champ de choix."
type: docs
weight: 3250
url: /fr/java/com.aspose.pdf/optioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OptionCollection

**All Implemented Interfaces:**
Iterable < Option >

```
public final class OptionCollection extends Object implements Iterable < Option >
```

Classe représentant la collection d'options du champ de choix.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Option-) | Ajoute un élément à la collection, lance une exception . Pas encore implémenté. |
| [clear](#clear--) | Supprime tous les éléments de la collection. |
| [contains](#contains-com.aspose.pdf.Option-) | Vérifie si l'élément existe dans la collection, lance une exception . Pas encore implémenté. |
| [deleteOption](#deleteOption-java.lang.String-) | Supprime l'option par son nom. |
| [get_Item](#get_Item-int-) | Obtient l'option par indice. |
| [get_Item](#get_Item-java.lang.String-) | Obtient l'option par son nom. |
| [get](#get-int-) | Obtient l'option par indice. |
| [get](#get-java.lang.String-) | Obtient l'option de la collection par le nom de l'option. |
| [getSyncRoot](#getSyncRoot--) | Objet de synchronisation de la collection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Renvoie vrai si l'objet est synchronisé. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Renvoie l'énumérateur des options dans la collection. |
| [iterator](#iterator--) | Renvoie l'énumérateur des options dans la collection. |
| [remove](#remove-com.aspose.pdf.Option-) | Supprime l'élément de la collection, lance une exception . Pas encore implémenté. |
| [size](#size--) | Obtient le nombre d'options. |

### add {#add-com.aspose.pdf.Option-}
Ajoute un élément à la collection, lance une exception . Pas encore implémenté.

### clear {#clear--}
```
public void clear()
```

Supprime tous les éléments de la collection.

### contains {#contains-com.aspose.pdf.Option-}
Vérifie si l'élément existe dans la collection, lance une exception . Pas encore implémenté.

### deleteOption {#deleteOption-java.lang.String-}
Supprime l'option par son nom.

### get_Item {#get_Item-int-}
```
public Option get_Item(int index)
```

Obtient l'option par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'option. |

**Returns:**
Option à l'indice spécifié.

### get_Item {#get_Item-java.lang.String-}
Obtient l'option par son nom.

### get {#get-int-}
```
public Option get(int index)
```

Obtient l'option par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'option. L'indice doit être dans la plage [1..n] où n est le nombre d'options. |

**Returns:**
Option récupérée.

### get {#get-java.lang.String-}
Obtient l'option de la collection par le nom de l'option.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objet de synchronisation de la collection.

**Returns:**
Élément d'objet

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

Renvoie vrai si l'objet est synchronisé.

**Returns:**
valeur booléenne

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Renvoie l'énumérateur des options dans la collection.

**Returns:**
Énumérateur des options.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Option > iterator()
```

Renvoie l'énumérateur des options dans la collection.

**Returns:**
Énumérateur des options.

### remove {#remove-com.aspose.pdf.Option-}
Supprime l'élément de la collection, lance une exception . Pas encore implémenté.

### size {#size--}
```
public int size()
```

Obtient le nombre d'options.

**Returns:**
valeur int
