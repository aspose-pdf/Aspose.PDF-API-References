---
title: "Classe TeXLoadOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.TeXLoadOptions. Représente les options de chargement/importation d'un fichier TeX dans un document PDF"
type: docs
weight: 10550
url: /fr/net/aspose.pdf/texloadoptions/
---
## TeXLoadOptions class

Représente les options de chargement/importation d'un fichier TeX dans un document PDF.

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
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Obtient/définit une certaine valeur pour les primitives date/heure comme l'année, le mois, le jour et l'heure. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtient ou définit le drapeau permettant de désactiver toutes les restrictions de licence pour toutes les polices lors du chargement du fichier. Lorsque `true`, autorise l’exécution d’opérations avec une police qui sont interdites par la licence de cette police, par exemple autorise l’intégration d’une police dans un document PDF même si les règles de licence désactivent l’intégration pour cette police. Par défaut `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Obtient/définit le répertoire d'entrée TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Obtient/définit le nom du travail. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Représente le format de fichier décrit par [`LoadOptions`](../loadoptions/). |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Obtient/définit un indicateur qui annule les ligatures dans toutes les polices. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Obtient/définit le répertoire de sortie TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Obtient/définit un indicateur qui permet de rasteriser les formules mathématiques. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Obtient/définit l'indicateur indiquant s'il est nécessaire d'exécuter le travail TeX deux fois dans le cas, par exemple, où il y a des références dans le(s) fichier(s) TeX d'entrée. En général, ce comportement est utile lorsque le moteur collecte certaines données pendant le processus de composition et les stocke dans un fichier auxiliaire lors de la première exécution. Et lors de la deuxième exécution, le moteur utilise d'une manière ou d'une autre ces données. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Obtient/définit le répertoire d'entrée requis par TeX. L'entrée requise est constituée des fichiers qui sont d'une manière ou d'une autre inclus dans le fichier .tex principal, par ex., les packages pour lesquels il n'existe aucun support intégré. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Obtient/définit l'indicateur indiquant s'il faut afficher la sortie du terminal sur la console. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Obtient/définit l'indicateur indiquant s'il faut sous-ensembler les polices dans le fichier de sortie ou non. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Fonction de rappel pour gérer les avertissements générés. Le WarningHandler renvoie un élément de l’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération de chargement se poursuit, cependant l’utilisateur peut également renvoyer Abort, auquel cas l’opération de chargement doit s’arrêter. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Obtient le résultat du chargement et de la compilation TeX - tout s'est-il déroulé sans problème ou y a-t-il eu des commentaires/erreurs. |

## Exemples

L'exemple suivant montre comment convertir un fichier TeX en fichier PDF

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier TeX.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// Le chemin du fichier PDF de sortie.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialiser TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Enregistrer le fichier PDF
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

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


