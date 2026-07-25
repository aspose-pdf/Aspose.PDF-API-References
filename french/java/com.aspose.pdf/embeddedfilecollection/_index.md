---
title: "EmbeddedFileCollection"
linktitle: "EmbeddedFileCollection"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant la collection de fichiers intégrés."
type: docs
weight: 1200
url: /fr/java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Classe représentant la collection de fichiers intégrés.

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Ajoute la spécification du fichier intégré dans la collection. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Ajoute le fichier aux fichiers intégrés avec la clé spécifiée. |
| [clear](#clear--) | Supprimer tous les fichiers incorporés du document. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Détermine si la collection contient la spécification de fichier spécifiée. Non pris en charge. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Copie le tableau d'objets FileSpecification dans la collection. |
| [delete](#delete--) | Supprimer tous les fichiers incorporés du document. |
| [delete](#delete-java.lang.String-) | Supprimer tous les fichiers incorporés du document. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Supprime le fichier de la collection par sa clé dans la collection. |
| [findByName](#findByName-java.lang.String-) | Renvoie le fichier incorporé par son nom. |
| [get_Item](#get_Item-int-) | Obtient le fichier incorporé par son index. |
| [get_Item](#get_Item-java.lang.String-) | Obtient le fichier incorporé par son nom. |
| [getKeys](#getKeys--) | Renvoie la liste des clés de pièces jointes de fichiers. |
| [getSyncRoot](#getSyncRoot--) | Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Vérifie si la structure des fichiers incorporés existe. Retourne TRUE si la structure existe, et FALSE sinon. Si le document n'a jamais contenu de fichiers incorporés, cette structure n'a pas été créée et est absente. |
| [isReadOnly](#isReadOnly--) | Détermine si la collection est en lecture seule. Retourne toujours false. |
| [isSynchronized](#isSynchronized--) | Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Renvoie l'énumérateur de la collection. |
| [iterator](#iterator--) | Renvoie l'énumérateur de la collection. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Supprime la spécification de fichier spécifiée de la collection. Non pris en charge. |
| [size](#size--) | Obtient le nombre de fichiers incorporés dans la collection. |

### add {#add-com.aspose.pdf.FileSpecification-}
Ajoute la spécification du fichier intégré dans la collection.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Ajoute le fichier aux fichiers intégrés avec la clé spécifiée.

### clear {#clear--}
```
public void clear()
```

Supprimer tous les fichiers incorporés du document.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Détermine si la collection contient la spécification de fichier spécifiée. Non pris en charge.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Copie le tableau d'objets FileSpecification dans la collection.

### delete {#delete--}
```
public void delete()
```

Supprimer tous les fichiers incorporés du document.

### delete {#delete-java.lang.String-}
Supprimer tous les fichiers incorporés du document.

### deleteByKey {#deleteByKey-java.lang.String-}
Supprime le fichier de la collection par sa clé dans la collection.

### findByName {#findByName-java.lang.String-}
Renvoie le fichier incorporé par son nom.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Obtient le fichier incorporé par son index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice du fichier incorporé. La numérotation commence à 1. |

**Returns:**
Spécification du fichier incorporé récupéré

### get_Item {#get_Item-java.lang.String-}
Obtient le fichier incorporé par son nom.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Renvoie la liste des clés de pièces jointes de fichiers.

**Returns:**
Liste de valeurs String

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Obtient un objet pouvant être utilisé pour synchroniser l'accès à cette collection.

**Returns:**
Objet pour la synchronisation

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Vérifie si la structure des fichiers incorporés existe. Retourne TRUE si la structure existe, et FALSE sinon. Si le document n'a jamais contenu de fichiers incorporés, cette structure n'a pas été créée et est absente.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Détermine si la collection est en lecture seule. Retourne toujours false.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Obtient une valeur indiquant si l'accès à cette collection est synchronisé (thread‑safe).

**Returns:**
valeur booléenne

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Renvoie l'énumérateur de la collection.

**Returns:**
Énumérateur de la collection.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Renvoie l'énumérateur de la collection.

**Returns:**
Énumérateur de la collection.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Supprime la spécification de fichier spécifiée de la collection. Non pris en charge.

### size {#size--}
```
public int size()
```

Obtient le nombre de fichiers incorporés dans la collection.

**Returns:**
valeur int
