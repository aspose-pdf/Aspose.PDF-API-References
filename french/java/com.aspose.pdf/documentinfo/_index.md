---
title: "DocumentInfo"
linktitle: "DocumentInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les métadonnées d'un document PDF."
type: docs
weight: 1160
url: /fr/java/com.aspose.pdf/documentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.Generic.Dictionary< String , String > com.aspose.pdf.DocumentInfo, com.aspose.ms.System.Collections.Generic.Dictionary< String , String >, com.aspose.pdf.DocumentInfo

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, String >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, String >>

```
public final class DocumentInfo extends com.aspose.ms.System.Collections.Generic.Dictionary< String , String >
```

Représente les métadonnées d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentInfo](#DocumentInfo-com.aspose.pdf.IDocument-) | Initialiser l'instance DocumentInfo. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addItem](#addItem-java.lang.String-java.lang.String-) | Ajoute un élément avec la clé et la valeur spécifiées dans la collection. |
| [clear](#clear--) | Efface les informations du document. |
| [clearCustomData](#clearCustomData--) | Efface uniquement les données personnalisées, laisse toutes les autres valeurs prédéfinies (Title, Author, etc.). |
| [get_Item](#get_Item-java.lang.String-) | Obtient la valeur associée à la clé spécifiée. |
| [getAuthor](#getAuthor--) | Obtient l'auteur du document. |
| [getCreationDate](#getCreationDate--) | Obtient la date de création du document. |
| [getCreationTimeZone](#getCreationTimeZone--) | Fuseau horaire de la date de création en millisecondes. |
| [getCreator](#getCreator--) | Obtient le créateur du document. |
| [getKeywords](#getKeywords--) | Obtient les mots‑clés du document. |
| [getModDate](#getModDate--) | Obtient la date de modification du document. |
| [getModTimeZone](#getModTimeZone--) | Fuseau horaire de la date de modification. |
| [getProducer](#getProducer--) | Obtient le producteur du document. |
| [getSubject](#getSubject--) | Obtient le sujet du document. |
| [getTitle](#getTitle--) | Obtient le titre du document. |
| [getTrapped](#getTrapped--) | Obtient le drapeau trapped. |
| [isPredefinedKey](#isPredefinedKey-java.lang.String-) | Détermine si la clé est prédéfinie (Title, Author, etc.), pas personnalisée. |
| [remove](#remove-java.lang.String-) | Supprime l'élément avec la clé spécifiée de la collection. |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Définit la valeur associée à la clé spécifiée. |
| [setAuthor](#setAuthor-java.lang.String-) | Définit l'auteur du document. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Définit la date de création du document. |
| [setCreationTimeZone](#setCreationTimeZone-double-) | Fuseau horaire de la date de création en millisecondes. |
| [setCreator](#setCreator-java.lang.String-) | Définit le créateur du document. |
| [setKeywords](#setKeywords-java.lang.String-) | Définit les mots‑clés du document. |
| [setModDate](#setModDate-java.util.Date-) | Définit la date de modification du document. |
| [setModTimeZone](#setModTimeZone-double-) | Fuseau horaire de la date de modification. |
| [setProducer](#setProducer-java.lang.String-) | Définit le producteur du document. |
| [setSubject](#setSubject-java.lang.String-) | Définit le sujet du document. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre du document. |
| [setTrapped](#setTrapped-java.lang.String-) | Définit le drapeau de trappage. |

### DocumentInfo {#DocumentInfo-com.aspose.pdf.IDocument-}
Initialiser l'instance DocumentInfo.

### addItem {#addItem-java.lang.String-java.lang.String-}
Ajoute un élément avec la clé et la valeur spécifiées dans la collection.

### clear {#clear--}
```
public void clear()
```

Efface les informations du document.

### clearCustomData {#clearCustomData--}
```
public void clearCustomData()
```

Efface uniquement les données personnalisées, laisse toutes les autres valeurs prédéfinies (Title, Author, etc.).

### get_Item {#get_Item-java.lang.String-}
Obtient la valeur associée à la clé spécifiée.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

Obtient l'auteur du document.

**Returns:**
valeur String

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtient la date de création du document.

**Returns:**
Objet Date

### getCreationTimeZone {#getCreationTimeZone--}
```
public double getCreationTimeZone()
```

Fuseau horaire de la date de création en millisecondes.

**Returns:**
valeur double

### getCreator {#getCreator--}
```
public String getCreator()
```

Obtient le créateur du document.

**Returns:**
valeur String

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

Obtient les mots‑clés du document.

**Returns:**
valeur String

### getModDate {#getModDate--}
```
public Date getModDate()
```

Obtient la date de modification du document.

**Returns:**
Objet Date

### getModTimeZone {#getModTimeZone--}
```
public double getModTimeZone()
```

Fuseau horaire de la date de modification.

**Returns:**
valeur double

### getProducer {#getProducer--}
```
public String getProducer()
```

Obtient le producteur du document.

**Returns:**
valeur String

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtient le sujet du document.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient le titre du document.

**Returns:**
valeur String

### getTrapped {#getTrapped--}
```
public String getTrapped()
```

Obtient le drapeau trapped.

**Returns:**
valeur String

### isPredefinedKey {#isPredefinedKey-java.lang.String-}
Détermine si la clé est prédéfinie (Title, Author, etc.), pas personnalisée.

### remove {#remove-java.lang.String-}
Supprime l'élément avec la clé spécifiée de la collection.

### set_Item {#set_Item-java.lang.String-java.lang.String-}
Définit la valeur associée à la clé spécifiée.

### setAuthor {#setAuthor-java.lang.String-}
Définit l'auteur du document.

### setCreationDate {#setCreationDate-java.util.Date-}
Définit la date de création du document.

### setCreationTimeZone {#setCreationTimeZone-double-}
```
public void setCreationTimeZone(double value)
```

Fuseau horaire de la date de création en millisecondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | en millisecondes |

### setCreator {#setCreator-java.lang.String-}
Définit le créateur du document.

### setKeywords {#setKeywords-java.lang.String-}
Définit les mots‑clés du document.

### setModDate {#setModDate-java.util.Date-}
Définit la date de modification du document.

### setModTimeZone {#setModTimeZone-double-}
```
public void setModTimeZone(double value)
```

Fuseau horaire de la date de modification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setProducer {#setProducer-java.lang.String-}
Définit le producteur du document.

### setSubject {#setSubject-java.lang.String-}
Définit le sujet du document.

### setTitle {#setTitle-java.lang.String-}
Définit le titre du document.

### setTrapped {#setTrapped-java.lang.String-}
Définit le drapeau de trappage.
