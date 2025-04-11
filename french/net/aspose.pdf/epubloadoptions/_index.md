---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.EpubLoadOptions. Contient des options pour charger/importer un fichier EPUB dans un document pdf
type: docs
weight: 4050
url: /fr/net/aspose.pdf/epubloadoptions/
---
## Classe EpubLoadOptions

Contient des options pour charger/importer un fichier EPUB dans un document pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Crée des options de chargement par défaut pour convertir un fichier EPUB en document pdf. Taille de page pdf par défaut - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Crée des options de chargement avec une taille de page spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Obtient ou définit le Css personnalisé à appliquer lors de l'ouverture du document Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Obtient une référence sur un objet qui représente les informations de marge. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Obtient ou définit la taille de page de sortie pour l'importation. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Représente le mode d'utilisation de la zone de marges - définit le traitement des instructions (le cas échéant) du CSS du document importé liées à l'utilisation des marges. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATTENTION! La fonctionnalité est implémentée mais n'a pas encore été mise dans l'API publique en raison d'un problème bloquant dans la couche OSHARED révélé pour un document d'exemple. Représente le mode d'utilisation de la taille de page lors de la conversion. Les formats (comme HTML, EPUB, etc.), ont généralement un design flottant, donc, cela permet d'adapter la taille de page requise. Mais parfois, le contenu a des positions ou des tailles horizontales spécifiées qui ne permettent pas de mettre le contenu dans la taille de page requise. Dans ce cas, nous pouvons définir ce qui doit être fait dans ce cas (c'est-à-dire lorsque la taille du contenu ne correspond pas à la taille de page initiale requise du document PDF résultant). |

## Exemples

L'exemple suivant montre comment convertir un fichier EPUB en fichier PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
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

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)