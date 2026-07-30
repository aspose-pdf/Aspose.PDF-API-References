---
title: "Classe TeXSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.TeXSaveOptions. Options d'enregistrement pour l'exportation au format TeX"
type: docs
weight: 10580
url: /fr/net/aspose.pdf/texsaveoptions/
---
## TeXSaveOptions class

Options d'enregistrement pour l'exportation au format TeX

```csharp
public class TeXSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TeXSaveOptions](texsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [OutDirectoryPath](../../aspose.pdf/texsaveoptions/outdirectorypath/) { get; set; } | Propriété pour le paramètre _outDirectoryPath. |
| [PagesCount](../../aspose.pdf/texsaveoptions/pagescount/) { get; } | Renvoie le nombre de pages après la conversion. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddFontEncs](../../aspose.pdf/texsaveoptions/addfontencs/)(params string[]) | Ajoute un encodage de police à la liste des encodages de police |
| [ClearFontEncs](../../aspose.pdf/texsaveoptions/clearfontencs/)() | Efface la liste des encodages de police |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier TeX

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf");

	// Le chemin du fichier TeX de sortie.
	var texFile= Path.Combine(dataDir, "PDF-to-TeX.tex");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialiser TeXSaveOptions	
		TeXSaveOptions saveOptions = new TeXSaveOptions();
		
		// Enregistrer le fichier TeX
		pdfDocument.Save(texFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-TeX.pdf")

    ' The path to output TeX File.
    Dim texFile = Path.Combine(dataDir, "PDF-to-TeX.tex")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize TeXSaveOptions
        Dim saveOptions As TeXSaveOptions = New TeXSaveOptions()
 
        ' Save TeX file
        pdfDocument.Save(texFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


