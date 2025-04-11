---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DicomDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format Dicom
type: docs
weight: 3560
url: /fr/net/aspose.pdf.devices/dicomdevice/
---
## Classe DicomDevice

Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Initialise une nouvelle instance de la classe `DicomDevice` avec une résolution par défaut. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe `DicomDevice` avec la taille de page fournie, avec une résolution par défaut (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `DicomDevice`. Résolution pour le fichier image résultant, voir la classe [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe `DicomDevice` avec les dimensions d'image fournies, avec une résolution par défaut (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `DicomDevice` avec la taille de page et la résolution fournies. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe `DicomDevice` avec les dimensions d'image et la résolution fournies. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Convertit la page en Dicom et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

### Voir aussi

* classe [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)