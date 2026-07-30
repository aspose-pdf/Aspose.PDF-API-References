---
title: "Classe ImagePlacement"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.ImagePlacement classe. Représente les caractéristiques d'une image placée sur la Page d'un Document Pdf"
type: docs
weight: 6030
url: /fr/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Représente les caractéristiques d'une image placée sur une page de document Pdf.

```csharp
public sealed class ImagePlacement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Obtient les paramètres de composition de l'état graphique actif pour l'image placée sur la Page. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Obtient l'objet de ressource XImage associé. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matrice de transformation actuelle pour cette image. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Opérateur utilisé pour afficher l'image. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Obtient la Page contenant l'image. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Obtient le Rectangle de l'image. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Obtient la résolution de l'image. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Obtient l'angle de rotation de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Supprimer l'image de la Page. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Remplacez l'image dans la collection par une autre image. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |

## Remarques

Lorsqu'une image est placée sur une page, elle peut avoir des dimensions différentes des dimensions physiques définies dans [`Resources`](../resources/). L'objet `ImagePlacement` est destiné à fournir ces informations, comme les dimensions, la résolution, etc.

## Exemples

L'exemple montre comment trouver les images sur la première page du document PDF et obtenir les images sous forme de bitmap avec leurs dimensions visibles.

```csharp
// Ouvrir le document
Document doc = new Document(@"D:\Tests\input.pdf");

// Créez un objet ImagePlacementAbsorber pour effectuer la recherche de placement d'image
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accepter l'absorbeur pour la première page
doc.Pages[1].Accept(abs);

// Récupérer les images avec leurs dimensions visibles
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Récupérer l'image depuis les ressources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Créer un nouveau bitmap avec les dimensions réelles
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


