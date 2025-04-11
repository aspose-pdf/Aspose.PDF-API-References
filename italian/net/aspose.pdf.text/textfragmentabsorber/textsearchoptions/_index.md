---
title: TextFragmentAbsorber.TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di TextFragmentAbsorber. Ottiene o imposta le opzioni di ricerca. Le opzioni abilitano la ricerca utilizzando espressioni regolari
type: docs
weight: 110
url: /it/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## Proprietà TextFragmentAbsorber.TextSearchOptions

Ottiene o imposta le opzioni di ricerca. Le opzioni abilitano la ricerca utilizzando espressioni regolari.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Esempi

L'esempio dimostra come eseguire la ricerca di testo utilizzando espressioni regolari.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// make the absorber to search all words starting 'h' and ending 'o' using regular expression.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// we should find "hello" word and replace it with "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)