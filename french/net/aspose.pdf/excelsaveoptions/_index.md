---
title: "Class ExcelSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.ExcelSaveOptions class. Options d'enregistrement pour l'exportation au format Excel"
type: docs
weight: 4200
url: /fr/net/aspose.pdf/excelsaveoptions/
---
## ExcelSaveOptions class

Options d'enregistrement pour l'exportation au format Excel

```csharp
public class ExcelSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ExcelSaveOptions](excelsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [Format](../../aspose.pdf/excelsaveoptions/format/) { get; set; } | Format de sortie |
| [InsertBlankColumnAtFirst](../../aspose.pdf/excelsaveoptions/insertblankcolumnatfirst/) { get; set; } | Définissez true si vous avez besoin d'insérer une colonne vide comme première colonne de la feuille de calcul. La valeur par défaut est false ; cela signifie qu'aucune colonne vide ne sera insérée. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf/excelsaveoptions/minimizethenumberofworksheets/) { get; set; } | Définissez true si vous devez réduire le nombre de feuilles de calcul dans le classeur résultant. La valeur par défaut est false ; cela signifie que chaque page PDF sera enregistrée comme une feuille séparée. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [UniformWorksheets](../../aspose.pdf/excelsaveoptions/uniformworksheets/) { get; set; } | Définissez true pour utiliser une division uniforme des colonnes dans le document. La valeur par défaut est false ; cela signifie que la division des colonnes sera indépendante pour chaque page. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier XLS ou XLSX

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf");

	// Le chemin vers le fichier xls ou xlsx de sortie.
	var excelFile= Path.Combine(dataDir, "PDF-to-xlsx.xlsx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize ExcelSaveOptions	
		ExcelSaveOptions saveOptions = new ExcelSaveOptions();
		
		// Enregistrer le fichier xls ou xlsx
		pdfDocument.Save(excelFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-xlsx.pdf")
    
	' The path to output xls or xlsx File.
    Dim excelFile = Path.Combine(dataDir, "PDF-to-xlsx.xlsx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize ExcelSaveOptions  
        Dim saveOptions As ExcelSaveOptions = New ExcelSaveOptions()
 
        ' Save xls or xlsx file
        pdfDocument.Save(excelFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


