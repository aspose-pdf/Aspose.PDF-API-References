---
title: "Classe PptxSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.PptxSaveOptions. Options d’enregistrement pour l’exportation au format SVG"
type: docs
weight: 9630
url: /fr/net/aspose.pdf/pptxsaveoptions/
---
## PptxSaveOptions class

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. il peut servir à afficher une barre de progression ou des messages sur le nombre actuel de pages traitées ; un exemple de code du gestionnaire qui affiche la progression dans la console est : |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Obtient ou définit la résolution d’image (dpi). La valeur par défaut est de 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Bascule la reconnaissance des colonnes de texte |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Si défini sur true, les images sont séparées de toutes les autres graphiques |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Si défini sur true, tout le contenu est reconnu comme des images (une par page) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier PPT ou PPTX

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// Le chemin vers votre fichier PPT ou PPTX.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialiser PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Enregistrer le fichier PPT ou PPTX
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


