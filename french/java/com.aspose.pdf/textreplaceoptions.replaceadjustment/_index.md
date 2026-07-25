---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un plus court. None - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AdjustSpaceWidth - essaie de."
type: docs
weight: 5270
url: /fr/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. None - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AdjustSpaceWidth - tente d'ajuster les espaces entre les mots pour conserver la longueur de la ligne ; WholeWordsHyphenation - tente de répartir les mots entre les lignes du paragraphe pour conserver le champ droit du paragraphe ; ShiftRestOfLine - décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée ; La valeur par défaut est ShiftRestOfLine.

## Champs

| Champ | Description |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Essaye d'ajuster les espaces entre les mots pour conserver la longueur de la ligne |
| [IsFormFillingMode](#IsFormFillingMode) | Essaye de répartir les mots dans l'espace blanc disponible en utilisant la largeur du paragraphe. Si le texte déborde, il sera masqué. |
| [None](#None) | Aucune action, le texte remplacé peut chevaucher le reste de la ligne |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Par défaut) Décale le reste de la ligne en fonction de la variation de la longueur du texte, la longueur de la ligne peut être modifiée |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Essaye de répartir les mots entre les lignes du paragraphe pour conserver la marge droite du paragraphe |

## Méthodes

| Méthode | Description |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Essaye d'ajuster les espaces entre les mots pour conserver la longueur de la ligne

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Essaye de répartir les mots dans l'espace blanc disponible en utilisant la largeur du paragraphe. Si le texte déborde, il sera masqué.

### None {#None}
```
public static final int None
```

Aucune action, le texte remplacé peut chevaucher le reste de la ligne

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Par défaut) Décale le reste de la ligne en fonction de la variation de la longueur du texte, la longueur de la ligne peut être modifiée

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Essaye de répartir les mots entre les lignes du paragraphe pour conserver la marge droite du paragraphe

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeau |  |  |
| flagToCheck |  |  |
