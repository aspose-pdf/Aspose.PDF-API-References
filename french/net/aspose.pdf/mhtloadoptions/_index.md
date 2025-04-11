---
title: Class MhtLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.MhtLoadOptions. Représente les options pour le chargement/l'importation d'un fichier .mht dans un document pdf
type: docs
weight: 6970
url: /fr/net/aspose.pdf/mhtloadoptions/
---
## Classe MhtLoadOptions

Représente les options pour le chargement/l'importation d'un fichier .mht dans un document pdf.

```csharp
public sealed class MhtLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MhtLoadOptions](mhtloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation de cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Obtient ou définit les informations de page du document |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

## Exemples

L'exemple suivant montre comment convertir un fichier MHT en fichier PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your MHT File.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialize MhtLoadOptions	
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MHT File.
    Dim mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf")
 
    ' Initialize MhtLoadOptions
    Dim mhtLoadOptions As MhtLoadOptions = New MhtLoadOptions()
 
    Using pdfDocument As Document = New Document(mhtFile, mhtLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```
	
### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)