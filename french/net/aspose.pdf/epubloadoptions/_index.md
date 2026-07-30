---
title: "Classe EpubLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.EpubLoadOptions. Contient les options de chargement/importation d’un fichier EPUB dans un document PDF."
type: docs
weight: 4170
url: /fr/net/aspose.pdf/epubloadoptions/
---
## EpubLoadOptions class

Contient des options pour charger/importer un fichier EPUB dans le document pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Crée les options de chargement par défaut pour convertir un fichier EPUB en document PDF. Taille de page PDF par défaut : A4 300 dpi 2480 × 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Crée des options de chargement avec la taille de page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Obtient ou définit le CSS personnalisé à appliquer lors de l’ouverture du document Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Obtient une référence sur l’objet qui représente les informations de marge. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Obtient ou définit la taille de page de sortie pour l’importation. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Représente le mode d’utilisation de la zone des marges – définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l’utilisation des marges. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENTION ! La fonctionnalité est implémentée mais n’est pas encore exposée dans l’API publique en raison d’un problème bloquant dans la couche OSHARED détecté pour le document d’exemple. Représente le mode d’utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.) ont généralement une mise en page fluide, ce qui permet d’ajuster la taille de page requise. Mais parfois le contenu possède des positions horizontales ou une taille spécifiées qui ne permettent pas de placer le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait (c’est‑à‑dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du PDF de résultat). |

## Exemples

L’exemple suivant montre comment convertir un fichier EPUB en fichier PDF.

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin de votre fichier EPUB.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialiser EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Enregistrer le fichier PDF
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


