---
title: TextFragmentAbsorber.Phrase
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextFragmentAbsorber. Ottiene o imposta la frase che il TextFragmentAbsorber cerca nel documento o nella pagina PDF
type: docs
weight: 50
url: /it/net/aspose.pdf.text/textfragmentabsorber/phrase/
---
## Proprietà TextFragmentAbsorber.Phrase

Ottiene o imposta la frase che il [`TextFragmentAbsorber`](../) cerca nel documento o nella pagina PDF.

```csharp
public string Phrase { get; set; }
```

## Esempi

L'esempio dimostra come eseguire la ricerca di testo più volte e effettuare sostituzioni di testo.

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

### Vedi Anche

* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)