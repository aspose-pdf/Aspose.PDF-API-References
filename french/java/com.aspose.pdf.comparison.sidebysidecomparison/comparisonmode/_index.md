---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "L'énumération des modes de comparaison."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

L'énumération des modes de comparaison.

## Champs

| Champ | Description |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Tous les espaces sont ignorés. Les modifications sont recherchées uniquement dans les mots. |
| [Normal](#Normal) | Mode normal. Seuls les espaces à l'intérieur des fragments de texte sont pris en compte (selon la façon dont le document est généré.) |
| [ParseSpaces](#ParseSpaces) | Le mode est similaire au mode normal, mais tente de tenir compte de l'espacement visuel entre les fragments de texte en fonction de la distance. Reconnaître le nombre d'espaces entre les fragments peut ne pas être précis car cela dépend fortement de la façon dont les documents sont générés. Si les documents sont créés par différents générateurs, il peut y avoir des inexactitudes dans la comparaison des espaces entre les fragments de texte. Cette option peut produire des résultats qui, bien que logiques, diffèrent des résultats de comparaison attendus lorsqu'elle est appliquée à des documents à structure complexe. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Tous les espaces sont ignorés. Les modifications sont recherchées uniquement dans les mots.

### Normal {#Normal}
```
public static final int Normal
```

Mode normal. Seuls les espaces à l'intérieur des fragments de texte sont pris en compte (selon la façon dont le document est généré.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

Le mode est similaire au mode normal, mais tente de tenir compte de l'espacement visuel entre les fragments de texte en fonction de la distance. Reconnaître le nombre d'espaces entre les fragments peut ne pas être précis car cela dépend fortement de la façon dont les documents sont générés. Si les documents sont créés par différents générateurs, il peut y avoir des inexactitudes dans la comparaison des espaces entre les fragments de texte. Cette option peut produire des résultats qui, bien que logiques, diffèrent des résultats de comparaison attendus lorsqu'elle est appliquée à des documents à structure complexe.
