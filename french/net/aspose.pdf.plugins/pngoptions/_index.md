---
title: "Classe PngOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Plugins.PngOptions classe. Représente les options du convertisseur Pdf vers Png pour le plugin Png"
type: docs
weight: 9330
url: /fr/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions class

Représente les options du convertisseur Pdf vers Png pour le plugin [`Png`](../png/).

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PngOptions](pngoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | Obtient le mode de conversion d'image. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | Renvoie la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | Renvoie le nom de l'opération. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | Obtient ou définit la valeur de résolution des images résultantes. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | Obtient ou définit une liste de pages pour le processus. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin [`PdfToImage`](../pdftoimage/). |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | Définit une nouvelle source de données d'enregistrement. Ne peut être qu'un . Si vous voulez enregistrer les images dans des flux mémoire, passez null comme paramètre. |

### Voir aussi

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


