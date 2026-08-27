---
title: "Métadonnées"
linktitle: "Métadonnées"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Fournit l’accès au flux de métadonnées XMP."
type: docs
weight: 3050
url: /fr/java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Fournit l’accès au flux de métadonnées XMP.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Ajoute une paire avec la clé et la valeur dans le dictionnaire. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Ajoute une valeur aux métadonnées. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Ajoute une extension pdf aux métadonnées. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Ajoute une valeur aux métadonnées. |
| [clear](#clear--) | Efface les métadonnées. |
| [contains](#contains-java.lang.String-) | Vérifie si la clé est contenue dans les métadonnées. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire. |
| [containsKey](#containsKey-java.lang.String-) | Détermine si ce dictionnaire contient la clé spécifiée. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Copie les éléments de la collection dans un tableau. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copie les éléments de la collection dans un tableau. |
| [get_Item](#get_Item-java.lang.String-) | Obtient les données des métadonnées. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | Pour usage interne uniquement. Obtient le dictionnaire des champs d'extension. |
| [getExtensionFields](#getExtensionFields--) | <p> Obtient le dictionnaire des champs d'extension. </p> |
| [getItem](#getItem-java.lang.String-) | Obtient les données des métadonnées. |
| [getKeys](#getKeys--) | Obtient la collection des clés de métadonnées. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Renvoie l'URI de l'espace de noms par préfixe. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Renvoie le préfixe par URI d'espace de noms. |
| [getSyncRoot](#getSyncRoot--) | Obtient l'objet de synchronisation de la collection. |
| [getValues](#getValues--) | Obtient les valeurs des métadonnées. |
| [isFixedSize](#isFixedSize--) | Vérifie si la collection a une taille fixe. |
| [isReadOnly](#isReadOnly--) | Vérifie si la collection est en lecture seule. |
| [isSynchronized](#isSynchronized--) | Vérifie si la collection est synchronisée. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Renvoie l'énumérateur du dictionnaire. |
| [iteratorIE](#iteratorIE--) | Obtient l'énumérateur de la collection. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Enregistre l'URI de l'espace de noms. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Enregistre l'URI de l'espace de noms. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Supprime la paire clé/valeur de la collection. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Supprime l'entrée des métadonnées. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Définit les données à partir des métadonnées. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Définit les données à partir des métadonnées. |
| [size](#size--) | Obtient le nombre d'éléments dans la collection. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Ajoute une paire avec la clé et la valeur dans le dictionnaire.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Ajoute une valeur aux métadonnées.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Ajoute une extension pdf aux métadonnées.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Ajoute une valeur aux métadonnées.

### clear {#clear--}
```
public void clear()
```

Efface les métadonnées.

### contains {#contains-java.lang.String-}
Vérifie si la clé est contenue dans les métadonnées.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Vérifie si la paire clé-valeur spécifiée est contenue dans le dictionnaire.

### containsKey {#containsKey-java.lang.String-}
Détermine si ce dictionnaire contient la clé spécifiée.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Copie les éléments de la collection dans un tableau.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copie les éléments de la collection dans un tableau.

### get_Item {#get_Item-java.lang.String-}
Obtient les données des métadonnées.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

Pour usage interne uniquement. Obtient le dictionnaire des champs d'extension.

**Returns:**
objet interne

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Obtient le dictionnaire des champs d'extension. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} objet

### getItem {#getItem-java.lang.String-}
Obtient les données des métadonnées.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Obtient la collection des clés de métadonnées.

**Returns:**
objet ICollection

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Renvoie l'URI de l'espace de noms par préfixe.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Renvoie le préfixe par URI d'espace de noms.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient l'objet de synchronisation de la collection.

**Returns:**
Objet pour la synchronisation

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Obtient les valeurs des métadonnées.

**Returns:**
objet ICollection

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Vérifie si la collection a une taille fixe.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Vérifie si la collection est en lecture seule.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Vérifie si la collection est synchronisée.

**Returns:**
valeur booléenne

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Renvoie l'énumérateur du dictionnaire.

**Returns:**
Énumérateur.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Obtient l'énumérateur de la collection.

**Returns:**
Objet IEnumerator @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Enregistre l'URI de l'espace de noms.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Enregistre l'URI de l'espace de noms.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Supprime la paire clé/valeur de la collection.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Supprime l'entrée des métadonnées.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Définit les données à partir des métadonnées.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Définit les données à partir des métadonnées.

### size {#size--}
```
public int size()
```

Obtient le nombre d'éléments dans la collection.

**Returns:**
valeur int

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Essaie de trouver la clé dans le dictionnaire et récupère la valeur si elle est trouvée.
