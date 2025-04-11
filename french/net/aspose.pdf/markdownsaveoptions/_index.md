---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.MarkdownSaveOptions. Représente la classe d'options de sauvegarde de document au format markdown
type: docs
weight: 6910
url: /fr/net/aspose.pdf/markdownsaveoptions/
---
## Classe MarkdownSaveOptions

Représente la classe d'options de sauvegarde de document au format markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Obtient ou définit une zone rectangulaire à extraire au format markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si l'objet Response sera fermé après que le document a été enregistré dans la réponse. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Obtient ou définit le style d'emphase pour le document généré. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Définit les niveaux de titre attendus à utiliser dans la stratégie de reconnaissance des en-têtes FontSize. Si la valeur de cette propriété est définie, alors la stratégie de reconnaissance des en-têtes !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic sera sélectionnée lorsque les stratégies !:PdfToMarkdown.HeadingRecognitionStrategy.Auto seront définies même si le document contient des signets. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Obtient ou définit la stratégie de reconnaissance des en-têtes. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Obtient ou définit le style d'en-tête pour le document généré. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Obtient ou définit le style de saut de ligne pour le document généré. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Obtient et définit le nom du répertoire pour enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui-même. Ce n'est pas un chemin, c'est seulement un nom ! Ce répertoire sera automatiquement créé dans le répertoire avec le fichier markdown enregistré. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Obtient et définit la possibilité de convertir les indices et les exposants. Cette valeur est vraie par défaut. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Obtient et définit la possibilité d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s'enroulera autour de l'image. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant l'utilisateur peut également retourner Abandonner dans ce cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images d'arrière-plan en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des limites visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anti-aliasing) sont différentes de celles d'Acrobat Reader. Si cela ressemble à un document exporté contenant de telles limites visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |

### Voir aussi

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)