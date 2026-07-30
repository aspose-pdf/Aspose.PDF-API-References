---
title: "Classe PdfToXlsOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "classe Aspose.Pdf.Plugins.PdfToXlsOptions. Représente les options du convertisseur PDF vers XLSX pour le plugin XlsConverter."
type: docs
weight: 9300
url: /fr/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions class

Représente les options du convertisseur PDF vers XLSX pour le plugin [`XlsConverter`](../xlsconverter/).

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | Format de sortie. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | Renvoie la collection de données du plugin PdfConverterOptions. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | Définissez true si vous avez besoin d'insérer une colonne vide comme première colonne de la feuille de calcul. La valeur par défaut est false ; cela signifie qu'aucune colonne vide ne sera insérée. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | Définissez true si vous devez réduire le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF sera enregistrée comme une feuille séparée. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | Obtient le nom de l'opération. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | Obtient la collection des cibles ajoutées pour enregistrer les résultats de l'opération. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfConverter. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | Ajoute une nouvelle source de données à la collection de données du plugin PdfToXLSXConverterOptions. |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | Permet de spécifier le format de fichier .xlsx, .xls/xml ou csv. La valeur par défaut est XLSX. |

### Voir aussi

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


