---
title: Class PdfXmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PdfXmlLoadOptions. Options de chargement pour le format PdfXml
type: docs
weight: 8460
url: /fr/net/aspose.pdf/pdfxmlloadoptions/
---
## Classe PdfXmlLoadOptions

Options de chargement pour le format PdfXml.

```csharp
public class PdfXmlLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfXmlLoadOptions](pdfxmlloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner auquel cas l'opération de chargement doit cesser. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDFXML en fichier PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PDFXML File.
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// Initialize PdfXmlLoadOptions	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDFXML File.
    Dim pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf")
 
    ' Initialize PdfXmlLoadOptions  
    Dim pdfXmlLoadOptions As PdfXmlLoadOptions = New PdfXmlLoadOptions()
 
    Using pdfDocument As Document = New Document(pdfXmlFile, pdfXmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)