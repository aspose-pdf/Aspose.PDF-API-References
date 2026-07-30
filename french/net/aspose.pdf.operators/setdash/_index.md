---
title: "Classe SetDash"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Operators.SetDash classe. Classe représentant l'opérateur d définissant le motif de tirets de ligne"
type: docs
weight: 7830
url: /fr/net/aspose.pdf.operators/setdash/
---
## SetDash class

Classe représentant l'opérateur d (définit le motif de tirets de ligne).

```csharp
public class SetDash : Operator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetDash](setdash/)(int[], int) | Crée l'opérateur de définition du motif de tirets. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |
| [Pattern](../../aspose.pdf.operators/setdash/pattern/) { get; set; } | Motif de tirets. Les éléments du tableau doivent être des nombres qui spécifient les longueurs des tirets et des espaces alternés. Dans le cas d'un tableau à un seul élément, les longueurs du tiret et de l'espace sont égales. |
| [Phase](../../aspose.pdf.operators/setdash/phase/) { get; set; } | Phase de tirets. Avant de commencer à tracer un chemin, le tableau de tirets doit être parcouru en boucle, en additionnant les longueurs des tirets et des espaces. Lorsque la longueur accumulée égale la valeur spécifiée par la phase de tirets, le traçage du chemin commence, et le tableau de tirets est utilisé de façon cyclique à partir de ce point. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setdash/accept/)(IOperatorSelector) | Accepte un objet visiteur pour traiter l'opérateur. |
| override [ToString](../../aspose.pdf.operators/setdash/tostring/)() | Obtient la représentation sous forme de chaîne de l'opérateur. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet fourni. |

### Voir aussi

* class [Operator](../../aspose.pdf/operator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


