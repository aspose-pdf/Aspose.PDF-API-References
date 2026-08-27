---
title: "Classe PdfXmlLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PdfXmlLoadOptions. Options de chargement pour le format PdfXml"
type: docs
weight: 8590
url: /fr/net/aspose.pdf/pdfxmlloadoptions/
---
## PdfXmlLoadOptions class

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDFXML en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDFXML.
	string pdfXmlFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdfxml");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "PDFXML-to-PDF.pdf");

	// Initialiser PdfXmlLoadOptions	
	PdfXmlLoadOptions pdfXmlLoadOptions = new PdfXmlLoadOptions();
		
	using (Document pdfDocument = new Document(pdfXmlFile, pdfXmlLoadOptions))
	{
	 
		// Enregistrer le fichier PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


