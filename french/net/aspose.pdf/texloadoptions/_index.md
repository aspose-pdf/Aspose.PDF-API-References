---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.TeXLoadOptions. Représente les options pour charger/importer un fichier TeX dans un document PDF
type: docs
weight: 10370
url: /fr/net/aspose.pdf/texloadoptions/
---
## Classe TeXLoadOptions

Représente les options pour charger/importer un fichier TeX dans un document PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Obtient/définit une certaine valeur pour les primitives de date/heure comme l'année, le mois, le jour et l'heure. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit un indicateur pour désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, permet d'exécuter des opérations avec des polices qui sont interdites par une licence de cette police, par exemple, permet d'incorporer une police dans un document PDF même si les règles de licence interdisent l'incorporation pour cette police. Par défaut `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Obtient/définit le répertoire d'entrée TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Obtient/définit le nom du travail. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier que décrit [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Obtient/définit un indicateur qui annule les ligatures dans toutes les polices. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Obtient/définit le répertoire de sortie TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Obtient/définit un indicateur qui permet de rasteriser les formules mathématiques. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Obtient/définit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données tout au long du processus de composition et les stocke dans un fichier auxiliaire, tout cela lors de la première exécution. Et lors de la deuxième exécution, le moteur utilise d'une certaine manière ces données. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Obtient/définit le répertoire d'entrée requis par TeX. L'entrée requise est les fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par exemple, des packages pour lesquels il n'y a pas de support intégré. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Obtient/définit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Obtient/définit l'indicateur indiquant s'il faut sous-ensemble les polices dans le fichier de sortie ou non. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de chargement continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de chargement doit cesser. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Obtient le résultat du chargement et de la compilation TeX - tout s'est-il bien passé ou y avait-il des commentaires/erreurs. |

## Exemples

L'exemple suivant montre comment convertir un fichier TeX en fichier PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Voir aussi

* classe [LoadOptions](../loadoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)