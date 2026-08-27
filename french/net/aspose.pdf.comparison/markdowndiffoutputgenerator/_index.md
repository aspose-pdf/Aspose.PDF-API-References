---
title: "Classe MarkdownDiffOutputGenerator"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Représente une classe permettant de générer une représentation markdown des différences de texte. En raison de la syntaxe markdown, il n'est pas possible d'afficher les modifications des caractères d'espacement. La sélection des changements entraîne l'ajout de caractères d'espacement autour du formatage, sinon le visualiseur markdown n'affichera pas correctement le texte. Les sauts de ligne supprimés sont indiqués par le symbole de marque de paragraphe."
type: docs
weight: 3360
url: /fr/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

Représente une classe générant une représentation markdown des différences de texte. En raison de la syntaxe markdown, il n'est pas possible d'afficher les modifications des caractères d'espacement. La sélection des modifications entraîne l'ajout de caractères d'espacement autour du formatage, sinon le visualiseur markdown n'affichera pas correctement le texte. Les sauts de ligne supprimés sont indiqués par le symbole de paragraphe -.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Génère la sortie basée sur les différences entre les textes et l'enregistre dans un fichier. |

### Voir aussi

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


