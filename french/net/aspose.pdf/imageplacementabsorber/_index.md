---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacementAbsorber. Représente un objet absorbeur d'objets de placement d'image. Effectue une recherche des utilisations d'images et fournit un accès aux résultats de recherche via la collection [`ImagePlacements`](./imageplacements/).
type: docs
weight: 5910
url: /fr/net/aspose.pdf/imageplacementabsorber/
---
## Classe ImagePlacementAbsorber

Représente un objet absorbeur d'objets de placement d'image. Effectue une recherche des utilisations d'images et fournit un accès aux résultats de recherche via la collection [`ImagePlacements`](./imageplacements/).

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
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | Obtient la collection des occurrences de placement d'image qui sont présentées avec des objets [`ImagePlacement`](../imageplacement/). |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | Obtient/définit le mode lecture seule pour la collection d'opérations d'analyse. Cela peut aider à éviter les exceptions de mémoire insuffisante. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | Effectue une recherche sur le document spécifié. |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | Effectue une recherche sur la page spécifiée. |

## Remarques

L'objet `ImagePlacementAbsorber` est essentiellement utilisé dans le scénario de recherche d'images. Lorsque la recherche est terminée, les occurrences sont représentées par des objets [`ImagePlacement`](../imageplacement/) que la collection [`ImagePlacements`](./imageplacements/) contient. L'objet [`ImagePlacement`](../imageplacement/) fournit un accès aux propriétés de placement d'image : dimensions, résolution, etc. La rotation positive de l'image est antihoraire, pour la page, elle est horaire. Ici, nous devons représenter l'angle de rotation de l'image, donc nous déduisons l'angle de la page de l'angle de l'image.

## Exemples

L'exemple démontre comment trouver des images sur la première page du document PDF et obtenir les propriétés de placement d'image.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
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

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)