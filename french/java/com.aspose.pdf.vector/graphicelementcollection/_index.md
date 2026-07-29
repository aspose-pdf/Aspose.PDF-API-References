---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la collection {@link GraphicElement}."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Représente la collection {@link GraphicElement}.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Initialise la nouvelle collection. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Ajoute un nouveau {@link GraphicElement} à la collection. Tous les éléments de la collection doivent avoir le même {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Efface la collection. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Détermine si un élément se trouve dans la collection. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [get_Item](#get_Item-int-) | Obtient l'élément {@link GraphicElement} à l'index spécifié. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. Retourne toujours false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [iterator](#iterator--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Supprime l'élément {@link GraphicElement}. |
| [size](#size--) | Obtient le nombre d'objets {@link GraphicElement} réellement contenus dans la collection. |
| [toList](#toList--) | Renvoie la collection interne pour une énumération sans restriction. |
| [toString](#toString--) | Obtient une représentation sous forme de chaîne de cette collection. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Initialise la nouvelle collection.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Ajoute un nouveau {@link GraphicElement} à la collection. Tous les éléments de la collection doivent avoir le même {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Efface la collection.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Détermine si un élément se trouve dans la collection.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Obtient l'élément {@link GraphicElement} à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule. Retourne toujours false.

**Returns:**
valeur booléenne

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Supprime l'élément {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

Obtient le nombre d'objets {@link GraphicElement} réellement contenus dans la collection.

**Returns:**
valeur int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Renvoie la collection interne pour une énumération sans restriction.

**Returns:**
Liste interne

### toString {#toString--}
```
public String toString()
```

Obtient une représentation sous forme de chaîne de cette collection.

**Returns:**
La chaîne.
