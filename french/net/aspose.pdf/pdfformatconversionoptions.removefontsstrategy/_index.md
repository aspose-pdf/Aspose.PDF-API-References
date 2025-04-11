---
title: Enum PdfFormatConversionOptions.RemoveFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: Enum PdfFormatConversionOptionsRemoveFontsStrategy d'Aspose.Pdf. Certains documents ont une taille importante après conversion au format PDF/A. Pour réduire la taille des fichiers pour ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies qui peuvent être utilisées pour optimiser l'utilisation des polices. Chaque stratégie de cette énumération a du sens uniquement lorsque le drapeau OptimizeFileSize est défini.
type: docs
weight: 8400
url: /fr/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## Énumération PdfFormatConversionOptions.RemoveFontsStrategy

Certains documents ont une taille importante après conversion au format PDF/A. Pour réduire la taille des fichiers pour ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies qui peuvent être utilisées pour optimiser l'utilisation des polices. Chaque stratégie de cette énumération a du sens uniquement lorsque le drapeau [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) est défini.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Cette stratégie supprime toutes les polices qui ont des doublons dans le document. Si le document contient un groupe de polices dupliquées, une seule police de ce groupe est intégrée dans le document. Toutes les autres polices de ce groupe sont supprimées du document, chaque police supprimée étant remplacée par l'analogue déjà intégré. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Cette stratégie ressemble à RemoveDuplicatedFonts mais elle ne supprime pas les polices entièrement dupliquées, mais les polices qui sont similaires les unes aux autres et ne diffèrent que par le paramètre "Largeurs". Ce paramètre contient un ensemble de certaines largeurs pour des symboles spécifiés de la police. Chaque valeur de largeur de cet ensemble "Largeurs" n'est pas la largeur réelle du symbole (glyphe), la largeur réelle de ce symbole étant déjà définie dans les données binaires de la police. La valeur de largeur de l'ensemble "Largeurs" signifie la largeur visuelle de ce symbole - la largeur que le logiciel de visualisation PDF doit définir lors de l'affichage du symbole au lieu de la largeur réelle définie dans la police. Plus précisément, la spécification indique : les visionneuses Acrobat 5.0 et ultérieures utilisent les largeurs de glyphe stockées dans le dictionnaire de la police pour remplacer les largeurs des glyphes dans le programme de police lui-même, ce qui améliore la cohérence de l'affichage et de l'impression du document. Cette stratégie est plus efficace que RemoveDuplicatedFonts mais l'utilisation de cette stratégie dans certains cas pourrait théoriquement endommager la présentation visuelle du document converti. Ce défaut est possible en raison du fait que les largeurs déclarées des polices pourraient être différentes pour le même symbole et dans ce cas, la largeur de ce symbole sera changée en une nouvelle après la substitution de la police - lorsque la police supprimée sera remplacée dans le document par celle déjà intégrée. Et si la largeur visuelle du symbole est modifiée - elle sera affichée incorrectement et cette distinction pourrait causer des défauts visuels tels que le chevauchement de texte ou d'autres problèmes. Mais le défaut visuel décrit est un cas très rare et cette stratégie réduit la taille du document de manière plus efficace. |
| SubsetFonts | `2` | C'est la stratégie la plus efficace pour réduire la taille du document. Elle prend des ensembles de polices entièrement intégrées et les réduit uniquement aux sous-ensembles utilisés. Il est recommandé d'utiliser cette stratégie en combinaison avec RemoveDuplicatedFonts ou RemoveSimilarFontsWithDifferentWidths pour obtenir un effet de compression multiple pour la taille du fichier. L'utilisation des trois stratégies simultanément n'a pas de sens et la stratégie RemoveSimilarFontsWithDifferentWidths ne sera pas utilisée dans ce cas. |

### Voir aussi

* classe [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)