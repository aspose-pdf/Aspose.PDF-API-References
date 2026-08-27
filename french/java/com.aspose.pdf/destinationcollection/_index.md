---
title: "DestinationCollection"
linktitle: "DestinationCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La classe représente la collection de toutes les destinations (un arbre de noms mappant les chaînes de noms aux destinations (voir 12.3.2.3, \"Named Destinations\") et (voir 7.7.4, \"Name Dictionary\")) in."
type: docs
weight: 960
url: /fr/java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Classe représentant la collection de toutes les destinations (un arbre de noms associant des chaînes de noms aux destinations (voir 12.3.2.3, \"Named Destinations\") et (voir 7.7.4, \"Name Dictionary\")) dans le document PDF.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ajoute l'élément spécifié. |
| [clear](#clear--) | La collection est en lecture seule. Lance toujours une exception NotSupportedException. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Détermine si cette instance contient l'objet. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les éléments de la collection dans un tableau, en commençant à un indice de tableau particulier. |
| [get_Item](#get_Item-int-) | Obtient l'objet de destination par indice. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Renvoie la destination explicite par le nom. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Renvoie le numéro de page de la destination par le nom. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Renvoie l'indice de la destination dans la collection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [iterator](#iterator--) | Renvoie l'énumérateur. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime l'élément spécifié. |
| [size](#size--) | Obtient le nombre d'éléments contenus dans la collection. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ajoute l'élément spécifié.

### clear {#clear--}
```
public void clear()
```

La collection est en lecture seule. Lance toujours une exception NotSupportedException.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Détermine si cette instance contient l'objet.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les éléments de la collection dans un tableau, en commençant à un indice de tableau particulier.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Obtient l'objet de destination par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | L'indice de la destination à obtenir. |

**Returns:**
Destination.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Renvoie la destination explicite par le nom.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Renvoie le numéro de page de la destination par le nom.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Renvoie l'indice de la destination dans la collection.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Renvoie l'énumérateur.

**Returns:**
L'énumérateur.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime l'élément spécifié.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments contenus dans la collection.

**Returns:**
valeur int
