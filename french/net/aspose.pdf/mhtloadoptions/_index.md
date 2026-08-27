---
title: "Classe MhtLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.MhtLoadOptions. Représente les options de chargement/importation d'un fichier .mht dans un document PDF"
type: docs
weight: 7110
url: /fr/net/aspose.pdf/mhtloadoptions/
---
## MhtLoadOptions class

Représente les options de chargement/importation d'un fichier .mht dans un document pdf.

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
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/mhtloadoptions/pageinfo/) { get; } | Obtient ou définit les informations de page du document |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Exemples

L'exemple suivant montre comment convertir un fichier MHT en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier MHT.
	string mhtFile = Path.Combine(dataDir, "MHT-to-PDF.mht");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "MHT-to-PDF.pdf");

	// Initialiser MhtLoadOptions\t
	MhtLoadOptions mhtLoadOptions = new MhtLoadOptions();
		
	using (Document pdfDocument = new Document(mhtFile, mhtLoadOptions))
	{
	 
		// Enregistrer le fichier PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


