---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.JpegOptions. Représente les options de convertisseur Pdf en Jpeg pour le plugin Jpeg
type: docs
weight: 8920
url: /fr/net/aspose.pdf.plugins/jpegoptions/
---
## Classe JpegOptions

Représente les options de convertisseur Pdf en Jpeg pour le plugin [`Jpeg`](../jpeg/).

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JpegOptions](jpegoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtient le mode de conversion d'image. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Renvoie la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | Renvoie le nom de l'opération. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtient ou définit la valeur de résolution des images résultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtient ou définit une liste de pages pour le processus. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Obtient et définit la qualité Jpeg |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Définit une nouvelle source de données de sauvegarde. Peut seulement être un . Si vous souhaitez sauvegarder des images dans des flux mémoire, passez null comme paramètre. |

### Voir aussi

* classe [PdfToImageOptions](../pdftoimageoptions/)
* espace de noms [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)