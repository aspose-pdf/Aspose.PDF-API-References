---
title: "Classe PdfToImageOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Plugins.PdfToImageOptions classe. Représente les options pour le plugin PdfToImage"
type: docs
weight: 9280
url: /fr/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

Représente les options pour le plugin [`PdfToImage`](../pdftoimage/).

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtient le mode de conversion d'image. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Renvoie la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | Renvoie le nom de l'opération. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtient ou définit la valeur de résolution des images résultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtient ou définit une liste de pages pour le processus. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Définit une nouvelle source de données d'enregistrement. Ne peut être qu'un . Si vous voulez enregistrer les images dans des flux mémoire, passez null comme paramètre. |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | Définit différents modes qui peuvent être utilisés lors de la conversion d'un document PDF en image Jpeg. Voir la classe [`JpegOptions`](../jpegoptions/). |

## Remarques

La classe PdfImageOptions contient des fonctions de base pour ajouter des données (fichiers, flux) représentant les documents PDF d'entrée.

### Voir aussi

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


