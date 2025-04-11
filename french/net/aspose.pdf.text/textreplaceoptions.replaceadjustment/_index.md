---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Enum TextReplaceOptions.ReplaceAdjustment d'Aspose.Pdf.Text. Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. Aucune - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AjusterLargeurEspace - essaie d'ajuster les espaces entre les mots pour maintenir la longueur de la ligne ; HyphénationMotsEntiers - essaie de distribuer les mots entre les lignes de paragraphe pour garder le champ droit du paragraphe ; DécalerResteDeLaLigne - décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée ; La valeur par défaut est DécalerResteDeLaLigne.
type: docs
weight: 11020
url: /fr/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Énumération TextReplaceOptions.ReplaceAdjustment

Détermine l'action qui sera effectuée après le remplacement d'un fragment de texte par un texte plus court. Aucune - aucune action, le texte remplacé peut chevaucher le reste de la ligne ; AjusterLargeurEspace - essaie d'ajuster les espaces entre les mots pour maintenir la longueur de la ligne ; HyphénationMotsEntiers - essaie de distribuer les mots entre les lignes de paragraphe pour garder le champ droit du paragraphe ; DécalerResteDeLaLigne - décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée ; La valeur par défaut est DécalerResteDeLaLigne.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Aucune | `0` | Aucune action, le texte remplacé peut chevaucher le reste de la ligne |
| AjusterLargeurEspace | `1` | Essaie d'ajuster les espaces entre les mots pour maintenir la longueur de la ligne |
| HyphénationMotsEntiers | `2` | Essaie de distribuer les mots entre les lignes de paragraphe pour garder le champ droit du paragraphe |
| ModeRemplissageFormulaire | `4` | Essaie de répartir les mots dans l'espace blanc disponible en utilisant la largeur du paragraphe. Si le texte déborde, il sera masqué. |
| DécalerResteDeLaLigne | `8` | (Par défaut) Décale le reste de la ligne en fonction de la longueur changeante du texte, la longueur de la ligne peut être modifiée |

### Voir aussi

* classe [TextReplaceOptions](../textreplaceoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)