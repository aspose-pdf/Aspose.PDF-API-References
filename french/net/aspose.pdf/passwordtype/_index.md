---
title: Enum PasswordType
second_title: Aspose.PDF for .NET API Reference
description: Enum PasswordType d'Aspose.Pdf. Cet enum représente les types de mots de passe connus utilisés pour les documents PDF protégés par mot de passe
type: docs
weight: 8290
url: /fr/net/aspose.pdf/passwordtype/
---
## Énumération PasswordType

Cet enum représente les types de mots de passe connus utilisés pour les documents PDF protégés par mot de passe.

```csharp
public enum PasswordType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Aucun | `0` | Le document PDF n'est pas protégé par mot de passe. |
| Utilisateur | `1` | Le document PDF a été ouvert en utilisant le mot de passe d'ouverture du document (accès restreint). |
| Propriétaire | `2` | Le document PDF a été ouvert en utilisant le mot de passe de changement de permissions (accès complet). |
| Inaccessible | `3` | Le document PDF est protégé par mot de passe mais les mots de passe utilisateur et propriétaire ne sont pas vides et aucun des mots de passe n'a été défini ou le mot de passe fourni était incorrect. Il est donc impossible de déduire le type de mot de passe. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)