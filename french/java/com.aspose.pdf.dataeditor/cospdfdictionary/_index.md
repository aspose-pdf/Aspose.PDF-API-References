---
title: "CosPdfDictionary"
linktitle: "CosPdfDictionary"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe pour accéder au dictionnaire d'un objet."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

Une classe pour accéder au dictionnaire d'un objet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Crée un dictionnaire à partir des ressources. @exception ArgumentNullException Les ressources sont null. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Définir ICosPdfPrimitive dans le dictionnaire. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Définit {@link ICosPdfPrimitive} dans le dictionnaire. @exception ArgumentException Lève une exception si la clé/la valeur ne peut pas être modifiée ou supprimée. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ajouter une paire d'éléments. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Ajouter un élément. |
| [clear](#clear--) | Supprime tous les éléments du {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Détermine si le CosPdfDictionary contient une valeur spécifique. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Renvoie true si l'élément est présent |
| [containsKey](#containsKey-java.lang.String-) | Détermine si le {@link CosPdfDictionary} contient un élément avec la clé spécifiée. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les éléments du CosPdfDictionary dans un tableau, en commençant à un indice de tableau particulier. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copier vers le tableau |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Crée un dictionnaire vide qui sera attaché au document. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Crée un dictionnaire vide qui sera attaché à la page. |
| [get_Item](#get_Item-java.lang.String-) | Obtient ou définit l'élément avec la clé spécifiée. |
| [getAllKeys](#getAllKeys--) | Collection complète de clés. Contient des clés modifiables et non modifiables. |
| [getKeys](#getKeys--) | Collection de clés modifiables. |
| [getValues](#getValues--) | Obtient une {@link ICollection} contenant les valeurs du {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si le {@link CosPdfDictionary} est en lecture seule. |
| [iterator](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime la première occurrence d'un objet spécifique du CosPdfDictionary. |
| [remove](#remove-java.lang.String-) | Supprime l'élément avec la clé spécifiée du {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprimer l'élément |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Supprimer l'élément par clé. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtient ou définit l'élément avec la clé spécifiée. @exception ArgumentNullException La clé est nulle. @exception KeyNotFoundException La propriété est récupérée et la clé n'est pas trouvée. @exception ArgumentException Lève une exception si la clé ne peut pas être modifiée/définie. |
| [size](#size--) | Obtient le nombre d'éléments contenus dans le {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Tente de convertir cette instance en {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Pour accéder à des types de données simples comme string, name, bool, number. Retourne null pour les autres types. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Essayer d'obtenir la valeur |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Crée un dictionnaire à partir des ressources. @exception ArgumentNullException Les ressources sont null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Définir ICosPdfPrimitive dans le dictionnaire.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Définit {@link ICosPdfPrimitive} dans le dictionnaire. @exception ArgumentException Lève une exception si la clé/la valeur ne peut pas être modifiée ou supprimée.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ajouter une paire d'éléments.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Ajouter un élément.

### clear {#clear--}
```
public final void clear()
```

Supprime tous les éléments du {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Détermine si le CosPdfDictionary contient une valeur spécifique.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Renvoie true si l'élément est présent

### containsKey {#containsKey-java.lang.String-}
Détermine si le {@link CosPdfDictionary} contient un élément avec la clé spécifiée.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les éléments du CosPdfDictionary dans un tableau, en commençant à un indice de tableau particulier.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copier vers le tableau

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Crée un dictionnaire vide qui sera attaché au document.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Crée un dictionnaire vide qui sera attaché à la page.

### get_Item {#get_Item-java.lang.String-}
Obtient ou définit l'élément avec la clé spécifiée.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Collection complète de clés. Contient des clés modifiables et non modifiables.

**Returns:**
Liste de valeurs String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Collection de clés modifiables.

**Returns:**
Liste de valeurs String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtient une {@link ICollection} contenant les valeurs du {@link CosPdfDictionary}.

**Returns:**
Liste d'instances ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le {@link CosPdfDictionary} est en lecture seule.

**Returns:**
true si le {@link CosPdfDictionary} est en lecture seule ; sinon, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Returns:**
Un itérateur qui peut être utilisé pour parcourir la collection.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime la première occurrence d'un objet spécifique du CosPdfDictionary.

### remove {#remove-java.lang.String-}
Supprime l'élément avec la clé spécifiée du {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprimer l'élément

### removeItemByKey {#removeItemByKey-java.lang.String-}
Supprimer l'élément par clé.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtient ou définit l'élément avec la clé spécifiée. @exception ArgumentNullException La clé est nulle. @exception KeyNotFoundException La propriété est récupérée et la clé n'est pas trouvée. @exception ArgumentException Lève une exception si la clé ne peut pas être modifiée/définie.

### size {#size--}
```
public final int size()
```

Obtient le nombre d'éléments contenus dans le {@link CosPdfDictionary}.

**Returns:**
valeur int

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Tente de convertir cette instance en {@link CosPdfDictionary}.

**Returns:**
null si l'instance n'est pas {@link CosPdfDictionary} sinon {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Pour accéder à des types de données simples comme string, name, bool, number. Retourne null pour les autres types.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Essayer d'obtenir la valeur
