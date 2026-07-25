---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe de base pour la collection d'opérateurs."
type: docs
weight: 270
url: /fr/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Représente la classe de base pour la collection d'opérateurs.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Ajoute un nouvel opérateur à la collection. |
| [cancelUpdate](#cancelUpdate--) | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu. |
| [clear](#clear--) | Vide la collection. |
| [contains](#contains-com.aspose.pdf.Operator-) | Vérifie si l'élément est dans la collection. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | interne |
| [get_Item](#get_Item-int-) | Obtient l'opérateur par son indice. |
| [getUnrestricted](#getUnrestricted-int-) | À usage interne uniquement |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Insère l'opérateur dans la collection. |
| [isEmpty](#isEmpty--) | Renvoie VRAI si la collection est vide. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indique si la collection est limitée à l'extraction rapide de texte |
| [isReadOnly](#isReadOnly--) | Renvoie vrai si la collection est en lecture seule. |
| [iterator](#iterator--) | Renvoie un énumérateur pour la collection |
| [remove](#remove-com.aspose.pdf.Operator-) | Supprime l'opérateur de la collection. |
| [resumeUpdate](#resumeUpdate--) | Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Définit l'opérateur par son indice. |
| [size](#size--) | Obtient le nombre d'opérateurs dans la collection. |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| [toList](#toList--) | Renvoie la liste d'opetator. |
| [updateData](#updateData--) | interne |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Ajoute un nouvel opérateur à la collection.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu.

### clear {#clear--}
```
public abstract void clear()
```

Vide la collection.

### contains {#contains-com.aspose.pdf.Operator-}
Vérifie si l'élément est dans la collection.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

interne

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Obtient l'opérateur par son indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'opérateur. La numérotation commence à 1. |

**Returns:**
Opérateur à l'indice demandé

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

À usage interne uniquement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

**Returns:**
Objet opérateur

### insert {#insert-int-com.aspose.pdf.Operator-}
Insère l'opérateur dans la collection.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Renvoie VRAI si la collection est vide.

**Returns:**
valeur booléenne

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indique si la collection est limitée à l'extraction rapide de texte

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Renvoie vrai si la collection est en lecture seule.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Renvoie un énumérateur pour la collection

**Returns:**
Énumérateur de collection

### remove {#remove-com.aspose.pdf.Operator-}
Supprime l'opérateur de la collection.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Définit l'opérateur par son indice.

### size {#size--}
```
public abstract int size()
```

Obtient le nombre d'opérateurs dans la collection.

**Returns:**
valeur entière

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Renvoie la liste d'opetator.

**Returns:**
liste d'opetator.

### updateData {#updateData--}
```
public abstract void updateData()
```

interne
