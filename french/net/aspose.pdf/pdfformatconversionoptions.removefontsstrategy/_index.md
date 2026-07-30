---
title: "Énumération PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.PdfFormatConversionOptionsRemoveFontsStrategy enum. Certains documents ont une taille importante après la conversion au format PDF/A. Pour réduire la taille du fichier de ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies qui peuvent être utilisées pour optimiser l’utilisation des polices. Chaque stratégie de cette énumération n’a de sens que lorsque le drapeau OptimizeFileSize est activé."
type: docs
weight: 8540
url: /fr/net/aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
## PdfFormatConversionOptions.RemoveFontsStrategy enumeration

Certains documents ont une taille importante après la conversion au format PDF/A. Pour réduire la taille du fichier de ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies qui peuvent être utilisées pour optimiser l’utilisation des polices. Chaque stratégie de cette énumération n’a de sens que lorsque le drapeau [`OptimizeFileSize`](../pdfformatconversionoptions/optimizefilesize/) est activé.

```csharp
[Flags]
public enum RemoveFontsStrategy : byte
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| RemoveDuplicatedFonts | `4` | Cette stratégie supprime toutes les polices qui ont des duplicatas dans le document. Si le document contient un groupe de polices dupliquées, une seule police de ce groupe est incorporée dans le document. Toutes les autres polices de ce groupe sont supprimées du document, chaque police supprimée étant remplacée par son analogue déjà incorporé. |
| RemoveSimilarFontsWithDifferentWidths | `1` | Cette stratégie ressemble à RemoveDuplicatedFonts mais elle supprime non pas les polices entièrement dupliquées, mais les polices qui sont similaires les unes aux autres et ne diffèrent que par le paramètre "Widths". Ce paramètre contient un ensemble de largeurs pour des symboles spécifiques de la police. Chaque valeur de largeur de cet ensemble "Widths" n’est pas la largeur réelle du symbole (glyphe) ; la largeur réelle de ce symbole est déjà définie dans les données binaires de la police. La valeur de largeur de l’ensemble "Widths" représente la largeur visuelle de ce symbole – la largeur que le logiciel de visualisation PDF doit appliquer lors de l’affichage du symbole à la place de la largeur réelle définie dans la police. Plus précisément, la spécification indique : les visionneuses Acrobat 5.0 et ultérieures utilisent les largeurs de glyphe stockées dans le dictionnaire de la police pour remplacer les largeurs des glyphes dans le programme de la police lui‑même, ce qui améliore la cohérence de l’affichage et de l’impression du document. Cette stratégie est plus efficace que RemoveDuplicatedFonts mais son utilisation dans certains cas pourrait théoriquement endommager la présentation visuelle du document converti. Ce défaut est possible parce que les largeurs déclarées des polices peuvent différer pour le même symbole et, dans ce cas, la largeur de ce symbole sera modifiée après la substitution de la police – la police supprimée étant remplacée dans le document par une police déjà incorporée. Si la largeur visuelle du symbole est modifiée, il sera affiché incorrectement et cette différence pourrait entraîner des défauts visuels tels que le chevauchement du texte ou d’autres problèmes. Cependant, le défaut visuel décrit est très rare et cette stratégie réduit la taille du document de manière plus efficace. |
| SubsetFonts | `2` | Il s'agit de la stratégie la plus efficace pour réduire la taille du document. Elle prend les jeux de polices entièrement incorporés et les réduit aux seuls sous‑ensembles utilisés. Il est recommandé d’utiliser cette stratégie en combinaison avec RemoveDuplicatedFonts ou RemoveSimilarFontsWithDifferentWidths pour obtenir un effet de compression multiple sur la taille du fichier. L’utilisation simultanée des trois stratégies n’a aucun sens et la stratégie RemoveSimilarFontsWithDifferentWidths ne sera pas utilisée dans ce cas. |

### Voir aussi

* class [PdfFormatConversionOptions](../pdfformatconversionoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


