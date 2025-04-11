---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operator. Classe abstraite représentant un opérateur
type: docs
weight: 7070
url: /fr/net/aspose.pdf/operator/
---
## Classe Operator

Classe abstraite représentant un opérateur.

```csharp
public abstract class Operator
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepte le visiteur IOperatorSelector qui fournit le traitement des opérateurs. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | Détermine si l'opérateur est celui qui est responsable de la sortie de texte (Tj, TJ, etc) |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)