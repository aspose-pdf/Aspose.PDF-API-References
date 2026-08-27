---
title: "Classe SvgSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.SvgSaveOptions class. Options d'enregistrement pour l'exportation au format SVG"
type: docs
weight: 10410
url: /fr/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Spécifie si la sortie sera créée sous forme d'une archive zip unique. Veuillez vous référer au commentaire des options 'TreatTargetFileNameAsDirectory' pour voir les règles de nommage des fichiers svg des pages d'un document source multipage, qui sont également appliquées à l'ensemble de fichiers de sortie compressés. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers d'images externes référencés créés (comme les BMP ou JPEG incorporés) incorporés dans le SVG enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne représentant l'URI souhaitée de la ressource enregistrée dans le SVG généré. Si le traitement de ce fichier ou de celui‑ci doit, pour une raison quelconque, être effectué par le code du convertisseur lui‑même, et non dans du code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'imageSavingInfo'. Cela indique au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur comme s'il n’y avait aucun code personnalisé externe. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Spécifie s'il faut mettre à l'échelle le document de sortie des points typographiques aux pixels. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Cette option définit si un répertoire cible (s'il n'existe pas encore) sera créé avec le même nom que le fichier de sortie demandé au lieu du fichier de sortie lui‑même. Ainsi, le répertoire contiendra toutes les images SVG de sortie des pages (comme décrit ci‑dessous). Si l'option est désactivée, les fichiers de sortie des pages autres que la première seront créés exactement dans le répertoire demandé comme fichier de sortie principal, mais porteront le suffixe _[2...n] dans le nom de fichier, défini par le numéro de page, par ex. si vous définissez le fichier de sortie "C:\\AsposeTests\\output.svg" et que la sortie contient plusieurs fichiers svg de pages, alors les fichiers des pages seront également créés dans le répertoire "C:\\AsposeTests\\" et auront les noms 'output.svg', 'output_2.svg', 'output_3.svg', etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier SVG

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// Le chemin du fichier SVG de sortie.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialiser SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Enregistrer le fichier SVG
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

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


