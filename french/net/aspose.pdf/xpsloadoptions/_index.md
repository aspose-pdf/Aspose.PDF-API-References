---
title: "Classe XpsLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.XpsLoadOptions. Représente les options pour charger/importer un fichier xps dans un document pdf"
type: docs
weight: 11700
url: /fr/net/aspose.pdf/xpsloadoptions/
---
## XpsLoadOptions class

Représente les options de chargement/importation du fichier xps dans le document pdf.

```csharp
public sealed class XpsLoadOptions : LoadOptions, IPipelineOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XpsLoadOptions](xpsloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpsloadoptions/batchsize/) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Exemples

L'exemple suivant montre comment convertir un fichier XPS en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier XPS.
	string xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf");

	// Initialiser XpsLoadOptions	
	XpsLoadOptions xpsLoadOptions = new XpsLoadOptions();
		
	using (Document pdfDocument = new Document(xpsFile, xpsLoadOptions)){
	 
		// Enregistrer le fichier PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XPS File.
    Dim xpsFile = Path.Combine(dataDir, "XPS-to-PDF.xps")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XPS-to-PDF.pdf")
 
    ' Initialize XpsLoadOptions
    Dim xpsLoadOptions As XpsLoadOptions = New XpsLoadOptions()
 
    Using pdfDocument As Document = New Document(xpsFile, xpsLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* class [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


