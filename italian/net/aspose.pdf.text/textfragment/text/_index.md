---
title: TextFragment.Text
second_title: Aspose.PDF for .NET API Reference
description: Proprietà TextFragment. Ottiene o imposta l'oggetto String di testo che l'oggetto TextFragment rappresenta
type: docs
weight: 130
url: /it/net/aspose.pdf.text/textfragment/text/
---
## Proprietà TextFragment.Text

Ottiene o imposta l'oggetto String di testo che l'oggetto [`TextFragment`](../) rappresenta.

```csharp
public string Text { get; set; }
```

## Esempi

L'esempio dimostra come cercare un testo e sostituire la prima occorrenza rappresentata con l'oggetto [`TextFragment`](../).

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

### Vedi Anche

* classe [TextFragmentAbsorber](../../textfragmentabsorber/)
* classe [Document](../../../aspose.pdf/document/)
* classe [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)