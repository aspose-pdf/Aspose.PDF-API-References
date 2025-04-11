---
title: Class PptxSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PptxSaveOptions. Options d'enregistrement pour l'exportation au format SVG
type: docs
weight: 9480
url: /fr/net/aspose.pdf/pptxsaveoptions/
---
## Classe PptxSaveOptions

Options d'enregistrement pour l'exportation au format SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion du PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple, il peut être utilisé pour afficher une barre de progression ou des messages sur le nombre actuel de pages traitées, un exemple de code du gestionnaire qui affiche la progression sur la console est : |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Obtient ou définit la résolution de l'image (dpi). Par défaut, c'est 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Active ou désactive la reconnaissance des colonnes de texte |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Si défini sur vrai, alors les images sont séparées de tous les autres graphiques |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Si défini sur vrai, alors tout le contenu est reconnu comme des images (une par page) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images de fond (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images de fond en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images de fond, car leurs techniques de lissage des bords d'image (anti-aliasing) sont différentes de celles d'Acrobat Reader. Si cela ressemble à un document exporté contenant de telles limites visibles entre les parties des mêmes images de fond, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier PPT ou PPTX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// The path to your PPT or PPTX File.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Save PPT or PPTX file
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Voir aussi

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)