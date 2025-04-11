---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgSaveOptions. Options d'enregistrement pour l'exportation au format SVG
type: docs
weight: 10230
url: /fr/net/aspose.pdf/svgsaveoptions/
---
## Classe SvgSaveOptions

Options d'enregistrement pour l'exportation au format SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion du PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Spécifie si la sortie sera créée sous forme d'une archive zip. Veuillez vous référer au commentaire sur les options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages pour un document source multipage, qui s'appliquent également à l'ensemble de fichiers de sortie compressés. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Ce champ peut contenir une stratégie de sauvegarde qui doit être utilisée (si présente) lors de la conversion pour un traitement personnalisé des fichiers d'images externes référencés créés (comme BMP ou JPEG intégrés) intégrés dans le SVG sauvegardé. Cette stratégie doit traiter les ressources et retourner une chaîne qui représente l'URI souhaitée de la ressource sauvegardée dans le SVG généré. Si le traitement pour ce fichier ou cet autre doit être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela signale au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même comme s'il n'y avait pas de code personnalisé externe. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Cette option définit si un répertoire cible sera créé (s'il n'est pas encore présent) avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie demandé lui-même. Dans ce cas, ce répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci-dessous). Sinon, les fichiers de sortie des pages autres que le premier seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais contiendront dans le nom de fichier le suffixe _[2...n], qui est défini par le numéro de page, par exemple si vous définissez le fichier de sortie "C:\AsposeTests\output.svg" et que la sortie contiendra plusieurs fichiers svg de pages, alors les fichiers de pages seront également créés dans le répertoire "C:\AsposeTests\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg', etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images de fond (de pages ou de cellules de tableau) construites à partir de plusieurs images de fond identiques en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images de fond, car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader. Si le document exporté semble contenir de telles limites visibles entre les parties des mêmes images de fond, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Voir aussi

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)