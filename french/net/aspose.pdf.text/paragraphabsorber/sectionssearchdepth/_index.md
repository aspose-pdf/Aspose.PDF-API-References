---
title: SectionsSearchDepth
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles déléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement en-têtes paragraphes etc. et trois recherches pour les sections divisées verticalement ceux colonnes.
type: docs
weight: 40
url: /fr/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

Obtient ou définit la valeur qui indique combien de fois des recherches séquentielles d'éléments de structure plus fins seront effectuées. La profondeur de recherche par défaut est de 3. Cela signifie trois recherches pour les sections divisées horizontalement (en-têtes, paragraphes, etc.) et trois recherches pour les sections divisées verticalement ceux (colonnes).

```csharp
public int SectionsSearchDepth { get; set; }
```

### Remarques

L'augmentation de cette valeur peut entraîner une diminution mineure des performances sans changement visible dans le résultat de la recherche. La diminution de cette valeur peut entraîner une détermination incorrecte des paragraphes dans les sections. Nous ne recommandons pas de définir une valeur inférieure à la valeur par défaut si vous ne l'êtes pas désir d'obtenir uniquement des éléments "bruts" de la structure de la page.

### Voir également

* class [ParagraphAbsorber](../../paragraphabsorber)
* espace de noms [Aspose.Pdf.Text](../../paragraphabsorber)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->