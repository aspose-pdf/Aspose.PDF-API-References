---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ImagePlacement. Représente les caractéristiques d'une image placée sur une page de document Pdf
type: docs
weight: 5900
url: /fr/net/aspose.pdf/imageplacement/
---
## Classe ImagePlacement

Représente les caractéristiques d'une image placée sur une page de document Pdf.

```csharp
public sealed class ImagePlacement
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | Obtient les paramètres de composition de l'état graphique actif pour l'image placée sur la page. |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | Obtient l'objet de ressource XImage associé. |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | Matrice de transformation actuelle pour cette image. |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | Opérateur utilisé pour afficher l'image. |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | Obtient la page contenant l'image. |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | Obtient le rectangle de l'image. |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | Obtient la résolution de l'image. |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | Obtient l'angle de rotation de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | Supprime l'image de la page. |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | Remplace l'image dans la collection par une autre image. |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |

## Remarques

Lorsqu'une image est placée sur une page, elle peut avoir des dimensions autres que les dimensions physiques définies dans [`Resources`](../resources/). L'objet `ImagePlacement` est destiné à fournir des informations telles que les dimensions, la résolution, etc.

## Exemples

L'exemple démontre comment trouver des images sur la première page du document PDF et obtenir des images sous forme de bitmaps avec des dimensions visibles.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)