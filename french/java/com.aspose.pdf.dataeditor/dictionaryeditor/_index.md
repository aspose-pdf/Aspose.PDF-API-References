---
title: "DictionaryEditor"
linktitle: "DictionaryEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe pour accéder au dictionnaire arborescent d'un document (dictionnaire du document, dictionnaire de page, dictionnaire des ressources)."
type: docs
weight: 70
url: /fr/java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

Une classe pour accéder au dictionnaire arborescent d'un document (dictionnaire du document, dictionnaire de page, dictionnaire des ressources).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException Les ressources sont null. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Définir ICosPdfPrimitive dans le dictionnaire. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Définir {@link ICosPdfPrimitive} dans le dictionnaire. |
| [clear](#clear--) | Supprime tous les éléments du {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Détermine si le DictionaryEditor contient une valeur spécifique. |
| [containsKey](#containsKey-java.lang.String-) | Détermine si le {@link DictionaryEditor} contient un élément avec la clé spécifiée. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les éléments du DictionaryEditor dans un tableau, en commençant à un indice de tableau particulier. |
| [get_Item](#get_Item-java.lang.String-) | Obtient ou définit l'élément avec la clé spécifiée. |
| [getAllKeys](#getAllKeys--) | Collection complète de clés. Contient des clés modifiables et non modifiables. |
| [getKeys](#getKeys--) | Collection de clés modifiables. |
| [getValues](#getValues--) | Obtient un {@link ICollection} contenant les valeurs du {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si le {@link DictionaryEditor} est en lecture seule. |
| [iterator](#iterator--) | Renvoie un énumérateur qui parcourt la collection. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime la première occurrence d'un objet spécifique du DictionaryEditor. |
| [remove](#remove-java.lang.String-) | Supprime l'élément avec la clé spécifiée du {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Obtient ou définit l'élément avec la clé spécifiée. |
| [size](#size--) | Obtient le nombre d'éléments contenus dans le {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | Pour accéder à des types de données simples comme string, name, bool, number. Retourne null pour les autres types. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException Les ressources sont null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Définir ICosPdfPrimitive dans le dictionnaire.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Définir {@link ICosPdfPrimitive} dans le dictionnaire.

### clear {#clear--}
```
public final void clear()
```

Supprime tous les éléments du {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Détermine si le DictionaryEditor contient une valeur spécifique.

### containsKey {#containsKey-java.lang.String-}
Détermine si le {@link DictionaryEditor} contient un élément avec la clé spécifiée.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les éléments du DictionaryEditor dans un tableau, en commençant à un indice de tableau particulier.

### get_Item {#get_Item-java.lang.String-}
Obtient ou définit l'élément avec la clé spécifiée.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Collection complète de clés. Contient des clés modifiables et non modifiables.

**Returns:**
Itérable d'instance String

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Collection de clés modifiables.

**Returns:**
Itérable d'instance String

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Obtient un {@link ICollection} contenant les valeurs du {@link DictionaryEditor}.

**Returns:**
Itérable d'instance ICosPdfPrimitive

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtient une valeur indiquant si le {@link DictionaryEditor} est en lecture seule.

**Returns:**
true si le {@link DictionaryEditor} est en lecture seule ; sinon, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Renvoie un énumérateur qui parcourt la collection.

**Returns:**
Un itérateur qui peut être utilisé pour parcourir la collection.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime la première occurrence d'un objet spécifique du DictionaryEditor.

### remove {#remove-java.lang.String-}
Supprime l'élément avec la clé spécifiée du {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Obtient ou définit l'élément avec la clé spécifiée.

### size {#size--}
```
public final int size()
```

Obtient le nombre d'éléments contenus dans le {@link DictionaryEditor}.

**Returns:**
valeur int

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
Pour accéder à des types de données simples comme string, name, bool, number. Retourne null pour les autres types.
