---
title: "Classe EpubSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.EpubSaveOptions classe. Options d'enregistrement pour l'exportation au format EPUB"
type: docs
weight: 4180
url: /fr/net/aspose.pdf/epubsaveoptions/
---
## EpubSaveOptions class

Options d'enregistrement pour l'exportation au format EPUB

```csharp
public class EpubSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EpubSaveOptions](epubsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [Title](../../aspose.pdf/epubsaveoptions/title/) { get; set; } | Obtient ou définit le titre du document EPUB. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [ContentRecognitionMode](../../aspose.pdf/epubsaveoptions/contentrecognitionmode/) | Lorsque le fichier PDF (qui a généralement une mise en page fixe) est converti, le moteur de conversion tente d'effectuer un regroupement et une analyse à plusieurs niveaux afin de restaurer l'intention de l'auteur du document original et de produire un résultat en mise en page fluide. Cette propriété ajuste cette conversion pour telle ou telle méthode souhaitable de reconnaissance du contenu. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier EPUB

```csharp
	[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf");

	// Le chemin du fichier EPUB de sortie.
	var epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub");
		
	using (Document pdfDocument = new Document(pdfFile))
	{

		// Initialiser EpubSaveOptions 	
		EpubSaveOptions saveOptions = new EpubSaveOptions();
		
		// Enregistrer le fichier EPUB
		pdfDocument.Save(epubFile, saveOptions);
	}
````

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-EPUB.pdf")

    ' The path to output EPUB File.
    Dim epubFile = Path.Combine(dataDir, "PDF-to-EPUB.epub")
 
    Using pdfDocument As Document = New Document(pdfFile)

        ' Initialize EpubSaveOptions    
        Dim saveOptions As EpubSaveOptions = New EpubSaveOptions()
 
        ' Save EPUB file
        pdfDocument.Save(epubFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


