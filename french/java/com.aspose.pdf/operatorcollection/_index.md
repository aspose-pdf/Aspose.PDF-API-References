---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant une collection d'opérateurs"
type: docs
weight: 3190
url: /fr/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Classe représentant une collection d'opérateurs

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | À usage interne uniquement ! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | À usage interne uniquement ! |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte un objet visiteur IOperatorSelector pour traiter les opérateurs. |
| [add](#add-java.lang.Iterable-) | Ajoute à la collection tous les opérateurs d’une autre collection. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Ajoute un nouvel opérateur à la collection. </p> <hr> <p> L’exemple montre comment ajouter des opérateurs à la fin de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Ajoute des opérateurs à la fin des opérateurs de contenu. </p> <hr> <p> L’exemple montre comment ajouter un opérateur à la fin du contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu. |
| [clear](#clear--) | <p> Supprime tous les opérateurs de la liste. </p> <hr> <p> L’exemple montre comment effacer le contenu de la page. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Effectue les tâches définies par l’application liées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [contains](#contains-com.aspose.pdf.Operator-) | Renvoie true si la collection contient l’opérateur donné. |
| [delete](#delete-int-) | <p> Supprime un opérateur de la collection. </p> <hr> <p> L’exemple montre comment supprimer un opérateur par son indice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Supprime des opérateurs de la collection. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Supprime des opérateurs de la collection. </p> <hr> <p> L’exemple montre comment retirer un opérateur du contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | version interne non restreinte de Delete(index) |
| [dispose](#dispose--) | Effectue les tâches définies par l’application liées à la libération, la remise ou la réinitialisation des ressources non gérées. |
| [get_Item](#get_Item-int-) | <p> Obtient l’opérateur par son indice. </p> <hr> Exemple montre comment obtenir l’opérateur du contenu de la page par indice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Version interne non restreinte de l’indexeur |
| [insert](#insert-int-java.lang.Iterable-) | Insère des opérateurs à la position donnée. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Insère un opérateur dans la collection. </p> <hr> <p> L’exemple montre comment insérer un opérateur dans le contenu de la page. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Insère des opérateurs à la position donnée. </p> <hr> <p> L’exemple montre comment insérer un opérateur dans le contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Obtient le statut entre crochets de la séquence d’opérateurs, c’est‑à‑dire si ces opérateurs sont à l’intérieur des blocs q - Q |
| [isCommandsParsed](#isCommandsParsed--) | Obtient les commandes analysées |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indique si la collection est limitée à l’extraction rapide de texte |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si la collection est en lecture seule. |
| [iterator](#iterator--) | Renvoie un énumérateur pour la collection |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Obtient le nombre d’opérateurs qui décrivent le contenu de la page sans les initialiser. |
| [remove](#remove-com.aspose.pdf.Operator-) | Supprime un opérateur de la collection. |
| [replace](#replace-java.lang.Iterable-) | Remplace les opérateurs de la collection par d’autres opérateurs. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Remplace les opérateurs de la collection par d’autres opérateurs. |
| [resumeUpdate](#resumeUpdate--) | Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente. |
| [resumeUpdate](#resumeUpdate-boolean-) | Reprend la mise à jour du document. Met à jour le flux de contenu au cas où il y aurait des modifications en attente. Marque tous les opérateurs comme "changed" si le paramètre invalidate est vrai. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Définit l'opérateur par son indice. |
| [size](#size--) | Obtient le nombre d'opérateurs dans la collection. |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour des données de contenu. Le flux de contenu n'est pas mis à jour tant que ResumeUpdate n'est pas appelé. |
| [toList](#toList--) | Renvoie la liste des opérateurs. |
| [toString](#toString--) | Renvoie la représentation textuelle de l'opérateur. |
| [updateData](#updateData--) | Met à jour le flux d'objet. |
| [updateNormalizedData](#updateNormalizedData--) | Met à jour le flux d'objet en corrigeant les opérateurs GSave/GRestore absents. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
À usage interne uniquement !

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
À usage interne uniquement !

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte un objet visiteur IOperatorSelector pour traiter les opérateurs.

### add {#add-java.lang.Iterable-}
Ajoute à la collection tous les opérateurs d’une autre collection.

### add {#add-com.aspose.pdf.Operator-}
<p> Ajoute un nouvel opérateur à la collection. </p> <hr> <p> L’exemple montre comment ajouter des opérateurs à la fin de page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Ajoute des opérateurs à la fin des opérateurs de contenu. </p> <hr> <p> L’exemple montre comment ajouter un opérateur à la fin du contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Annule la dernière mise à jour. Cette méthode peut être appelée lorsque le changement ne doit pas déclencher la mise à jour du contenu.

### clear {#clear--}
```
public void clear()
```

<p> Supprime tous les opérateurs de la liste. </p> <hr> <p> L’exemple montre comment effacer le contenu de la page. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Effectue les tâches définies par l’application liées à la libération, la remise ou la réinitialisation des ressources non gérées.

### contains {#contains-com.aspose.pdf.Operator-}
Renvoie true si la collection contient l’opérateur donné.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Supprime un opérateur de la collection. </p> <hr> <p> L’exemple montre comment supprimer un opérateur par son indice. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice de l'opérateur à supprimer. La numérotation des opérateurs commence à 1. |

### delete {#delete-java.lang.Iterable-}
Supprime des opérateurs de la collection.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Supprime des opérateurs de la collection. </p> <hr> <p> L’exemple montre comment retirer un opérateur du contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

version interne non restreinte de Delete(index)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

### dispose {#dispose--}
```
public final void dispose()
```

Effectue les tâches définies par l’application liées à la libération, la remise ou la réinitialisation des ressources non gérées.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Obtient l’opérateur par son indice. </p> <hr> Exemple montre comment obtenir l’opérateur du contenu de la page par indice. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Version interne non restreinte de l’indexeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | valeur int |

**Returns:**
Objet opérateur

### insert {#insert-int-java.lang.Iterable-}
Insère des opérateurs à la position donnée.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Insère un opérateur dans la collection. </p> <hr> <p> L’exemple montre comment insérer un opérateur dans le contenu de la page. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Insère des opérateurs à la position donnée. </p> <hr> <p> L’exemple montre comment insérer un opérateur dans le contenu de la page. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Obtient le statut entre crochets de la séquence d’opérateurs, c’est‑à‑dire si ces opérateurs sont à l’intérieur des blocs q - Q

**Returns:**
valeur booléenne

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Obtient les commandes analysées

**Returns:**
valeur booléenne

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indique si la collection est limitée à l’extraction rapide de texte

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Renvoie un énumérateur pour la collection

**Returns:**
Énumérateur de collection

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Obtient le nombre d’opérateurs qui décrivent le contenu de la page sans les initialiser.

**Returns:**
valeur int

### remove {#remove-com.aspose.pdf.Operator-}
Supprime un opérateur de la collection.

### replace {#replace-java.lang.Iterable-}
Remplace les opérateurs de la collection par d’autres opérateurs.

### replace {#replace-com.aspose.pdf.Operator:A-}
Remplace les opérateurs de la collection par d’autres opérateurs.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Reprend la mise à jour du document. Met à jour le flux de contenu s’il y a des modifications en attente.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Reprend la mise à jour du document. Met à jour le flux de contenu au cas où il y aurait des modifications en attente. Marque tous les opérateurs comme "changed" si le paramètre invalidate est vrai.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| updateAll |  | Si vrai, tous les opérateurs de la collection sont marqués comme mis à jour. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Définit l'opérateur par son indice.

### size {#size--}
```
public int size()
```

Obtient le nombre d'opérateurs dans la collection.

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
liste d'opérateurs.

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation textuelle de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.

### updateData {#updateData--}
```
public void updateData()
```

Met à jour le flux d'objet.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Met à jour le flux d'objet en corrigeant les opérateurs GSave/GRestore absents.
