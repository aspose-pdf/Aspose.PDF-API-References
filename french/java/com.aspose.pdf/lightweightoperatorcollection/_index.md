---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Collection d'opérateurs légère. Destinée à être utilisée dans les scénarios où le flux de contenu sous-jacent n'est pas attaché, et où seule la collection d'opérateurs est requise en résultat."
type: docs
weight: 2700
url: /fr/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Collection d'opérateurs légère. Destinée à être utilisée dans les scénarios où le flux de contenu sous-jacent n'est pas attaché, et où seule la collection d'opérateurs est requise en résultat.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Initialiser l'objet |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Initialiser l'objet |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Initialiser l'objet |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Ajouter un opérateur |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Ajouter LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu. |
| [clear](#clear--) | Vide la collection. |
| [contains](#contains-com.aspose.pdf.Operator-) | Vérifie si l'élément est dans la collection. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | suppression interne Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Obtient l'opérateur par son index. </p> <hr> <pre> L'exemple montre comment obtenir l'opérateur du contenu de la page par index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Pour usage interne getUnrestricted operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Insérer l'opérateur |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indique si la collection est limitée à l'extraction rapide de texte |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [iterator](#iterator--) | Retourner l'itérateur |
| [remove](#remove-com.aspose.pdf.Operator-) | Supprime l'opérateur de la collection. |
| [resumeUpdate](#resumeUpdate--) | Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Définit l'opérateur par son index. <hr> <pre> L'exemple montre comment obtenir l'opérateur du contenu de la page par index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Nombre d'opérateurs |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| [toList](#toList--) | Renvoie la liste des opérateurs. |
| [updateData](#updateData--) | interne |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Initialiser l'objet

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Initialiser l'objet

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Initialiser l'objet

### add {#add-com.aspose.pdf.Operator-}
Ajouter un opérateur

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Ajouter LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu.

### clear {#clear--}
```
public void clear()
```

Vide la collection.

### contains {#contains-com.aspose.pdf.Operator-}
Vérifie si l'élément est dans la collection.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

suppression interne Unrestrictedelement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtient l'opérateur par son index. </p> <hr> <pre> L'exemple montre comment obtenir l'opérateur du contenu de la page par index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'opérateur. La numérotation commence à 1. |

**Returns:**
Opérateur à l'indice demandé

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Pour usage interne getUnrestricted operator

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

**Returns:**
Objet opérateur

### insert {#insert-int-com.aspose.pdf.Operator-}
Insérer l'opérateur

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indique si la collection est limitée à l'extraction rapide de texte

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si la collection est en lecture seule.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Retourner l'itérateur

**Returns:**
{@code IGenericEnumerator<Operator>} objet

### remove {#remove-com.aspose.pdf.Operator-}
Supprime l'opérateur de la collection.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Définit l'opérateur par son index. <hr> <pre> L'exemple montre comment obtenir l'opérateur du contenu de la page par index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Nombre d'opérateurs

**Returns:**
valeur int

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Renvoie la liste des opérateurs.

**Returns:**
liste des opérateurs.

### updateData {#updateData--}
```
public void updateData()
```

interne
