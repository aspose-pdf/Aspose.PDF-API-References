---
title: "Classe HtmlDiffOutputGenerator"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. Représente une classe permettant de générer une représentation HTML des différences de textes. Les sauts de ligne supprimés sont indiqués par la marque de paragraphe"
type: docs
weight: 3310
url: /fr/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Représente une classe générant une représentation HTML des différences de texte. Les sauts de ligne supprimés sont indiqués par le symbole de paragraphe.

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
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération Delete. Exemple : |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération Equal. Exemple : |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Obtient et définit la chaîne de style CSS pour l'opération Insert. Exemple : |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Obtient ou définit le style text-decoration: line-through pour l'opération de suppression. La valeur par défaut est `False`. |

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


