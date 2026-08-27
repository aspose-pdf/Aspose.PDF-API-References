---
title: "Classe HtmlLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.HtmlLoadOptions classe. Représente les options de chargement/importation d’un fichier html dans un document pdf"
type: docs
weight: 5660
url: /fr/net/aspose.pdf/htmlloadoptions/
---
## HtmlLoadOptions class

Représente les options de chargement/importation du fichier html dans le document pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Crée des options de chargement pour convertir du html en document pdf avec un chemin de base vide. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Crée des options de chargement pour convertir du html en document pdf avec un chemin de base défini. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | Le chemin de base/URL du fichier html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Obtient ou définit les types de médias possibles utilisés lors du rendu. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Obtient ou définit l’attribut spécifiant l’encodage utilisé pour ce document lors de l’analyse. Si cet attribut est nul, l’encodage sera déterminé à partir de l’attribut de jeu de caractères du document. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Obtient ou définit l’incorporation des polices dans le document résultant |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Obtient ou définit l’indicateur qui spécifie que les règles @page définies dans le css remplaceront les valeurs définies dans PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Obtient ou définit le rendu de tout le document sur une seule page |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Obtient ou définit les informations de page du document |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Obtient ou définit l'option de mise en page. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Il arrive parfois qu’il soit nécessaire d’éviter l’utilisation du chargeur interne des ressources externes (comme les images ou les CSS) et de fournir une méthode personnalisée qui récupérera les ressources demandées depuis un emplacement. Par exemple, lors de l’utilisation d’Aspose.PDF dans le cloud, l’accès direct aux fichiers référencés est impossible : dans ce cas, du code personnalisé placé dans une méthode spéciale doit être utilisé, et le délégué qui fait référence à cette méthode doit être assigné à cet attribut. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Si le chargement de données externes référencées dans le HTML nécessite des informations d’identification, vous pouvez les placer dans ce paramètre – elles seront utilisées lors du chargement des ressources externes. |

## Exemples

L’exemple suivant montre comment convertir un fichier HTML en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier HTML.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialiser HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Enregistrer le fichier PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


