---
title: "Classe ImagePlacementAbsorber"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.ImagePlacementAbsorber. Représente un objet absorbeur d'objets de placement d'image. Effectue la recherche des utilisations d'images et fournit l'accès aux résultats de recherche via la collection ImagePlacements."
type: docs
weight: 6040
url: /fr/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

Représente un objet absorbeur d'objets de placement d'image. Effectue la recherche des utilisations d'images et fournit l'accès aux résultats de recherche via la collection [`ImagePlacements`](./imageplacements/).

```csharp
public sealed class ImagePlacementAbsorber
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Obtient la collection des occurrences de placement d'image présentées avec les objets [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Obtient/definit le mode lecture seule pour la collection des opérations d'analyse. Cela peut aider à éviter les exceptions de mémoire insuffisante. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Effectue une recherche sur le document spécifié. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Effectue une recherche sur la page spécifiée. |

## Remarques

L'objet `ImagePlacementAbsorber` est essentiellement utilisé dans le scénario de recherche d'images. Lorsque la recherche est terminée, les occurrences sont représentées par des objets [`ImagePlacement`](../imageplacement/) que la collection [`ImagePlacements`](./imageplacements/) contient. L'objet [`ImagePlacement`](../imageplacement/) fournit l'accès aux propriétés de placement de l'image : dimensions, résolution, etc. La rotation positive de l'image est dans le sens antihoraire, pour la page, elle est dans le sens horaire. Ici, nous devons représenter l'angle de rotation de l'image, donc nous soustrayons l'angle de la page de l'angle de l'image.

## Exemples

L'exemple montre comment trouver des images sur la première page du document PDF et obtenir les propriétés de placement de l'image.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créez un objet ImagePlacementAbsorber pour effectuer la recherche de placement d'image
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(abs);

// Affichez les propriétés de placement d'image pour tous les placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


