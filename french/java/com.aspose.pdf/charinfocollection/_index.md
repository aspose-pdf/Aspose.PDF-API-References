---
title: "CharInfoCollection"
linktitle: "CharInfoCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente la collection d'objets CharInfo. </p> <hr> <pre> L'exemple montre comment parcourir tous les caractères et récupérer le caractère //open document Document."
type: docs
weight: 570
url: /fr/java/com.aspose.pdf/charinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.CharInfoCollection

**All Implemented Interfaces:**
Itérable < CharInfo >

```
public final class CharInfoCollection extends Object implements Iterable < CharInfo >
```

<p> Représente la collection d'objets CharInfo. </p> <hr> <pre> L'exemple montre comment parcourir tous les caractères et récupérer le caractère //ouvrir le document Document pdfDocument = new Document(inFile); //créer l'objet TextFragmentAbsorber pour collecter tous les objets texte de la page TextFragmentAbsorber textFragmentAbsorber = new TextFragmentAbsorber(); //accepter l'absorbeur pour toutes les pages pdfDocument.getPages().get_Item(1).accept(textFragmentAbsorber); //obtenir les fragments de texte extraits TextFragmentCollection textFragmentCollection = textFragmentAbsorber.getTextFragments(); //boucler sur les fragments for (TextFragment textFragment : ({@code Iterable<TextFragment>})textFragmentCollection) { //boucler sur les segments for (TextSegment textSegment : ({@code Iterable<TextSegment>}) textFragment.getSegments()) { //boucler sur les caractères {@code for (int i = 1; i <= textSegment.getText().length(); i++)} { CharInfo charInfo = textSegment.getCharacters().get_Item(i); //afficher les informations de position et de rectangle du caractère System.out.println("XIndent : " + charInfo.getPosition().getXIndent()); System.out.println("YIndent : " + charInfo.getPosition().getYIndent()); System.out.println("Width : " + charInfo.getRectangle().getWidth()); System.out.println("Height : " + charInfo.getRectangle().getHeight()); } } } </pre> <hr> <p> Fournit l'accès aux informations de positionnement des caractères du segment de texte. </p>

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.CharInfo-) | Pas encore pris en charge. La collection est en lecture seule, lève une exception. |
| [clear](#clear--) | Pas encore pris en charge. La collection est en lecture seule. Lève toujours NotImplementedException. |
| [contains](#contains-com.aspose.pdf.CharInfo-) | Détermine si la collection contient une valeur spécifique. |
| [copyTo](#copyTo-com.aspose.pdf.CharInfo:A-int-) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [get_Item](#get_Item-int-) | Obtient l'élément CharInfo à l'index spécifié 1..n. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [iterator](#iterator--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [remove](#remove-com.aspose.pdf.CharInfo-) | Pas encore pris en charge. La collection est en lecture seule, lève une exception. |
| [size](#size--) | Obtient le nombre d'éléments d'objet {@code CharInfo} réellement contenus dans la collection. |

### add {#add-com.aspose.pdf.CharInfo-}
Pas encore pris en charge. La collection est en lecture seule, lève une exception.

### clear {#clear--}
```
public void clear()
```

Pas encore pris en charge. La collection est en lecture seule. Lève toujours NotImplementedException.

### contains {#contains-com.aspose.pdf.CharInfo-}
Détermine si la collection contient une valeur spécifique.

### copyTo {#copyTo-com.aspose.pdf.CharInfo:A-int-}
Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

### get_Item {#get_Item-int-}
```
public CharInfo get_Item(int index)
```

Obtient l'élément CharInfo à l'index spécifié 1..n.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
Objet CharInfo.

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
public com.aspose.ms.System.Collections.IEnumerator< CharInfo > iterator()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### remove {#remove-com.aspose.pdf.CharInfo-}
Pas encore pris en charge. La collection est en lecture seule, lève une exception.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments d'objet {@code CharInfo} réellement contenus dans la collection.

**Returns:**
valeur int
