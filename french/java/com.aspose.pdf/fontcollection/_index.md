---
title: "FontCollection"
linktitle: "FontCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la collection de polices. </p> <hr> <pre> L'exemple montre comment rendre toutes les polices déclarées sur la page intégrées. // Open document Document doc = new."
type: docs
weight: 1670
url: /fr/java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Représente la collection de polices. </p> <hr> <pre> L'exemple montre comment rendre toutes les polices déclarées sur la page intégrées. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // assurez-vous que toutes les polices déclarées dans les ressources de la page sont intégrées // notez que si les polices sont déclarées dans les ressources du formulaire, elles ne sont pas accessibles depuis les ressources de la page for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Les collections de polices représentées par la classe {@code FontCollection} sont utilisées dans plusieurs scénarios. Par exemple, dans les ressources avec la propriété {@code Resources.Fonts}. </p>

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Ajoute une police à la collection. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Ajoute une nouvelle police aux ressources de polices et renvoie le nom attribué automatiquement à la ressource de police. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Ajoute une nouvelle police à la collection de polices. |
| [add](#add-java.lang.String-java.lang.String-) | Ajoute aux ressources de polices une nouvelle entrée de police avec le nom de police de base spécifié. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Ajoute une police à la collection. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Détermine si la collection contient une valeur spécifique. |
| [contains](#contains-java.lang.String-) | Vérifie si la police existe dans la collection de polices. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [delete](#delete-java.lang.String-) | Supprime la police avec le nom de ressource spécifié. |
| [get_Item](#get_Item-int-) | Obtient l'élément police à l'index spécifié. |
| [get_Item](#get_Item-java.lang.String-) | Obtient la police de la collection par son nom. Une exception est levée si la police n'est pas trouvée. |
| [getFontsDictionary](#getFontsDictionary--) | Obtenir l'objet IPdfDictionary |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [iterator](#iterator--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [remove](#remove-com.aspose.pdf.Font-) | Supprime l'élément spécifié de la collection. |
| [size](#size--) | Obtient le nombre d'éléments d'objet {@code Font} réellement contenus dans la collection. |

### add {#add-com.aspose.pdf.Font-}
Ajoute une police à la collection.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Ajoute une nouvelle police aux ressources de polices et renvoie le nom attribué automatiquement à la ressource de police.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Ajoute une nouvelle police à la collection de polices.

### add {#add-java.lang.String-java.lang.String-}
Ajoute aux ressources de polices une nouvelle entrée de police avec le nom de police de base spécifié.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Ajoute une police à la collection. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Détermine si la collection contient une valeur spécifique.

### contains {#contains-java.lang.String-}
Vérifie si la police existe dans la collection de polices.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

### delete {#delete-java.lang.String-}
Supprime la police avec le nom de ressource spécifié.

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Obtient l'élément police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
Objet police.

### get_Item {#get_Item-java.lang.String-}
Obtient la police de la collection par son nom. Une exception est levée si la police n'est pas trouvée.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Obtenir l'objet IPdfDictionary

**Returns:**
Objet IPdfDictionary

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection.

**Returns:**
Objet pour la synchronisation

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

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### remove {#remove-com.aspose.pdf.Font-}
Supprime l'élément spécifié de la collection.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments d'objet {@code Font} réellement contenus dans la collection.

**Returns:**
valeur int
