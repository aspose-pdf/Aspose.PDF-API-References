---
title: "FontSourceCollection"
linktitle: "FontSourceCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une collection de sources de polices."
type: docs
weight: 40
url: /fr/java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Représente une collection de sources de polices.

## Champs

| Champ | Description |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | Événement CollectionChanged |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Initialise l'objet de collection |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Ajoute un nouvel objet source de police à la collection. |
| [clear](#clear--) | Efface la collection de sources de police. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Détermine si un élément se trouve dans la collection. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible. |
| [delete](#delete-com.aspose.pdf.FontSource-) | Supprime l'élément source de police. |
| [getItem](#getItem-int-) | Obtient l'élément police à l'index spécifié. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection. |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe). |
| [iterator](#iterator--) | Renvoie un énumérateur pour l'ensemble de la collection. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Supprime l'élément source de police. |
| [size](#size--) | Obtient le nombre d'éléments d'objet Font réellement contenus dans la collection. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

Événement CollectionChanged

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Initialise l'objet de collection

### add {#add-com.aspose.pdf.FontSource-}
Ajoute un nouvel objet source de police à la collection.

### clear {#clear--}
```
public void clear()
```

Efface la collection de sources de police.

### contains {#contains-com.aspose.pdf.FontSource-}
Détermine si un élément se trouve dans la collection.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Copie l'intégralité de la collection dans un tableau unidimensionnel compatible, en commençant à l'index spécifié du tableau cible.

### delete {#delete-com.aspose.pdf.FontSource-}
Supprime l'élément source de police.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Obtient l'élément police à l'index spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index dans la collection. |

**Returns:**
Objet source de police.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès à la collection.

**Returns:**
Élément d'objet

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient une valeur indiquant si l'accès à la collection est synchronisé (thread safe).

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Renvoie un énumérateur pour l'ensemble de la collection.

**Returns:**
Objet énumérateur.

### remove {#remove-com.aspose.pdf.FontSource-}
Supprime l'élément source de police.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments d'objet Font réellement contenus dans la collection.

**Returns:**
valeur int
