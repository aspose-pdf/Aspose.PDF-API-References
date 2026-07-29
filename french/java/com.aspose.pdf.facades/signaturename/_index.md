---
title: "SignatureName"
linktitle: "SignatureName"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe pour un nom de signature. Représente un nom de signature plus précis. Utilisé à la place des noms de chaîne. Vous permet de présenter des signatures avec les mêmes noms de chaîne."
type: docs
weight: 690
url: /fr/java/com.aspose.pdf.facades/signaturename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.SignatureName

```
public final class SignatureName extends Object
```

Représente une classe pour un nom de signature. Représente un nom de signature plus précis. Utilisé à la place des noms de chaîne. Vous permet de présenter des signatures avec les mêmes noms de chaîne.

## Champs

| Champ | Description |
| --- | --- |
| [FullName](#FullName) | Obtient le nom complet de la signature, fournissant un identifiant unique et précis pour le champ de signature. |
| [Name](#Name) | Obtient le nom d'une signature. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [equals](#equals-java.lang.Object-) | Détermine si cette instance et un objet spécifié sont égaux. |
| [getSignatureDictionary](#getSignatureDictionary--) | Obtient le dictionnaire de la signature. |
| [hashCode](#hashCode--) | Renvoie un code de hachage pour cette instance basé sur la propriété FullName. |
| [hasSignature](#hasSignature--) | Indique si la signature est présente ou non. |
| [toString](#toString--) | Renvoie une représentation sous forme de chaîne de l'instance {@link SignatureName}, en utilisant principalement son nom. |

### FullName {#FullName}
```
public final String FullName
```

Obtient le nom complet de la signature, fournissant un identifiant unique et précis pour le champ de signature.

### Name {#Name}
```
public final String Name
```

Obtient le nom d'une signature.

### equals {#equals-java.lang.Object-}
Détermine si cette instance et un objet spécifié sont égaux.

### getSignatureDictionary {#getSignatureDictionary--}
```
public final com.aspose.pdf.engine.data.IPdfDictionary getSignatureDictionary()
```

Obtient le dictionnaire de la signature.

**Returns:**
Le dictionnaire de la signature ou null s'il n'est pas trouvé.

### hashCode {#hashCode--}
```
public int hashCode()
```

Renvoie un code de hachage pour cette instance basé sur la propriété FullName.

**Returns:**
Un entier représentant le code de hachage de la propriété FullName.

### hasSignature {#hasSignature--}
```
public final boolean hasSignature()
```

Indique si la signature est présente ou non.

**Returns:**
valeur booléenne

### toString {#toString--}
```
public String toString()
```

Renvoie une représentation sous forme de chaîne de l'instance {@link SignatureName}, en utilisant principalement son nom.

**Returns:**
Une chaîne représentant le nom de la signature.
