---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Security.ValidationMode. Spécifie le mode de validation pour les processus de validation de signature PDF
type: docs
weight: 10060
url: /fr/net/aspose.pdf.security/validationmode/
---
## Énumération ValidationMode

Spécifie le mode de validation pour les processus de validation de signature PDF.

```csharp
public enum ValidationMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Aucun | `0` | Représente un mode où la validation n'est pas effectuée. |
| VérifierSeulement | `1` | Représente le mode dans lequel la validation est effectuée, mais son résultat n'affecte pas la validation de la signature numérique. Vous pouvez vérifier le résultat de la validation vous-même. |
| Strict | `2` | Représente le mode dans lequel la validation est effectuée et son résultat affecte la validation de la signature numérique. Si le certificat n'a pas pu être vérifié, alors la signature numérique sera considérée comme invalide. Vous pouvez vérifier le résultat de la validation vous-même. |

### Voir Aussi

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)