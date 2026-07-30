---
title: "Énum ComparisonMode"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Comparison.ComparisonMode enum. L'énumération du mode de comparaison"
type: docs
weight: 3250
url: /fr/net/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enumeration

L'énumération des modes de comparaison.

```csharp
public enum ComparisonMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Normal | `0` | Mode normal. Seuls les espaces à l'intérieur des fragments de texte sont pris en compte (en fonction de la façon dont le document est généré.) |
| IgnoreSpaces | `1` | Tous les espaces sont ignorés. Les modifications sont recherchées uniquement dans les mots. |
| ParseSpaces | `2` | Le mode est similaire au mode normal, mais tente de tenir compte de l'espacement visuel entre les fragments de texte en fonction de la distance. Reconnaître le nombre d'espaces entre les fragments peut ne pas être précis car cela dépend fortement de la façon dont les documents sont générés. Si les documents sont créés par différents générateurs, il peut y avoir des imprécisions dans la comparaison des espaces entre les fragments de texte. |

### Voir aussi

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


