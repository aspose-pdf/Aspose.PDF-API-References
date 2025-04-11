---
title: Class SetDash
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetDash. Classe représentant l'opérateur d définition du motif de ligne en tirets
type: docs
weight: 7690
url: /fr/net/aspose.pdf.operators/setdash/
---
## Classe SetDash

Classe représentant l'opérateur d (définir le motif de ligne en tirets).

```csharp
public class SetDash : Operator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Crée un opérateur de motif de tirets. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets alternés et des espaces. Dans le cas d'un tableau à un élément, les longueurs des tirets et des espaces sont égales. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Phase des tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être cyclé, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée est égale à la valeur spécifiée par la phase des tirets, le traçage du chemin doit commencer, et le tableau de tirets doit être utilisé de manière cyclique à partir de ce point. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accepte l'objet visiteur pour traiter l'opérateur. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Obtient la représentation sous forme de chaîne de l'opérateur. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |

### Voir aussi

* classe [Operator](../../aspose.pdf/operator/)
* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)