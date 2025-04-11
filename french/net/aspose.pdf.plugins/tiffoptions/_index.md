---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.TiffOptions. Représente les options de conversion de Pdf en Tiff pour le plugin Tiff
type: docs
weight: 9420
url: /fr/net/aspose.pdf.plugins/tiffoptions/
---
## Classe TiffOptions

Représente les options de conversion de Pdf en Tiff pour le [`Tiff`](../tiff/) plugin.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TiffOptions](tiffoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | Obtient ou définit une valeur limite de la transformation des couleurs en noir et blanc. Ce paramètre peut être appliqué avec EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle ou ColorDepth.Format1bpp == 1 |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | Obtient ou définit le type de compression. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtient le mode de conversion d'image. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | Obtient ou définit la profondeur de couleur. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Renvoie la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | Renvoie le nom de l'opération. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtient ou définit la valeur de résolution des images résultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtient ou définit une liste de pages pour le processus. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | Obtient et définit un indicateur qui permet de sauvegarder toutes les pages dans un seul tiff multi-pages. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | Obtient ou définit le type de forme. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut ignorer les pages blanches. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Définit une nouvelle source de données de sauvegarde. Peut seulement être un . Si vous souhaitez sauvegarder des images dans des flux mémoire, passez null comme paramètre. |

### Voir aussi

* classe [PdfToImageOptions](../pdftoimageoptions/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)