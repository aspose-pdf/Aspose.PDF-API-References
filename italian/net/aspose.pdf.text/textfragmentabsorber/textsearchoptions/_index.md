---
title: "TextFragmentAbsorber.TextSearchOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà TextFragmentAbsorber. Ottiene o imposta le opzioni di ricerca. Le opzioni consentono la ricerca mediante espressioni regolari."
type: docs
weight: 110
url: /it/net/aspose.pdf.text/textfragmentabsorber/textsearchoptions/
---
## TextFragmentAbsorber.TextSearchOptions property

Ottiene o imposta le opzioni di ricerca. Le opzioni consentono la ricerca usando espressioni regolari.

```csharp
public TextSearchOptions TextSearchOptions { get; set; }
```

## Esempi

L'esempio dimostra come eseguire la ricerca di testo usando le espressioni regolari.

```csharp
// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea un oggetto TextFragmentAbsorber
TextFragmentAbsorber absorber = new TextFragmentAbsorber();

// Fai in modo che l'assorbitore cerchi tutte le parole che iniziano con 'h' e terminano con 'o' usando un'espressione regolare.
absorber.Phrase = @"h\w*?o";
absorber.TextSearchOptions = new TextSearchOptions(true);

// dovremmo trovare la parola "hello" e sostituirla con "Hi"
doc.Pages[1].Accept(absorber);
absorber.TextFragments[1].Text = "Hi"; 

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


