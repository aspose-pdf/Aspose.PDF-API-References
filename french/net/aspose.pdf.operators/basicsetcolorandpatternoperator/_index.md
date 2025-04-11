---
title: Class BasicSetColorAndPatternOperator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.BasicSetColorAndPatternOperator. Opérateur de base pour tous les opérateurs de définition de couleur
type: docs
weight: 7150
url: /fr/net/aspose.pdf.operators/basicsetcolorandpatternoperator/
---
## Classe BasicSetColorAndPatternOperator

Opérateur de base pour tous les opérateurs de définition de couleur.

```csharp
public abstract class BasicSetColorAndPatternOperator : BasicSetColorOperator
```

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/basicsetcoloroperator/b/) { get; } | Obtient le composant rouge de la couleur |
| [C](../../aspose.pdf.operators/basicsetcoloroperator/c/) { get; } | Obtient le composant cyan de la couleur CMJN. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtient le tableau des composants de couleur. |
| [G](../../aspose.pdf.operators/basicsetcoloroperator/g/) { get; } | Obtient le composant vert de la couleur |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtient le composant noir de la couleur grise. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de page. |
| [K](../../aspose.pdf.operators/basicsetcoloroperator/k/) { get; } | Obtient le composant noir de la couleur CMJN. |
| [M](../../aspose.pdf.operators/basicsetcoloroperator/m/) { get; } | Obtient le composant magenta de la couleur CMJN. |
| [PatternName](../../aspose.pdf.operators/basicsetcolorandpatternoperator/patternname/) { get; } | Obtient le nom du motif. |
| [R](../../aspose.pdf.operators/basicsetcoloroperator/r/) { get; } | Obtient le composant rouge de la couleur |
| [Y](../../aspose.pdf.operators/basicsetcoloroperator/y/) { get; } | Obtient le composant jaune de la couleur CMJN. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | Accepte le visiteur IOperatorSelector qui fournit le traitement des opérateurs. |
| abstract [getColor](../../aspose.pdf.operators/setcoloroperator/getcolor/)() | Renvoie la couleur spécifiée par l'opérateur. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et de ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |

### Voir aussi

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)