---
title: Class SetColorStroke
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColorStroke. Classe représentant l'opérateur SC pour définir la couleur des opérateurs de couleur de contour
type: docs
weight: 7680
url: /fr/net/aspose.pdf.operators/setcolorstroke/
---
## Classe SetColorStroke

Classe représentant l'opérateur SC pour définir la couleur des opérateurs de couleur de contour.

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initialise l'opérateur. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Définit la couleur pour les opérateurs de contour pour les espaces de couleur DeviceGray, CalGray et Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Constructeur qui permet de définir les composants de couleur. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Définit la couleur pour l'opérateur de contour pour les espaces de couleur DeviceRGB, CalRGB et Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Définit la couleur pour l'opérateur de contour pour l'espace de couleur CMYK. |

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Obtient ou définit le composant bleu. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Obtient ou définit le composant cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtient le tableau des composants de couleur. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Obtient ou définit le composant vert. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtient le composant noir de la couleur grise. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de page. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Obtient ou définit le composant noir. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Obtient ou définit le composant magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Obtient ou définit le composant rouge. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Obtient ou définit le composant jaune. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accepte l'objet visiteur pour traiter l'opérateur. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Renvoie la couleur spécifiée par l'opérateur. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |

### Voir aussi

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)