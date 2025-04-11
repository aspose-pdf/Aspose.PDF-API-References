---
title: Class SideBySideComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.SideBySideComparisonOptions. Représente une classe d'options pour comparer des documents avec une sortie côte à côte
type: docs
weight: 3290
url: /fr/net/aspose.pdf.comparison/sidebysidecomparisonoptions/
---
## Classe SideBySideComparisonOptions

Représente une classe d'options pour comparer des documents avec une sortie côte à côte.

```csharp
public class SideBySideComparisonOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SideBySideComparisonOptions](sidebysidecomparisonoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AdditionalChangeMarks](../../aspose.pdf.comparison/sidebysidecomparisonoptions/additionalchangemarks/) { get; set; } | Obtenir et définir la propriété qui détermine si des marqueurs de changement supplémentaires sont affichés. Si défini, affiche les marques de changement qui ne sont pas sur la page actuelle mais qui sont présentes sur une autre page. Si le changement se situe entre des mots, la marque peut ne pas être positionnée exactement par rapport au caractère d'espace. La valeur par défaut est `false`. |
| [ComparisonArea1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea1/) { get; set; } | Obtenir et définir la zone de comparaison. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option ne peut pas être définie avec les options [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) et [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonArea2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonarea2/) { get; set; } | Obtenir et définir la zone de comparaison. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option ne peut pas être définie avec les options [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) et [`ExcludeAreas2`](./excludeareas2/). |
| [ComparisonMode](../../aspose.pdf.comparison/sidebysidecomparisonoptions/comparisonmode/) { get; set; } | Obtient et définit un mode de comparaison. La valeur par défaut est !:SideBySideComparison.ComparisonMode.IgnoreSpaces. |
| [ExcludeAreas1](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas1/) { get; set; } | Obtenir et définir les zones à exclure. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec [`ExcludeTables`](./excludetables/). Cette option ne peut pas être définie avec l'option [`ComparisonArea1`](./comparisonarea1/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludeareas2/) { get; set; } | Obtenir et définir les zones à exclure. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec [`ExcludeTables`](./excludetables/). Cette option ne peut pas être définie avec l'option [`ComparisonArea2`](./comparisonarea2/). |
| [ExcludeTables](../../aspose.pdf.comparison/sidebysidecomparisonoptions/excludetables/) { get; set; } | Obtenir et définir l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie avec [`ComparisonArea1`](./comparisonarea1/) et [`ComparisonArea2`](./comparisonarea2/). La valeur par défaut est `false`. |

### Voir aussi

* espace de noms [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)