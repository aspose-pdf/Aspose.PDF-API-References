---
title: "Classe RenderingOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.RenderingOptions. Représente les options de rendu"
type: docs
weight: 9910
url: /fr/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

Représente les options de rendu.

```csharp
public sealed class RenderingOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le !:FontRepository.Sources. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer les noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système une police capable d'afficher les caractères requis. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Obtient ou définit le mode d'optimisation du code-barres. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indique que toutes les polices seront converties en versions Unicode TTF. Cela est utile pour des raisons de compatibilité et pour optimiser l'utilisation des polices, car chaque nouvelle police TTF ne contiendra pas tous les symboles de la police source, mais uniquement les symboles utilisés dans le texte. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Obtient/définit le nom par défaut de la police utilisée pour remplacer les polices manquantes. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront ignorés pendant le traitement. false par défaut |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Obtient ou définit le mode de haute qualité pour l'interpolation. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Nombre maximal de polices dans le cache des polices. La valeur par défaut est 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Nombre maximal de symboles dans le cache des symboles. La valeur par défaut est 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Obtient ou définit le mode d'optimisation des dimensions. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Obtient ou définit un mode où les polices système sont rendues nativement. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | L'utilisation de ce drapeau active le mécanisme d'optimisation des polices (font hinting). Le hinting des polices consiste à utiliser des instructions mathématiques pour ajuster l'affichage d'une police vectorielle. Dans certains cas, activer ce drapeau peut résoudre des problèmes de lisibilité du texte. À l'heure actuelle, l'utilisation de ce drapeau ne produit d'effet que pour les polices TTF, si ces polices sont utilisées dans le document source. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Obtient ou définit une valeur utilisée pour augmenter ou diminuer la largeur du rectangle pour l'opérateur AppendRectangle. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


