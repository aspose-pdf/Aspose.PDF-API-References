---
title: "Classe MdLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.MdLoadOptions. Options de chargement pour la conversion du format Markdown"
type: docs
weight: 7080
url: /fr/net/aspose.pdf/mdloadoptions/
---
## MdLoadOptions class

Options de chargement pour la conversion du format Markdown.

```csharp
public class MdLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MdLoadOptions](mdloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [IsPriorityCssPageRule](../../aspose.pdf/mdloadoptions/isprioritycsspagerule/) { get; set; } | Obtient ou définit l’indicateur qui spécifie que les règles @page définies dans le css remplaceront les valeurs définies dans PageInfo. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/mdloadoptions/pageinfo/) { get; set; } | Obtient ou définit les informations de page du document |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Exemples

L'exemple suivant montre comment convertir un fichier MD en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier MD.
	string mdFile = Path.Combine(dataDir, "MD-to-PDF.md");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf");

	// Initialiser MdLoadOptions	
	MdLoadOptions mdLoadOptions = new MdLoadOptions();
		
	using (Document pdfDocument = new Document(mdFile, mdLoadOptions))
	{
	 
		// Enregistrer le fichier PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your MD File.
    Dim mdFile = Path.Combine(dataDir, "MD-to-PDF.md")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "MD-to-PDF.pdf")
 
    ' Initialize MdLoadOptions  
    Dim mdLoadOptions As MdLoadOptions = New MdLoadOptions()
 
    Using pdfDocument As Document = New Document(mdFile, mdLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


