---
title: "Classe PdfAConverter"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Plugins.PdfAConverter. Représente un plugin permettant de gérer la conversion de documents PDF au format PDF/A et la validation de la conformité PDF/A"
type: docs
weight: 9150
url: /fr/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Représente un plugin permettant de gérer la conversion de documents PDF au format PDF/A et la validation de la conformité PDF/A.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Démarre un processus de conversion ou de validation PDF/A avec les options fournies. |

## Exemples

L'exemple montre comment valider la conformité du document PDF au format PDF/A (PDF/A-1a dans ce cas) :

```csharp
// Créez la classe d'options pour configurer le processus de validation
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Ajoutez un ou plusieurs fichiers à valider
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// ajoutez d'autres fichiers si nécessaire

// Créez l'instance du plugin
var plugin = new PdfAConverter();

// Exécutez la validation et obtenez les résultats
var resultContainer = plugin.Process(options);

// Vérifiez la propriété resultContainer.ResultCollection pour les résultats de validation de chaque fichier :
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

L'exemple montre comment convertir le document PDF au format PDF/A (PDF/A-3b dans ce cas) :

```csharp
// Créer la classe d'options pour configurer le processus de conversion
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Ajouter le fichier source
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Ajouter le chemin pour enregistrer le fichier converti
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Créez l'instance du plugin
var plugin = new PdfAConverter();

// Exécuter la conversion
plugin.Process(options);
```

### Voir aussi

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


