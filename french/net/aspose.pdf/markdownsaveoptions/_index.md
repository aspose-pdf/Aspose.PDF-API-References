---
title: "Classe MarkdownSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.MarkdownSaveOptions. Représente la classe d’options d’enregistrement du document au format markdown"
type: docs
weight: 7050
url: /fr/net/aspose.pdf/markdownsaveoptions/
---
## MarkdownSaveOptions class

Représente la classe d'options d'enregistrement du document au format markdown.

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
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Obtient ou définit une zone rectangulaire pour extraire le contenu en markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Obtient ou définit le style d’emphase pour le document généré. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Obtient et définit une propriété indiquant si les graphiques vectoriels doivent être extraits. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Définit les niveaux de titres attendus à utiliser dans la stratégie de reconnaissance des en-têtes par taille de police. Si la valeur de cette propriété est définie, alors la stratégie heuristique de reconnaissance des en-têtes sera sélectionnée lorsque la valeur !:PdfToMarkdown.HeadingRecognitionStrategy.Auto est définie, même si le document contient des signets. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Obtient ou définit la stratégie de reconnaissance des en-têtes. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Obtient ou définit le style de titre pour le document généré. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Obtient ou définit le style de saut de ligne pour le document généré. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Obtient et définit le nom du répertoire où enregistrer les ressources du document telles que les images. Si la valeur n'est pas spécifiée, les images seront écrites dans le même répertoire que le fichier markdown lui‑même. Ce n’est pas un chemin, c’est uniquement un nom ! Ce répertoire sera créé automatiquement dans le répertoire contenant le fichier markdown enregistré. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Obtient et définit l'autorisation de convertir les indices et exposants. Cette valeur est vraie par défaut. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Obtient et définit l'autorisation d'utiliser une balise img pour insérer des images à gauche et à droite du texte. Dans ce cas, dans le visualiseur markdown, le texte s’enroulera autour de l’image. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


