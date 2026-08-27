---
title: "Classe TextReplaceOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextReplaceOptions. Représente les options de remplacement de texte"
type: docs
weight: 11190
url: /fr/net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Représente les options de remplacement du texte

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initialise une nouvelle instance de l'objet `TextReplaceOptions` pour l'action après remplacement spécifiée. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initialise une nouvelle instance de l'objet `TextReplaceOptions` pour la portée spécifiée. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Obtient ou définit la valeur de l'interligne utilisée si l'ajustement du remplacement force la création d'une nouvelle ligne de texte. La valeur attendue est un multiplicateur de la taille de police du texte remplacé. La valeur par défaut est 1,2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Obtient ou définit la politique d'ajustement de la taille de police pour qu'elle tienne dans les limites définies par le [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut ignorer les paragraphes distincts lors de l'ajustement du texte sur la page après le remplacement de texte. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Définit ou obtient l'ajustement de la position gauche pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = IsFormFillingMode ; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Obtient ou définit le rectangle pour ajuster le texte après le remplacement. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Obtient ou définit une action qui sera exécutée après le remplacement d'un fragment de texte pour le rendre plus court. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Obtient ou définit la portée où l'opération de remplacement de texte est appliquée |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Définit ou obtient l'ajustement de la position droite pour le texte remplacé lors de l'utilisation de TextReplaceOptions : - ReplaceAdjustmentAction = WholeWordsHyphenation ; - ReplaceAdjustmentAction = IsFormFillingMode ; |

### Voir aussi

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


