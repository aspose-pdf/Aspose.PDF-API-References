---
title: Enum TextEditOptions.NoCharacterAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Action à effectuer si la police ne contient pas le caractère requis
type: docs
weight: 10860
url: /fr/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## Énumération TextEditOptions.NoCharacterAction

Action à effectuer si la police ne contient pas le caractère requis

```csharp
public enum NoCharacterAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ThrowException | `0` | Lancer une exception |
| UseStandardFont | `1` | Remplacer la police par une police standard qui contient le caractère requis |
| ReplaceAnyway | `2` | Remplacer le texte de toute façon sans substitution de police |
| ReplaceFonts | `3` | Remplace les polices si nécessaire pour s'assurer que tous les caractères du texte peuvent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété Font, vérifiez si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, recherchez parmi les polices ajoutées via les [`Sources`](../fontrepository/sources/). 3. Analysez le texte pour identifier son alphabet ou son écriture et suggérez des noms de polices en conséquence. Essayez de localiser et d'utiliser ces polices à partir du système. 4. En dernier recours, recherchez dans le système toute police capable d'afficher les caractères requis. |
| UseCustomReplacementFont | `4` | Remplacer la police par la police de remplacement définie |

### Voir aussi

* classe [TextEditOptions](../texteditoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)