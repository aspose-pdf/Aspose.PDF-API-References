---
title: Class XYZExplicitDestination
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XYZExplicitDestination. Représente une destination explicite qui affiche la page avec les coordonnées en haut à gauche positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle.
type: docs
weight: 2730
url: /fr/net/aspose.pdf.annotations/xyzexplicitdestination/
---
## Classe XYZExplicitDestination

Représente une destination explicite qui affiche la page avec les coordonnées (gauche, haut) positionnées dans le coin supérieur gauche de la fenêtre et le contenu de la page agrandi par le facteur de zoom. Une valeur nulle pour l'un des paramètres gauche, haut ou zoom spécifie que la valeur actuelle de ce paramètre doit être conservée inchangée. Une valeur de zoom de 0 a la même signification qu'une valeur nulle.

```csharp
public sealed class XYZExplicitDestination : ExplicitDestination
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_2)(int, double, double, double) | Crée une destination explicite distante. |
| [XYZExplicitDestination](xyzexplicitdestination/#constructor_1)(Page, double, double, double) | Crée une destination explicite locale. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Left](../../aspose.pdf.annotations/xyzexplicitdestination/left/) { get; } | Obtient la coordonnée horizontale gauche du coin supérieur gauche de la fenêtre. |
| [Page](../../aspose.pdf.annotations/explicitdestination/page/) { get; } | Obtient l'objet de la page de destination |
| [PageNumber](../../aspose.pdf.annotations/explicitdestination/pagenumber/) { get; } | Obtient le numéro de la page de destination |
| [Top](../../aspose.pdf.annotations/xyzexplicitdestination/top/) { get; } | Obtient la coordonnée verticale supérieure du coin supérieur gauche de la fenêtre. |
| [Zoom](../../aspose.pdf.annotations/xyzexplicitdestination/zoom/) { get; } | Obtient le facteur de zoom. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [CreateDestination](../../aspose.pdf.annotations/xyzexplicitdestination/createdestination/)(Page, double, double, double, bool) | Crée une destination vers l'emplacement spécifié de la page en tenant compte de la rotation de la page si nécessaire. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner)(Page) | Crée une destination vers la page spécifiée. |
| static [CreateDestinationToUpperLeftCorner](../../aspose.pdf.annotations/xyzexplicitdestination/createdestinationtoupperleftcorner/#createdestinationtoupperleftcorner_1)(Page, double) | Crée une destination vers le coin supérieur gauche de la page spécifiée. |
| override [ToString](../../aspose.pdf.annotations/xyzexplicitdestination/tostring/)() | Convertit l'état de l'objet en valeur de chaîne. Exemple : "1 XYZ 100 200 3". |

## Exemples

```csharp
Document doc = new Document("example.pdf");
XYZExplicitDestination dest = (XYZExplicitDestination)doc.Outlines[1].Destination;
string left = dest.Left;
string top = dest.Top;
string zoom = dest.Zoom;
```

### Voir aussi

* classe [ExplicitDestination](../explicitdestination/)
* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)