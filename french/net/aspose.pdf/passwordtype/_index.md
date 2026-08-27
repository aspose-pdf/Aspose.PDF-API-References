---
title: "Énumération PasswordType"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.PasswordType. Cette énumération représente les types de mots de passe connus utilisés pour les documents pdf protégés par mot de passe."
type: docs
weight: 8430
url: /fr/net/aspose.pdf/passwordtype/
---
## PasswordType enumeration

Cette énumération représente les types de mot de passe connus utilisés pour les documents pdf protégés par mot de passe.

```csharp
public enum PasswordType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Le document PDF n'est pas protégé par mot de passe. |
| User | `1` | Le document PDF a été ouvert en utilisant le mot de passe d'ouverture du document (accès restreint). |
| Owner | `2` | Le document PDF a été ouvert en utilisant le mot de passe de modification des autorisations (accès complet). |
| Inaccessible | `3` | Le document PDF est protégé par mot de passe mais les mots de passe utilisateur et propriétaire ne sont pas vides et aucun des mots de passe n'a été défini ou le mot de passe fourni était incorrect. Il est donc impossible de déduire le type du mot de passe. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


