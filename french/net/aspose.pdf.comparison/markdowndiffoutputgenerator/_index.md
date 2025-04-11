---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator. Représente une classe pour générer une représentation markdown des différences de textes. En raison de la syntaxe markdown, il n'est pas possible de montrer les changements des caractères d'espacement. La sélection des changements nécessite d'ajouter des caractères d'espacement autour du formatage, sinon le visualiseur markdown n'affichera pas correctement le texte. Les sauts de ligne supprimés sont indiqués par le marqueur de paragraphe.
type: docs
weight: 3250
url: /fr/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## Classe MarkdownDiffOutputGenerator

Représente une classe pour générer une représentation markdown des différences de textes. En raison de la syntaxe markdown, il n'est pas possible de montrer les changements des caractères d'espacement. La sélection des changements nécessite d'ajouter des caractères d'espacement autour du formatage, sinon le visualiseur markdown n'affichera pas correctement le texte. Les sauts de ligne supprimés sont indiqués par le marqueur de paragraphe.

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