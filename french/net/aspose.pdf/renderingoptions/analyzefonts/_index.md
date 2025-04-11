---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: Propriété RenderingOptions. Remplace les polices si nécessaire pour garantir que tous les caractères du texte peuvent être affichés. L'algorithme de substitution de polices suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifiez si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, recherchez parmi les polices ajoutées via le !:FontRepository.Sources. 3. Analysez le texte pour identifier son alphabet ou son écriture et suggérez des noms de polices en conséquence. Essayez de localiser et d'utiliser ces polices à partir du système. 4. En dernier recours, recherchez dans le système toute police capable d'afficher les caractères requis.
type: docs
weight: 20
url: /fr/net/aspose.pdf/renderingoptions/analyzefonts/
---
## Propriété RenderingOptions.AnalyzeFonts

Remplace les polices si nécessaire pour garantir que tous les caractères du texte peuvent être affichés. L'algorithme de substitution de polices suit ces étapes : 1. Si l'utilisateur définit explicitement la propriété DefaultFontName, vérifiez si la police spécifiée peut afficher les caractères souhaités. 2. Si aucune police définie par l'utilisateur n'est définie, recherchez parmi les polices ajoutées via le !:FontRepository.Sources. 3. Analysez le texte pour identifier son alphabet ou son écriture et suggérez des noms de polices en conséquence. Essayez de localiser et d'utiliser ces polices à partir du système. 4. En dernier recours, recherchez dans le système toute police capable d'afficher les caractères requis.

```csharp
public bool AnalyzeFonts { get; set; }
```

### Voir aussi

* classe [RenderingOptions](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)