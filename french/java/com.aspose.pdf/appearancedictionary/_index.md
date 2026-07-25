---
title: "AppearanceDictionary"
linktitle: "AppearanceDictionary"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page."
type: docs
weight: 150
url: /fr/java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Dictionnaire d'apparence d'annotation spécifiant comment l'annotation doit être présentée visuellement sur la page.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Ajoute un élément avec la clé et la valeur fournies. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ajoute une paire avec la clé et la valeur dans le dictionnaire. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Ajoute un X form pour la clé spécifiée. |
| [clear](#clear--) | Supprime tous les éléments du dictionnaire. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [containsKey](#containsKey-java.lang.String-) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Renvoie un objet IDictionaryEnumerator pour le dictionnaire. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les éléments de l'ICollection dans un tableau, en commençant à un indice de tableau particulier. |
| [get_Item](#get_Item-java.lang.String-) | Représente une forme pratique pour obtenir les flux d'apparence. |
| [getDict](#getDict--) | Obtient le dictionnaire pdf |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Valeurs D).state, où N - apparence normale, R - apparence au survol, D - apparence enfoncée et state - le nom de l'état (par ex. On, Off pour les cases à cocher). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\ | R\ | Valeurs D).state, où N - apparence normale, R - apparence au survol, D - apparence enfoncée et state - le nom de l'état (par ex. On, Off pour les cases à cocher). |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès au dictionnaire. |
| [getValues_](#getValues_--) | Obtient la liste des valeurs du dictionnaire. La collection résultante contient la liste des objets XForm. |
| [getValues](#getValues--) | Obtient la liste des valeurs du dictionnaire. La collection résultante contient la liste des objets XForm. |
| [isFixedSize](#isFixedSize--) | Obtient une valeur indiquant si le dictionnaire a une taille fixe. |
| [isReadOnly](#isReadOnly--) | Obtient une valeur indiquant si le dictionnaire est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès au dictionnaire est synchronisé (thread safe). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Énumérateur pour la collection. |
| [iterator](#iterator--) | Renvoie un objet IDictionaryEnumerator pour le dictionnaire. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime la paire clé/valeur de la collection. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Supprime la clé du dictionnaire. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Obtient le nombre d'éléments contenus dans le dictionnaire. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### add {#add-java.lang.Object-java.lang.Object-}
Ajoute un élément avec la clé et la valeur fournies.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ajoute une paire avec la clé et la valeur dans le dictionnaire.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Ajoute un X form pour la clé spécifiée.

### clear {#clear--}
```
public void clear()
```

Supprime tous les éléments du dictionnaire.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire.

### containsKey {#containsKey-java.lang.String-}
Détermine si ce dictionnaire contient la clé spécifiée.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Renvoie un objet IDictionaryEnumerator pour le dictionnaire. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les éléments de l'ICollection dans un tableau, en commençant à un indice de tableau particulier.

### get_Item {#get_Item-java.lang.String-}
Représente une forme pratique pour obtenir les flux d'apparence.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Obtient le dictionnaire pdf

**Returns:**
Objet IPdfDictionary

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Obtient les clés du dictionnaire. Si le dictionnaire d'apparence possède des sous-dictionnaires, alors {@code Keys} contient les valeurs (N|R|D).state, où N - apparence normale, R - apparence au survol, D - apparence enfoncée et state - le nom de l'état (par ex. On, Off pour les cases à cocher).

**Returns:**
Liste de valeurs String

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtient les clés du dictionnaire. Si le dictionnaire d'apparence possède des sous-dictionnaires, alors {@code Keys} contient les valeurs (N|R|D).state, où N - apparence normale, R - apparence au survol, D - apparence enfoncée et state - le nom de l'état (par ex. On, Off pour les cases à cocher).

**Returns:**
Liste de valeurs String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès au dictionnaire.

**Returns:**
Objet pour la synchronisation

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Obtient la liste des valeurs du dictionnaire. La collection résultante contient la liste des objets XForm.

**Returns:**
Liste de valeurs XForm

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Obtient la liste des valeurs du dictionnaire. La collection résultante contient la liste des objets XForm.

**Returns:**
Liste de valeurs XForm

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Obtient une valeur indiquant si le dictionnaire a une taille fixe.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Obtient une valeur indiquant si le dictionnaire est en lecture seule.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient une valeur indiquant si l'accès au dictionnaire est synchronisé (thread safe).

**Returns:**
valeur booléenne

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Énumérateur pour la collection.

**Returns:**
énumérateur des éléments de la collection.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Renvoie un objet IDictionaryEnumerator pour le dictionnaire.

**Returns:**
Énumérateur du dictionnaire.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime la paire clé/valeur de la collection.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Supprime la clé du dictionnaire.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments contenus dans le dictionnaire.

**Returns:**
valeur int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée.
