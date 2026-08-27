---
title: "TextSegmentCollection"
linktitle: "TextSegmentCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une collection de segments de texte"
type: docs
weight: 5310
url: /fr/java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegmentCollection

**All Implemented Interfaces:**
Iterable < TextSegment >

```
public final class TextSegmentCollection extends Object implements Iterable < TextSegment >
```

Représente une collection de segments de texte

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.TextSegment-) | Ajoute l'élément de segment de texte à l'index spécifié. |
| [clear](#clear--) | Efface tous les éléments de la collection. |
| [contains](#contains-com.aspose.pdf.TextSegment-) | Détermine si la collection contient une valeur spécifique. |
| [copyTo](#copyTo-com.aspose.pdf.TextSegment:A-int-) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [delete](#delete-int-) | Supprime l'élément de segment de texte à l'index spécifié. |
| [get_Item](#get_Item-int-) | Obtient l'élément de segment de texte à l'index spécifié. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe). |
| [iterator](#iterator--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [remove](#remove-com.aspose.pdf.TextSegment-) | Supprime l'élément spécifié de la collection. |
| [size](#size--) | Obtient le nombre d'éléments d'objet {@code TextSegment} réellement contenus dans la collection. |

### add {#add-com.aspose.pdf.TextSegment-}
Ajoute l'élément de segment de texte à l'index spécifié.

### clear {#clear--}
```
public void clear()
```

Efface tous les éléments de la collection.

### contains {#contains-com.aspose.pdf.TextSegment-}
Détermine si la collection contient une valeur spécifique.

### copyTo {#copyTo-com.aspose.pdf.TextSegment:A-int-}
Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

### delete {#delete-int-}
```
public void delete(int index)
```

Supprime l'élément de segment de texte à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

### get_Item {#get_Item-int-}
```
public TextSegment get_Item(int index)
```

Obtient l'élément de segment de texte à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
Objet TextSegment.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection.

**Returns:**
Élément d'objet

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe).

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public Iterator < TextSegment > iterator()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### remove {#remove-com.aspose.pdf.TextSegment-}
Supprime l'élément spécifié de la collection.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments d'objet {@code TextSegment} réellement contenus dans la collection.

**Returns:**
valeur int
