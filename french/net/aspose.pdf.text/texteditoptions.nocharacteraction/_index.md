---
title: "Énumération TextEditOptions.NoCharacterAction"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.Text.TextEditOptionsNoCharacterAction. Action à exécuter si la police ne contient pas le caractère requis"
type: docs
weight: 11040
url: /fr/net/aspose.pdf.text/texteditoptions.nocharacteraction/
---
## TextEditOptions.NoCharacterAction enumeration

Action à effectuer si la police ne contient pas le caractère requis

```csharp
public enum NoCharacterAction
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| ThrowException | `0` | Lancer une exception |
| UseStandardFont | `1` | Remplacez la police par une police standard qui contient le caractère requis |
| ReplaceAnyway | `2` | Remplacez le texte de toute façon sans substitution de police |
| ReplaceFonts | `3` | Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit les étapes suivantes : 1. Si l'utilisateur définit explicitement la propriété Font, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via les [`Sources`](../fontrepository/sources/). 3. Analyser le texte pour identifier son alphabet ou son script et suggérer les noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système toute police capable d'afficher les caractères requis. |
| UseCustomReplacementFont | `4` | Remplace la police par la police de remplacement définie |

### Voir aussi

* class [TextEditOptions](../texteditoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


