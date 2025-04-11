---
title: Font.IsSubset
second_title: Aspose.PDF for .NET API Reference
description: Propriété de la police. Obtient ou définit une valeur qui indique si la police est un sous-ensemble. La police basée sur IFont sera automatiquement un sous-ensemble et intégrée
type: docs
weight: 70
url: /fr/net/aspose.pdf.text/font/issubset/
---
## Propriété Font.IsSubset

Obtient ou définit une valeur qui indique si la police est un sous-ensemble. La police basée sur IFont sera automatiquement un sous-ensemble et intégrée

```csharp
public bool IsSubset { get; set; }
```

## Exemples

L'exemple démontre comment rechercher du texte sur la première page et obtenir la valeur qui indique si la police est un sous-ensemble.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsSubset)
   Console.Out.WriteLine("the font is a subset");
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [Font](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)