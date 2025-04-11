---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextFragmentAbsorber. Obtient ou définit la phrase que le TextFragmentAbsorber recherche dans le document ou la page PDF
type: docs
weight: 50
url: /fr/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Propriété TextFragmentAbsorber.Phrase

Obtient ou définit la phrase que le [`TextFragmentAbsorber`](../) recherche dans le document ou la page PDF.

```csharp
public string Phrase { get; set; }
```

## Exemples

L'exemple démontre comment effectuer une recherche de texte plusieurs fois et effectuer des remplacements de texte.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello");

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi";

// search another word and replace it
absorber.Phrase = "world";

doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "John";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Voir aussi

* classe [TextFragmentAbsorber](../)
* espace de noms [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)