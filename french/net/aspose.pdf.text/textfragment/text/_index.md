---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragment. Obtient ou définit l'objet texte de type String que représente l'objet TextFragment
type: docs
weight: 130
url: /fr/net/aspose.pdf.text/textfragment/text/
---
## Propriété TextFragment.Text

Obtient ou définit l'objet texte de type String que représente l'objet [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## Exemples

L'exemple démontre comment rechercher un texte et remplacer la première occurrence représentée par l'objet [`TextFragment`](../).

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Voir aussi

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragment](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)