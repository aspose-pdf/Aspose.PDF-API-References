---
title: TiffDevice
second_title: Référence de l'API Aspose.PDF pour .NET
description: Cette classe permet denregistrer un document pdf page par page dans une seule image tiff.
type: docs
weight: 1800
url: /fr/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

Cette classe permet d'enregistrer un document pdf page par page dans une seule image tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [TiffDevice](tiffdevice#constructor)() | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe avec les paramètres par défaut. |
| [TiffDevice](tiffdevice#constructor_6)(PageSize) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_1)(Resolution) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_4)(TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_12)(int, int) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_7)(PageSize, Resolution) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_10)(PageSize, TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_2)(Resolution, TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_5)(TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_13)(int, int, Resolution) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_16)(int, int, TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_8)(PageSize, Resolution, TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_14)(int, int, Resolution, TiffSettings) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |
| [TiffDevice](tiffdevice#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Initialise une nouvelle instance du[`TiffDevice`](../tiffdevice) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/tiffdevice/height) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution) { get; } | Obtient la résolution de l'image. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings) { get; } | Obtient les paramètres de mappage du pdf dans l'image tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | La description |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/documentdevice/binarizebradley)(Stream, Stream, double) | Effectuez la binarisation Bradley pour le flux d'entrée. |
| [Process](../../aspose.pdf.devices/documentdevice/process)(Document, Stream) | Traite l'intégralité du document et enregistre les résultats dans le flux. |
| [Process](../../aspose.pdf.devices/documentdevice/process)(Document, string) | Traite l'intégralité du document et enregistre les résultats dans un fichier. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process#process)(Document, int, int, Stream) | Convertit certaines pages du document en tiff et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/documentdevice/process)(Document, int, int, string) | Traite certaines pages du document et enregistre les résultats dans un fichier. |

### Voir également

* class [DocumentDevice](../documentdevice)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
