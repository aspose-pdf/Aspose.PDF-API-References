---
title: Class SetColor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Operators.SetColor. Représente la classe pour l'opérateur sc qui définit la couleur pour les opérations non traçantes
type: docs
weight: 7630
url: /fr/net/aspose.pdf.operators/setcolor/
---
## Classe SetColor

Représente la classe pour l'opérateur sc (définir la couleur pour les opérations non traçantes).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initialise l'opérateur. |
| [SetColor](setcolor/#constructor_1)(double) | Définit la couleur pour les opérateurs de traçage pour les espaces de couleur DeviceGray, CalGray et Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Constructeur qui permet de spécifier les composants de couleur. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Définit la couleur pour l'opérateur de traçage pour les espaces de couleur DeviceRGB, CalRGB et Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Définit la couleur pour l'opérateur non traçant pour l'espace de couleur CMYK. |

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Obtient ou définit le composant bleu. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Obtient ou définit le composant cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtient le tableau des composants de couleur. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Obtient ou définit le composant vert. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtient le composant noir de la couleur grise. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de page. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Obtient ou définit le composant noir. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Obtient ou définit le composant magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Obtient ou définit le composant rouge. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Obtient ou définit le composant jaune. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accepte l'objet visiteur pour traiter l'opérateur. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Retourne la couleur spécifiée par l'opérateur. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Retourne la représentation sous forme de chaîne de la couleur. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet donné. |

### Voir aussi

* classe [BasicSetColorOperator](../basicsetcoloroperator/)
* espace de noms [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)