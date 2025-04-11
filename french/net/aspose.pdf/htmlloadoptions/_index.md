---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlLoadOptions. Représente les options pour charger/importer un fichier html dans un document pdf
type: docs
weight: 5530
url: /fr/net/aspose.pdf/htmlloadoptions/
---
## Classe HtmlLoadOptions

Représente les options pour charger/importer un fichier html dans un document pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Crée des options de chargement pour convertir html en document pdf avec un chemin de base vide. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Crée des options de chargement pour convertir html en document pdf avec un chemin de base défini. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Le chemin/url de base pour le fichier html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toute restriction de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Obtient ou définit les types de médias possibles utilisés lors du rendu. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Obtient ou définit l'attribut spécifiant l'encodage utilisé pour ce document au moment de l'analyse. Si cet attribut est nul, l'encodage sera déterminé à partir de l'attribut de jeu de caractères du document. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Obtient ou définit l'incorporation des polices dans le document résultant |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Obtient ou définit l'indicateur qui spécifie que les règles @page définies dans css remplaceront les valeurs définies dans PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Obtient ou définit le rendu de tout le document sur une seule page |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Obtient ou définit les informations de page du document |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Obtient ou définit l'option de mise en page. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continue soit Abort. Continue est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abort dans ce cas l'opération de chargement doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Parfois, il est nécessaire d'éviter l'utilisation du chargeur interne de ressources externes (comme des images ou des CSS) et de fournir une méthode personnalisée qui obtiendra les ressources demandées d'ailleurs. Par exemple, lors de l'utilisation d'Aspose.PDF dans le cloud, l'accès direct aux fichiers référencés est impossible : dans ce cas, un code personnalisé placé dans une méthode spéciale doit être utilisé, et un délégué qui fait référence à cette méthode doit être assigné à cet attribut. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Si le chargement de données externes référencées dans HTML nécessite des identifiants, vous pouvez les mettre dans ce paramètre - ils seront utilisés lors du chargement des ressources externes |

## Exemples

L'exemple suivant montre comment convertir un fichier HTML en fichier PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)