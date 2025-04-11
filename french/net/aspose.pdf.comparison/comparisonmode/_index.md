---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Enumération Aspose.Pdf.Comparison.ComparisonMode. L'énumération du mode de comparaison
type: docs
weight: 3140
url: /fr/net/aspose.pdf.comparison/comparisonmode/
---
## Énumération ComparisonMode

L'énumération du mode de comparaison.

```csharp
public enum ComparisonMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Normal | `0` | Mode normal. Seules les espaces au sein des fragments de texte sont prises en compte (selon la manière dont le document est généré.) |
| IgnoreSpaces | `1` | Tous les espaces sont ignorés. Les changements ne sont recherchés que dans les mots. |
| ParseSpaces | `2` | Le mode est similaire au normal, mais tente de tenir compte de l'espacement visuel entre les fragments de texte en fonction de la distance. La reconnaissance du nombre d'espaces entre les fragments peut ne pas être précise car cela dépend beaucoup de la manière dont les documents sont générés. Si les documents sont créés par différents générateurs, il peut y avoir des inexactitudes dans la comparaison des espaces entre les fragments de texte. |

### Voir Aussi

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)