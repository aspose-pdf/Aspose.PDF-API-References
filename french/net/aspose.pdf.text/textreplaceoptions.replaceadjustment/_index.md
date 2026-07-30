---
title: "Enum TextReplaceOptions.ReplaceAdjustment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Enum Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment. Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. None aucune action le texte remplacé peut chevaucher le reste de la ligne AdjustSpaceWidth tente d'ajuster les espaces entre les mots pour conserver la longueur de la ligne WholeWordsHyphenation tente de répartir les mots entre les lignes de paragraphe pour garder le champ droit du paragraphe ShiftRestOfLine décale le reste de la ligne en fonction de la variation de la longueur du texte ; la longueur de la ligne peut être modifiée Valeur par défaut : ShiftRestOfLine"
type: docs
weight: 11210
url: /fr/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## TextReplaceOptions.ReplaceAdjustment enumeration

Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. None - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AdjustSpaceWidth - tente d'ajuster les espaces entre les mots pour conserver la longueur de la ligne ; WholeWordsHyphenation - tente de répartir les mots entre les lignes de paragraphe pour garder le champ droit du paragraphe ; ShiftRestOfLine - décale le reste de la ligne en fonction de la variation de la longueur du texte, la longueur de la ligne peut être modifiée ; La valeur par défaut est ShiftRestOfLine.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Aucune action, le texte remplacé peut chevaucher le reste de la ligne |
| AdjustSpaceWidth | `1` | Essaie d'ajuster les espaces entre les mots pour conserver la longueur de la ligne |
| WholeWordsHyphenation | `2` | Essaie de répartir les mots entre les lignes du paragraphe pour conserver le champ droit du paragraphe |
| IsFormFillingMode | `4` | Essaie de répartir les mots dans l'espace blanc disponible en utilisant la largeur du paragraphe. Si le texte déborde, il sera masqué. |
| ShiftRestOfLine | `8` | (Par défaut) Décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée |

### Voir aussi

* class [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


