---
title: Class FitRExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FitRExplicitDestination. Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour s'adapter au rectangle spécifié par les coordonnées gauche, bas, droite et haut entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible.
type: docs
weight: 1780
url: /fr/net/aspose.pdf.annotations/fitrexplicitdestination/
---
## Classe FitRExplicitDestination

Représente une destination explicite qui affiche la page avec son contenu agrandi juste assez pour s'adapter au rectangle spécifié par les coordonnées gauche, bas, droite et haut entièrement dans la fenêtre à la fois horizontalement et verticalement. Si les facteurs de grossissement horizontal et vertical requis sont différents, utilisez le plus petit des deux, centrant le rectangle dans la fenêtre dans l'autre dimension. Une valeur nulle pour l'un des paramètres peut entraîner un comportement imprévisible.

```csharp
public sealed class FitRExplicitDestination : ExplicitDestination
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_2)(int, double, double, double, double) | Crée une destination explicite distante. |
| [FitRExplicitDestination](fitrexplicitdestination/#constructor_1)(Page, double, double, double, double) | Crée une destination explicite locale. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bottom](../../aspose.pdf.annotations/fitrexplicitdestination/bottom/) { get; } | Obtient la coordonnée verticale inférieure du rectangle visible. |
| [Left](../../aspose.pdf.annotations/fitrexplicitdestination/left/) { get; } | Obtient la coordonnée horizontale gauche du rectangle visible. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtient l'objet de la page de destination |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtient le numéro de la page de destination |
| [Right](../../aspose.pdf.annotations/fitrexplicitdestination/right/) { get; } | Obtient la coordonnée horizontale droite du rectangle visible. |
| [Top](../../aspose.pdf.annotations/fitrexplicitdestination/top/) { get; } | Obtient la coordonnée verticale supérieure du rectangle visible. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.annotations/fitrexplicitdestination/tostring/)() | Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 FitR 100 200 300 400". |

### Voir aussi

* classe [ExplicitDestination](../explicitdestination/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)