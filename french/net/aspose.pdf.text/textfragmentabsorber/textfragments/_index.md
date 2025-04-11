---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragmentAbsorber. Obtient la collection des occurrences de recherche qui sont présentées avec des objets TextFragment
type: docs
weight: 90
url: /fr/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Propriété TextFragmentAbsorber.TextFragments

Obtient la collection des occurrences de recherche qui sont présentées avec des objets [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Exemples

L'exemple démontre comment trouver du texte sur la première page du document PDF et remplacer toutes les occurrences de recherche par du nouveau texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)