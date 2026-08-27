---
title: "Classe TextShowOperator"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Operators.TextShowOperator classe. Classe de base abstraite pour tous les opérateurs utilisés pour afficher du texte Tj TJ etc"
type: docs
weight: 8060
url: /fr/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

Classe de base abstraite pour tous les opérateurs utilisés pour sortir le texte (Tj, TJ, etc).

```csharp
public class TextShowOperator : TextOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | Initialise TextShowOperator. |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | Initialise TextShowOperator qui permet de passer TextProperties. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | Obtient le texte que l'opérateur produit sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepte un objet visiteur pour traiter l'opérateur. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet fourni. |

### Voir aussi

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


