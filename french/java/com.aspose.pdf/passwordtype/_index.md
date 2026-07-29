---
title: "PasswordType"
linktitle: "PasswordType"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette énumération représente les types de mots de passe connus utilisés pour les documents PDF protégés par mot de passe."
type: docs
weight: 3520
url: /fr/java/com.aspose.pdf/passwordtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PasswordType > com.aspose.pdf.PasswordType, java.lang.Enum < PasswordType >, com.aspose.pdf.PasswordType

**All Implemented Interfaces:**
Serializable, Comparable < PasswordType >

```
public enum PasswordType extends Enum < PasswordType >
```

Cette énumération représente les types de mots de passe connus utilisés pour les documents PDF protégés par mot de passe.

## Champs

| Champ | Description |
| --- | --- |
| [Inaccessible](#Inaccessible) | Le document PDF est protégé par mot de passe, mais les mots de passe utilisateur et propriétaire ne sont pas vides et aucun des mots de passe n'a été défini ou le mot de passe fourni était incorrect. |
| [None](#None) | Le document PDF n'est pas protégé par mot de passe. |
| [Owner](#Owner) | Le document PDF a été ouvert en utilisant le mot de passe de modification des autorisations (accès complet). |
| [User](#User) | Le document PDF a été ouvert en utilisant le mot de passe d'ouverture du document (accès restreint). |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### Inaccessible {#Inaccessible}
```
public static final PasswordType Inaccessible
```

Le document PDF est protégé par mot de passe, mais les mots de passe utilisateur et propriétaire ne sont pas vides et aucun des mots de passe n'a été défini ou le mot de passe fourni était incorrect.

### None {#None}
```
public static final PasswordType None
```

Le document PDF n'est pas protégé par mot de passe.

### Owner {#Owner}
```
public static final PasswordType Owner
```

Le document PDF a été ouvert en utilisant le mot de passe de modification des autorisations (accès complet).

### User {#User}
```
public static final PasswordType User
```

Le document PDF a été ouvert en utilisant le mot de passe d'ouverture du document (accès restreint).

### getByValue {#getByValue-int-}
```
public static PasswordType getByValue(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static PasswordType [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
