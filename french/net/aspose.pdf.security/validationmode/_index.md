---
title: "Enum ValidationMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Security.ValidationMode enum. Spécifie le mode de validation pour les processus de validation de signature PDF"
type: docs
weight: 10240
url: /fr/net/aspose.pdf.security/validationmode/
---
## ValidationMode enumeration

Spécifie le mode de validation pour les processus de validation de signature PDF.

```csharp
public enum ValidationMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Représente un mode où la validation n'est pas effectuée. |
| OnlyCheck | `1` | Représente le mode dans lequel la validation est effectuée, mais son résultat n'affecte pas la validation de la signature numérique. Vous pouvez vérifier vous‑même le résultat de la validation. |
| Strict | `2` | Représente le mode dans lequel la validation est effectuée et son résultat affecte la validation de la signature numérique. Si le certificat ne peut pas être vérifié, la signature numérique sera considérée comme invalide. Vous pouvez vérifier vous‑même le résultat de la validation. |

### Voir aussi

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


