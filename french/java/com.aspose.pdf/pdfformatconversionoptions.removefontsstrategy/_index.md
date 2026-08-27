---
title: "PdfFormatConversionOptions.RemoveFontsStrategy"
linktitle: "PdfFormatConversionOptions.RemoveFontsStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Certains documents ont une taille importante après conversion au format PDF/A. Pour réduire la taille du fichier de ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération."
type: docs
weight: 3760
url: /fr/java/com.aspose.pdf/pdfformatconversionoptions.removefontsstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.PdfFormatConversionOptions.RemoveFontsStrategy

```
public static class PdfFormatConversionOptions.RemoveFontsStrategy extends com.aspose.ms.System.Enum
```

Certains documents ont une taille importante après conversion au format PDF/A. Pour réduire la taille du fichier de ces documents, il est nécessaire de définir une stratégie de suppression des polices. Cette énumération déclare des stratégies pouvant être utilisées pour optimiser l'utilisation des polices. Chaque stratégie de cette énumération n'a de sens que lorsque l'indicateur {@code OptimizeFileSize} est activé.

## Champs

| Champ | Description |
| --- | --- |
| [RemoveDuplicatedFonts](#RemoveDuplicatedFonts) | Cette stratégie supprime toutes les polices qui ont des duplicata dans le document. Si le document contient un groupe de polices dupliquées, une seule police de ce groupe est incorporée dans le document. Toutes les autres polices de ce groupe sont supprimées du document, chaque police supprimée étant remplacée par l'analogue déjà incorporé. |
| [RemoveSimilarFontsWithDifferentWidths](#RemoveSimilarFontsWithDifferentWidths) | Cette stratégie ressemble à {@code RemoveDuplicatedFonts} mais elle ne supprime pas les polices entièrement dupliquées, mais les polices qui sont similaires les unes aux autres et ne diffèrent que par le paramètre \"Widths\". Ce paramètre contient un ensemble de certaines largeurs pour les symboles spécifiés de la police. Chaque valeur de largeur de cet ensemble \"Widths\" n'est pas la largeur réelle du symbole (glyphe), la largeur réelle de ce symbole étant déjà définie dans les données binaires de la police. La valeur de largeur de l'ensemble \"Widths\" représente la largeur visuelle de ce symbole – la largeur que le logiciel de visualisation PDF doit appliquer lors de l'affichage du symbole à la place de la largeur réelle définie dans la police. Plus précisément, la spécification indique : les visionneuses Acrobat 5.0 et ultérieures utilisent les largeurs de glyphes stockées dans le dictionnaire de la police pour remplacer les largeurs des glyphes dans le programme de la police lui‑même, ce qui améliore la cohérence de l'affichage et de l'impression du document. Cette stratégie est plus efficace que {@code RemoveDuplicatedFonts}, mais son utilisation dans certains cas pourrait théoriquement endommager la présentation visuelle du document converti. Ce défaut est possible parce que les largeurs déclarées des polices peuvent différer pour le même symbole et, dans ce cas, la largeur de ce symbole sera modifiée après la substitution de police – la police supprimée étant remplacée dans le document par une police déjà incorporée. Et si la largeur visuelle du symbole est modifiée, il sera affiché de façon incorrecte et cette différence peut entraîner des défauts visuels tels que le chevauchement du texte ou d'autres problèmes. Cependant, le défaut visuel décrit est très rare et cette stratégie réduit la taille du document de façon plus efficace. |
| [SubsetFonts](#SubsetFonts) | C'est la stratégie la plus efficace pour réduire la taille du document. Elle prend les ensembles de polices entièrement incorporées et les réduit aux seuls sous‑ensembles utilisés. Il est recommandé d'utiliser cette stratégie en combinaison avec {@code RemoveDuplicatedFonts} ou {@code RemoveSimilarFontsWithDifferentWidths} afin d'obtenir un effet de compression multiple sur la taille du fichier. L'utilisation simultanée des trois stratégies n'a aucun sens et la stratégie {@code RemoveSimilarFontsWithDifferentWidths} ne sera pas utilisée dans ce cas. |

### RemoveDuplicatedFonts {#RemoveDuplicatedFonts}
```
public static final byte RemoveDuplicatedFonts
```

Cette stratégie supprime toutes les polices qui ont des duplicata dans le document. Si le document contient un groupe de polices dupliquées, une seule police de ce groupe est incorporée dans le document. Toutes les autres polices de ce groupe sont supprimées du document, chaque police supprimée étant remplacée par l'analogue déjà incorporé.

### RemoveSimilarFontsWithDifferentWidths {#RemoveSimilarFontsWithDifferentWidths}
```
public static final byte RemoveSimilarFontsWithDifferentWidths
```

Cette stratégie ressemble à {@code RemoveDuplicatedFonts} mais elle ne supprime pas les polices entièrement dupliquées, mais les polices qui sont similaires les unes aux autres et ne diffèrent que par le paramètre \"Widths\". Ce paramètre contient un ensemble de certaines largeurs pour les symboles spécifiés de la police. Chaque valeur de largeur de cet ensemble \"Widths\" n'est pas la largeur réelle du symbole (glyphe), la largeur réelle de ce symbole étant déjà définie dans les données binaires de la police. La valeur de largeur de l'ensemble \"Widths\" représente la largeur visuelle de ce symbole – la largeur que le logiciel de visualisation PDF doit appliquer lors de l'affichage du symbole à la place de la largeur réelle définie dans la police. Plus précisément, la spécification indique : les visionneuses Acrobat 5.0 et ultérieures utilisent les largeurs de glyphes stockées dans le dictionnaire de la police pour remplacer les largeurs des glyphes dans le programme de la police lui‑même, ce qui améliore la cohérence de l'affichage et de l'impression du document. Cette stratégie est plus efficace que {@code RemoveDuplicatedFonts}, mais son utilisation dans certains cas pourrait théoriquement endommager la présentation visuelle du document converti. Ce défaut est possible parce que les largeurs déclarées des polices peuvent différer pour le même symbole et, dans ce cas, la largeur de ce symbole sera modifiée après la substitution de police – la police supprimée étant remplacée dans le document par une police déjà incorporée. Et si la largeur visuelle du symbole est modifiée, il sera affiché de façon incorrecte et cette différence peut entraîner des défauts visuels tels que le chevauchement du texte ou d'autres problèmes. Cependant, le défaut visuel décrit est très rare et cette stratégie réduit la taille du document de façon plus efficace.

### SubsetFonts {#SubsetFonts}
```
public static final byte SubsetFonts
```

C'est la stratégie la plus efficace pour réduire la taille du document. Elle prend les ensembles de polices entièrement incorporées et les réduit aux seuls sous‑ensembles utilisés. Il est recommandé d'utiliser cette stratégie en combinaison avec {@code RemoveDuplicatedFonts} ou {@code RemoveSimilarFontsWithDifferentWidths} afin d'obtenir un effet de compression multiple sur la taille du fichier. L'utilisation simultanée des trois stratégies n'a aucun sens et la stratégie {@code RemoveSimilarFontsWithDifferentWidths} ne sera pas utilisée dans ce cas.
