---
title: "Classe PdfExtractorOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.PdfExtractorOptions. Représente les options pour les plugins TextExtractor et ImageExtractor."
type: docs
weight: 9220
url: /fr/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions class

Représente les options pour les plugins TextExtractor et ImageExtractor.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Renvoie la collection de données du plugin PdfExtractor. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | Renvoie le nom de l'opération |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfExtractor. |

## Remarques

Le `PdfExtractorOptions` contient des fonctions de base pour ajouter des données (fichiers, flux) représentant des documents PDF d'entrée. Veuillez créer [`TextExtractorOptions`](../textextractoroptions/) ou ImageExtractorOptions à la place.

### Voir aussi

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


