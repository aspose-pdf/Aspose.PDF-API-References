---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextReplaceOptions. Représente les options de remplacement de texte
type: docs
weight: 11010
url: /fr/net/aspose.pdf.text/textreplaceoptions/
---
## Classe TextReplaceOptions

Représente les options de remplacement de texte

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initialise une nouvelle instance de l'objet `TextReplaceOptions` pour l'action de remplacement spécifiée. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initialise une nouvelle instance de l'objet `TextReplaceOptions` pour la portée spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Obtient ou définit la valeur de l'espacement des lignes utilisé si l'ajustement de remplacement est forcé de créer une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. Par défaut, c'est 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement du texte. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Définit ou obtient l'ajustement de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Obtient ou définit une action qui sera effectuée après le remplacement du fragment de texte par un texte plus court. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Obtient ou définit une portée où l'opération de remplacement de texte est appliquée |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Définit ou obtient l'ajustement de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### Voir aussi

* classe [TextOptions](../textoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)