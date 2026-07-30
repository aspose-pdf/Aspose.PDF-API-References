---
title: "RenderingOptions.AnalyzeFonts"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété RenderingOptions. Remplace les polices si nécessaire afin de garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution des polices suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher parmi les polices ajoutées via FontRepository.Sources. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer les noms de polices en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système une police capable d'afficher les caractères requis."
type: docs
weight: 20
url: /fr/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts property

Remplace les polices si nécessaire pour garantir que tous les caractères du texte puissent être affichés. L'algorithme de substitution de police suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifier si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, rechercher les polices ajoutées via le !:FontRepository.Sources. 3. Analyser le texte pour identifier son alphabet ou son script et suggérer les noms de police en conséquence. Tenter de localiser et d'utiliser ces polices depuis le système. 4. En dernier recours, rechercher dans le système une police capable d'afficher les caractères requis.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Voir aussi

* class [RenderingOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


