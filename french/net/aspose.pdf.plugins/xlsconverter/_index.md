---
title: "Classe XlsConverter"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.XlsConverter. Représente le plugin XlsConverter"
type: docs
weight: 9600
url: /fr/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

Représente le plugin `XlsConverter`.

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XlsConverter](xlsconverter/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | Implémentation de IDisposable. |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | Démarre le traitement PdfToExcel avec les paramètres spécifiés. |

## Exemples

L'exemple montre comment convertir un PDF en document XLSX.

```csharp
// créer le convertisseur XlsConverter
var converter = new XlsConverter();
// créer PdfToXLSOptions
var opt = new PdfToXLSOptions();
// ajouter le chemin du fichier d'entrée
opt.AddInput(new FileDataSource(inputPath));
// définir le chemin du fichier de sortie
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


