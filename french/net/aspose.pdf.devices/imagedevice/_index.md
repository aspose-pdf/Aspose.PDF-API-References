---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.ImageDevice. Une classe abstraite pour les dispositifs d'image
type: docs
weight: 3610
url: /fr/net/aspose.pdf.devices/imagedevice/
---
## Classe ImageDevice

Une classe abstraite pour les dispositifs d'image.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Initialisateur abstrait pour les descendants de `ImageDevice`, définit la résolution à 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et une résolution par défaut (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Initialisateur abstrait pour les descendants de `ImageDevice`. Résolution pour le fichier image résultant, voir la classe [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et une résolution par défaut (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Effectue une opération sur la page donnée, par exemple, convertit la page en image graphique. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* classe [PageDevice](../pagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)