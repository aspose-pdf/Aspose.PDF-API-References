---
title: DocSaveOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: Enregistrer les options dexportation au format Doc
type: docs
weight: 1840
url: /fr/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Enregistrer les options d'exportation au format Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Utilisez des sauts de paragraphe ou de ligne |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Obtient ou définit une valeur booléenne qui indique que l'objet de réponse sera fermé après l'enregistrement du document dans la réponse. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Cet attribut a activé la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Format de sortie |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Résolution X des images converties. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Résolution Y des images converties. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Ce paramètre est utilisé pour regrouper les lignes de texte en paragraphes. Détermine la distance qui peut séparer deux lignes de texte relatives. Spécifié en centaines de pour cent de la hauteur des lignes de texte. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Définit le chemin (nom de fichier ou nom de répertoire) pour conserver les données temporaires lors de la conversion en mode d'économie de mémoire. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Mode de reconnaissance. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Activer la reconnaissance des balles |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | En Pdf, les mots peuvent être représentés en interne avec des opérateurs qui impriment les mots en imprimant indépendamment leurs lettres ou syllabes. Ainsi, pour détecter des mots, nous devons parfois détecter des groupes de caractères indépendants qui sont en fait des mots. Ce paramètre définit la largeur de l'espace entre les éléments de texte (lettres, syllabes) qui doivent être traités comme une distance entre les mots lors de la reconnaissance des mots dans le PDF source . (la présence d'un espace vide au moins avec cette largeur entre les lettres signifie que éléments textuels se rapportent à des mots différents). Il est normé à la taille de la police - 1.0 signifie 100 % de la taille de police supposée du mot. ATTENTION ! Il n'est utilisé que dans les cas lorsque le PDF source contient des polices spécifiques rarement utilisées pour lesquelles la valeur optimale ne peut pas être calculée à partir de la police. Ainsi, dans la grande majorité des cas, ce paramètre ne change rien au document de résultat. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format de sauvegarde des données. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l'élément d'énumération ReturnAction en spécifiant Continuer ou Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde se poursuit, mais l'utilisateur peut également renvoyer Abort, auquel cas l'opération de sauvegarde doit cesser. |

## Des champs

| Nom | La description |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion fe il peut être utilisé pour afficher la barre de progression ou des messages sur la quantité actuelle de pages traitées, exemple de code de gestionnaire qui montre la progression sur la console est : |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Parfois, les fichiers PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière-plan en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus de formats cibles (par exemple MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images d'arrière-plan , car leurs techniques de lissage des bords de l'image (anti-crénelage) sont différentes d'Acrobat Reader. S'il semble que le document exporté contient de telles limites visibles entre parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de de cela effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement essentiellement la conversion, donc, s'il vous plaît, n'utilisez cette option que lorsque c'est vraiment nécessaire. |

### Voir également

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
