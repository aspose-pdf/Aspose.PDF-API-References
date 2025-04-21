---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: Propriété de ParagraphAbsorber. Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement et trois recherches pour celles divisées verticalement.
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## Propriété ParagraphAbsorber.SectionsSearchDepth

Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles pour des éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour celles divisées verticalement (colonnes).

```csharp
public int SectionsSearchDepth { get; set; }
```

## Remarques

L'augmentation de cette valeur peut entraîner une légère diminution des performances sans changements visibles dans le résultat de la recherche. La diminution de cette valeur peut entraîner une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne souhaitez obtenir que des éléments 'bruts' de la structure de la page.

### Voir aussi

* classe [ParagraphAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)