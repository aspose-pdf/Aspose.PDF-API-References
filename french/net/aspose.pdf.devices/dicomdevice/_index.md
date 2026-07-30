---
title: "Classe DicomDevice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Devices.DicomDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format Dicom."
type: docs
weight: 3680
url: /fr/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

Représente un dispositif d'image qui permet d'enregistrer les pages du document PDF au format DICOM.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initialise une nouvelle instance de la classe `DicomDevice` avec la résolution par défaut. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe `DicomDevice` avec la taille de page fournie, avec la résolution par défaut (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `DicomDevice`. Résolution du fichier image résultant, voir la classe [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe `DicomDevice` avec les dimensions d'image fournies, avec la résolution par défaut (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `DicomDevice` avec la taille de page fournie et la résolution. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe `DicomDevice` avec les dimensions d'image fournies et la résolution. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Convertit la page en Dicom et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


