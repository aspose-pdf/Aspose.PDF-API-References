---
title: "Classe DocSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.DocSaveOptions. Options d'enregistrement pour l'exportation au format Doc"
type: docs
weight: 3870
url: /fr/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Options d'enregistrement pour l'exportation au format Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Utilisez des sauts de paragraphe ou de ligne |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Obtient ou définit la conversion pour les polices Type3. Dans les polices Type3, les glyphes doivent être définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX nous voyons des images au lieu du texte. Définissez ce drapeau sur true pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Format de sortie |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Résolution X des images converties. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Résolution Y des images converties. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Il détermine à quelle distance peuvent se trouver deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Mode de reconnaissance. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Activer la reconnaissance des puces |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Dans les PDF, les mots peuvent être représentés en interne par des opérateurs qui impriment les mots en affichant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter les mots, il faut parfois identifier des groupes de caractères indépendants qui sont en réalité des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doit être considérée comme la distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé à la taille de la police : 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne modifie rien dans le document résultant. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Obtient ou définit la procédure de réenregistrement des polices. Si elle est définie sur true, nous rechargeons les polices à chaque page pour éviter l'influence des propriétés de police précédentes et charger la police nouvellement créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true ; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. il peut servir à afficher une barre de progression ou des messages sur le nombre actuel de pages traitées ; un exemple de code du gestionnaire qui affiche la progression dans la console est : |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

### Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier DOC ou DOCX

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// Le chemin du fichier DOC ou DOCX de sortie.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Définir le mode de reconnaissance comme Flux
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Définir la proximité horizontale à 2,5
			RelativeHorizontalProximity = 2.5f,
			// Activer la reconnaissance des puces pendant le processus de conversion
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


