---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les paramètres OCSP utilisés pendant le processus de signature."
type: docs
weight: 5360
url: /fr/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

Représente les paramètres OCSP utilisés pendant le processus de signature.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | Initialise une nouvelle instance de la classe {@code TimestampSettings}. |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | Initialise une nouvelle instance de la classe {@code TimestampSettings}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | Obtient les informations d'authentification de base, Username et password sont combinés dans une chaîne "username:password". |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | Obtient/définit l'algorithme de hachage pour les fonctions de hachage internes. |
| [getServerUrl](#getServerUrl--) | Obtient l'url du serveur d'horodatage. |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | Définit les informations d'authentification de base, Username et password sont combinés dans une chaîne "username:password". |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | Obtient/définit l'algorithme de hachage pour les fonctions de hachage internes. |
| [setServerUrl](#setServerUrl-java.lang.String-) | Définit l'url du serveur d'horodatage. |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
Initialise une nouvelle instance de la classe {@code TimestampSettings}.

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
Initialise une nouvelle instance de la classe {@code TimestampSettings}.

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

Obtient les informations d'authentification de base, Username et password sont combinés dans une chaîne "username:password".

**Returns:**
valeur String

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

Obtient/définit l'algorithme de hachage pour les fonctions de hachage internes.

**Returns:**
Élément DigestHashAlgorithm @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

Obtient l'url du serveur d'horodatage.

**Returns:**
valeur String

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
Définit les informations d'authentification de base, Username et password sont combinés dans une chaîne "username:password".

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
Obtient/définit l'algorithme de hachage pour les fonctions de hachage internes.

### setServerUrl {#setServerUrl-java.lang.String-}
Définit l'url du serveur d'horodatage.
