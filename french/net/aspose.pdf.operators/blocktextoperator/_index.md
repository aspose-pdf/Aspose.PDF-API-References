---
title: Class BlockTextOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BlockTextOperator. Classe de base abstraite pour les opérateurs de bloc de texte c'est-à-dire les opérateurs de début et de fin de texte BT/ET
type: docs
weight: 7170
url: /fr/net/aspose.pdf.operators/blocktextoperator/
---
## Classe BlockTextOperator

Classe de base abstraite pour les opérateurs de bloc de texte c'est-à-dire les opérateurs de début et de fin de texte (BT/ET)

```csharp
public class BlockTextOperator : TextOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BlockTextOperator](blocktextoperator/#constructor)() | Initialise l'opérateur. |
| [BlockTextOperator](blocktextoperator/#constructor_1)(TextProperties) | Initialise BlockTextOperator qui accepte TextProperties. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | Accepte l'objet visiteur pour traiter l'opérateur. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |

### Voir aussi

* classe [TextOperator](../textoperator/)
* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)