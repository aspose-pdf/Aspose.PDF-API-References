---
title: "Classe SetColor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Operators.SetColor classe. Représente la classe pour l'opérateur sc définissant la couleur pour les opérations de non-tracé"
type: docs
weight: 7770
url: /fr/net/aspose.pdf.operators/setcolor/
---
## SetColor class

Représente la classe pour l'opérateur sc (définit la couleur pour les opérations sans tracé).

```csharp
public class SetColor : BasicSetColorOperator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SetColor](setcolor/#constructor)() | Initialise l'opérateur. |
| [SetColor](setcolor/#constructor_1)(double) | Définir la couleur pour les opérateurs de tracé pour les espaces colorimétriques DeviceGray, CalGray et Indexed. |
| [SetColor](setcolor/#constructor_4)(double[]) | Constructeur qui permet de spécifier les composants de couleur. |
| [SetColor](setcolor/#constructor_2)(double, double, double) | Définir la couleur pour l'opérateur de tracé pour les espaces colorimétriques DeviceRGB, CalRGB et Lab. |
| [SetColor](setcolor/#constructor_3)(double, double, double, double) | Définit la couleur pour l'opérateur de non-tracé dans l'espace colorimétrique CMYK |

## Propriétés

| Nom | Description |
| --- | --- |
| [B](../../aspose.pdf.operators/setcolor/b/) { get; set; } | Obtient ou définit le composant bleu. |
| [C](../../aspose.pdf.operators/setcolor/c/) { get; set; } | Obtient ou définit le composant cyan. |
| virtual [Color](../../aspose.pdf.operators/basicsetcoloroperator/color/) { get; } | Obtient le tableau des composants de couleur. |
| [G](../../aspose.pdf.operators/setcolor/g/) { get; set; } | Obtient ou définit le composant vert. |
| [Gray](../../aspose.pdf.operators/basicsetcoloroperator/gray/) { get; } | Obtient le composant noir de la couleur gris. |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Index de l'opérateur dans la liste des opérateurs de la page. |
| [K](../../aspose.pdf.operators/setcolor/k/) { get; set; } | Obtient ou définit le composant noir. |
| [M](../../aspose.pdf.operators/setcolor/m/) { get; set; } | Obtient ou définit le composant magenta. |
| [R](../../aspose.pdf.operators/setcolor/r/) { get; set; } | Obtient ou définit le composant rouge. |
| [Y](../../aspose.pdf.operators/setcolor/y/) { get; set; } | Obtient ou définit le composant jaune. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/setcolor/accept/)(IOperatorSelector) | Accepte un objet visiteur pour traiter l'opérateur. |
| override [getColor](../../aspose.pdf.operators/setcolor/getcolor/)() | Renvoie la couleur spécifiée par l'opérateur. |
| override [ToString](../../aspose.pdf.operators/setcolor/tostring/)() | Renvoie la représentation sous forme de chaîne de la couleur. |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | Compare cette instance avec l'objet fourni. |

### Voir aussi

* class [BasicSetColorOperator](../basicsetcoloroperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


