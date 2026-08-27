---
title: "Classe ThumbnailDevice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Devices.ThumbnailDevice. Représente un dispositif d'image qui enregistre les pages de documents pdf en image Thumbnail"
type: docs
weight: 3810
url: /fr/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Représente un dispositif d'image qui enregistre les pages du document PDF en image miniature.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initialise une nouvelle instance de la classe `ThumbnailDevice` avec la taille par défaut de l'image thumbnail (200x200 pixels). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initialise une nouvelle instance de la classe `ThumbnailDevice`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Convertit la page en Bitmap. |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Convertit la page en image thumbnail png et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


