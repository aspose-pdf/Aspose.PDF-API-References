---
title: "Classe ImageDevice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Devices.ImageDevice class. Une classe abstraite pour les dispositifs d'image."
type: docs
weight: 3730
url: /fr/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

Une classe abstraite pour les dispositifs d'image.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | Initialiseur abstrait pour les descendants de `ImageDevice`, définit la résolution à 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution par défaut (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Initialiseur abstrait pour les descendants de `ImageDevice`. Résolution du fichier image résultant, voir la classe [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution par défaut (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Effectue une opération sur la page donnée, par ex. convertit la page en image graphique. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


