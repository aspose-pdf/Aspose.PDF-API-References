---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DocSaveOptions. Options d'enregistrement pour l'exportation au format Doc
type: docs
weight: 3750
url: /fr/net/aspose.pdf/docsaveoptions/
---
## Classe DocSaveOptions

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
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Utiliser des paragraphes ou des sauts de ligne |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Obtient ou définit la conversion pour les polices Type3. Dans les polices de type 3, les glyphes doivent être définis par des flux d'opérateurs graphiques. Cela signifie que dans la sortie DOC/DOCX, nous voyons des images au lieu de texte. Activez ce paramètre pour convertir les polices Type3 en TTF et obtenir du texte dans le fichier résultant. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Format de sortie |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Résolution X des images converties. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Résolution Y des images converties. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine la distance maximale entre deux lignes de texte relatives. Spécifié en centaines de pourcentages de la hauteur des lignes de texte. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Définit le chemin (nom de fichier ou nom de répertoire) pour stocker les données temporaires lors de la conversion en mode d'enregistrement en mémoire. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Mode de reconnaissance. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Activer la reconnaissance des puces |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Dans le PDF, les mots peuvent être représentés intérieurement par des opérateurs qui impriment les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter des mots, nous devons parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doivent être considérés comme une distance entre les mots lors de la reconnaissance des mots dans le PDF source. (la présence d'un espace vide d'au moins cette largeur entre les lettres signifie que les éléments textuels appartiennent à des mots différents). Il est normalisé par rapport à la taille de la police - 1,0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas où le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Donc, dans la grande majorité des cas, ce paramètre ne change rien dans le document résultant. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Obtient ou définit la procédure de réenregistrement des polices. S'il est défini sur true, nous rechargeons les polices sur chaque page pour éviter l'influence des propriétés de police précédentes et charger la nouvelle police créée à partir de zéro. Définissez cette option sur false si vous souhaitez améliorer les performances. La valeur par défaut est true; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant, l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple, il peut être utilisé pour afficher une barre de progression ou des messages sur le nombre actuel de pages traitées, un exemple de code du gestionnaire qui affiche la progression sur la console est : |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages dans plusieurs threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images d'arrière-plan en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti-aliasing) diffèrent de celles d'Acrobat Reader. Si cela ressemble à un document exporté contenant de telles limites visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

### Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier DOC ou DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
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

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)