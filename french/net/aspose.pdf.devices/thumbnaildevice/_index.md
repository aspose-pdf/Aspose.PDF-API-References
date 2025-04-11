---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.ThumbnailDevice. Représente un appareil d'image qui enregistre les pages de documents PDF en image miniature
type: docs
weight: 3690
url: /fr/net/aspose.pdf.devices/thumbnaildevice/
---
## Classe ThumbnailDevice

Représente un appareil d'image qui enregistre les pages de documents PDF en image miniature.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Initialise une nouvelle instance de la classe `ThumbnailDevice` avec la taille par défaut de l'image miniature (200x200 pixels). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Initialise une nouvelle instance de la classe `ThumbnailDevice`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Convertit la page en image miniature png et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* classe [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)