---
title: TextFragmentAbsorber.TextFragments
second_title: Aspose.PDF for .NET API Reference
description: Proprietà TextFragmentAbsorber. Ottiene la collezione delle occorrenze di ricerca presentate con oggetti TextFragment
type: docs
weight: 90
url: /it/net/aspose.pdf.text/textfragmentabsorber/textfragments/
---
## Proprietà TextFragmentAbsorber.TextFragments

Ottiene la collezione delle occorrenze di ricerca presentate con oggetti [`TextFragment`](../../textfragment/).

```csharp
public TextFragmentCollection TextFragments { get; set; }
```

## Esempi

L'esempio dimostra come trovare testo nella prima pagina del documento PDF e sostituire tutte le occorrenze di ricerca con nuovo testo.

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

### Vedi Anche

* classe [TextFragmentCollection](../../textfragmentcollection/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)