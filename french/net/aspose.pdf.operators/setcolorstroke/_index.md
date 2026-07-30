---
title: "Classe SetColorStroke"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Operators.SetColorStroke class. Classe représentant l'opérateur SC qui définit la couleur pour les opérateurs de couleur de tracé"
type: docs
weight: 7820
url: /fr/net/aspose.pdf.operators/setcolorstroke/
---
## SetColorStroke class

Classe représentant l'opérateur SC (définit la couleur pour les opérateurs de couleur de tracé).

```csharp
public class SetColorStroke : BasicSetColorOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetColorStroke](setcolorstroke/#constructor)() | Initialise l'opérateur. |
| [SetColorStroke](setcolorstroke/#constructor_1)(double) | Définir la couleur pour les opérateurs de tracé pour les espaces colorimétriques DeviceGray, CalGray et Indexed. |
| [SetColorStroke](setcolorstroke/#constructor_4)(double[]) | Constructeur qui permet de définir les composants de couleur. |
| [SetColorStroke](setcolorstroke/#constructor_2)(double, double, double) | Définir la couleur pour l'opérateur de tracé pour les espaces colorimétriques DeviceRGB, CalRGB et Lab. |
| [SetColorStroke](setcolorstroke/#constructor_3)(double, double, double, double) | Définir la couleur pour l'opérateur de tracé pour l'espace colorimétrique CMYK. |

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolorstroke/b/) { get; set; } | Obtient ou définit le composant bleu. |
| [C](../../aspose.pdf.operators/setcolorstroke/c/) { get; set; } | Obtient ou définit le composant cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtient le tableau des composants de couleur. |
| [G](../../aspose.pdf.operators/setcolorstroke/g/) { get; set; } | Obtient ou définit le composant vert. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtient le composant noir de la couleur gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |
| [K](../../aspose.pdf.operators/setcolorstroke/k/) { get; set; } | Obtient ou définit le composant noir. |
| [M](../../aspose.pdf.operators/setcolorstroke/m/) { get; set; } | Obtient ou définit le composant magenta. |
| [R](../../aspose.pdf.operators/setcolorstroke/r/) { get; set; } | Obtient ou définit le composant rouge. |
| [Y](../../aspose.pdf.operators/setcolorstroke/y/) { get; set; } | Obtient ou définit le composant jaune. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolorstroke/accept/)(IOperatorSelector) | Accepte un objet visiteur pour traiter l'opérateur. |
| override [getColor](../../aspose.pdf.operators/setcolorstroke/getcolor/)() | Renvoie la couleur spécifiée par l'opérateur. |
| override [ToString](../../aspose.pdf/operator/tostring/)() | Renvoie le texte de l'opérateur et ses paramètres. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet fourni. |

### Voir aussi

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


