---
title: Class ComparisonOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.ComparisonOptions. Représente une classe d'options de comparaison de documents PDF
type: docs
weight: 3150
url: /fr/net/aspose.pdf.comparison/comparisonoptions/
---
## Classe ComparisonOptions

Représente une classe d'options de comparaison de documents PDF.

```csharp
public class ComparisonOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ComparisonOptions](comparisonoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [EditOperationsOrder](../../aspose.pdf.comparison/comparisonoptions/editoperationsorder/) { get; set; } | Obtient et définit l'ordre des opérations d'édition. |
| [ExcludeAreas1](../../aspose.pdf.comparison/comparisonoptions/excludeareas1/) { get; set; } | Obtient et définit les zones à exclure. Utilisé pour la première page ou le document dans la méthode de comparaison. Cette option peut être définie avec [`ExcludeTables`](./excludetables/). Cette option ne peut pas être définie avec l'option [`ExtractionArea`](./extractionarea/). |
| [ExcludeAreas2](../../aspose.pdf.comparison/comparisonoptions/excludeareas2/) { get; set; } | Obtient et définit les zones à exclure. Utilisé pour la deuxième page ou le document dans la méthode de comparaison. Cette option peut être définie avec [`ExcludeTables`](./excludetables/). Cette option ne peut pas être définie avec l'option [`ExtractionArea`](./extractionarea/). |
| [ExcludeTables](../../aspose.pdf.comparison/comparisonoptions/excludetables/) { get; set; } | Obtient et définit l'option qui détermine si les tables sont exclues de la comparaison. Cette option ne peut pas être définie avec l'option [`ExtractionArea`](./extractionarea/). La valeur par défaut est `false`. |
| [ExtractionArea](../../aspose.pdf.comparison/comparisonoptions/extractionarea/) { get; set; } | Obtient et définit la zone rectangulaire dans laquelle le texte des pages sera comparé. Cette option ne peut pas être définie avec les options [`ExcludeTables`](./excludetables/), [`ExcludeAreas1`](./excludeareas1/) et [`ExcludeAreas2`](./excludeareas2/). |

### Voir aussi

* espace de noms [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)