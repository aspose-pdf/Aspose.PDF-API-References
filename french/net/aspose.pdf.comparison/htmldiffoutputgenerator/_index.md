---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Représente une classe pour générer une représentation html des différences de textes. Les sauts de ligne supprimés sont indiqués par un marqueur de paragraphe.
type: docs
weight: 3200
url: /fr/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Classe HtmlDiffOutputGenerator

Représente une classe pour générer une représentation html des différences de textes. Les sauts de ligne supprimés sont indiqués par un marqueur de paragraphe.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Crée une instance de la classe `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Crée une instance de la classe `HtmlDiffOutputGenerator`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération de suppression. Exemple : |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération d'égalité. Exemple : |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération d'insertion. Exemple : |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Obtient ou définit le style de décoration de texte : ligne à travers pour l'opération de suppression. La valeur par défaut est `False`. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |

### Voir aussi

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)