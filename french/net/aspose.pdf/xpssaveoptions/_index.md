---
title: "Classe XpsSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.XpsSaveOptions. Options d'enregistrement pour l'exportation au format Xps"
type: docs
weight: 11710
url: /fr/net/aspose.pdf/xpssaveoptions/
---
## XpsSaveOptions class

Options d’enregistrement pour l’exportation au format Xps

```csharp
public class XpsSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/xpssaveoptions/batchsize/) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [DefaultFont](../../aspose.pdf/xpssaveoptions/defaultfont/) { get; set; } | Obtient/définit le nom de police par défaut. Utilisé si le nom de police incorporé n'est pas trouvé dans le système. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [SaveTransparentTexts](../../aspose.pdf/xpssaveoptions/savetransparenttexts/) { get; set; } | Indique s'il faut conserver le texte transparent (OCRisé). |
| [UseEmbeddedTrueTypeFonts](../../aspose.pdf/xpssaveoptions/useembeddedtruetypefonts/) { get; set; } | Obtient/définit le drapeau d'utilisation des polices TrueType incorporées. Éviter l'utilisation des polices TrueType incorporées peut réduire le temps de conversion. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier XPS

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF
	var pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf");

	// Le chemin vers votre fichier XPS
	var xpsFile= Path.Combine(dataDir, "PDF-to-XPS.xps");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialiser XpsSaveOptions\t
		XpsSaveOptions saveOptions = new XpsSaveOptions();
		
		// Enregistrer le fichier XPS
		pdfDocument.Save(xpsFile, saveOptions);
	}
```

```csharp
[VB.NET]
 
    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-XPS.pdf")

    ' The path to your XPS File
    Dim xpsFile = Path.Combine(dataDir, "PDF-to-XPS.xps")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize XpsSaveOptions
        Dim saveOptions As XpsSaveOptions = New XpsSaveOptions()
 
        ' Save XPS file
        pdfDocument.Save(xpsFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


